<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col">
        <h1 class="text-center display-6">Cabin Fever Daze!</h1>
        <p class="lead">Let's introduce homebound people so that we can interact remotely during the covid-19 shut down.</p>
        <p>We will help connect you, and then you can use your own preferred video conferencing and social tools to connect!</p>
        <hr class="my-4">
      </div>
    </div>
    <div class="row">
      <div class="col">
        <form class="form-signin">
          <div class="form-group">
            <label for="exampleInputEmail">Email address</label>
            <input type="email" class="form-control" id="exampleInputEmail" aria-describedby="emailHelp" placeholder="Enter email">
          </div>
          <div class="form-group">
            <label for="exampleInputPassword">Password</label>
            <input type="password" class="form-control" id="exampleInputPassword" placeholder="Password">
          </div>

          <button class="btn btn-lg btn-primary btn-block" type="submit">Login</button>
          <router-link to="/signup" tag="button" class="btn btn-lg btn-secondary btn-block" type="submit">Sign Up</router-link>
          <a class="links">Forgot password?</a>
          <p class="mt-5 mb-3 text-muted">Cabin Fever Daze ©2020</p>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  },
  methods: {
    signup: function (event) {
      console.log("CLICKED")
      window.location.href = '/signup'
      // this.$router.go('/signup')
    }
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

html,
body {
  height: 100%;
}

body {
  display: -ms-flexbox;
  display: -webkit-box;
  display: flex;
  -ms-flex-align: center;
  -ms-flex-pack: center;
  -webkit-box-align: center;
  align-items: center;
  -webkit-box-pack: center;
  justify-content: center;
  padding-top: 40px;
  padding-bottom: 40px;
  background-color: #f5f5f5;
}

.form-signin {
  width: 100%;
  max-width: 330px;
  padding: 15px;
  margin: 0 auto;
}
.form-signin .checkbox {
  font-weight: 400;
}
.form-signin .form-control {
  position: relative;
  box-sizing: border-box;
  height: auto;
  padding: 10px;
  font-size: 16px;
}
.form-signin .form-control:focus {
  z-index: 2;
}
.form-signin input[type="email"] {
  margin-bottom: -1px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.form-signin input[type="password"] {
  margin-bottom: 10px;
  border-top-left-radius: 0;
  border-top-right-radius: 0;
}

</style>

<style lang="sass">
  .red
    color: red
</style>
