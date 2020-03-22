<template>
    <div class="container-fluid">
        <div class="row">
            <div class="col">
                <h1 class="text-center display-6">Far Flung Visits</h1>
            </div>
        </div>
        <div class="row">
            <div class="col">
                <form class="form-signin">
                      <div class="checkbox mb-3">
                        <label>
                          <input type="checkbox" value="remember-me"> I want to visit
                        </label>
                      </div>
                      <div class="checkbox mb-3">
                        <label>
                          <input type="checkbox" value="remember-me"> I want to make a visit
                        </label>
                      </div>
                    <router-link to="/signup" tag="button" class="btn btn-lg btn-primary" type="submit">Cancel</router-link>
                    <router-link to="/signup3" tag="button" class="btn btn-lg btn-secondary" type="submit">Next</router-link>
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

        }
    }
</script>


<style>
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
</style>