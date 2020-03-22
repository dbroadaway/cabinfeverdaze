<template class="container-fluid">
    <div>
        <div class="row">
            <div class="col">
                <h1 class="text-center display-6">Far Flung Visits</h1>
            </div>
        </div>
        <div class="row">
            <div class="col">
                <p class="lead">How are you doing?</p>
                <form class="form-signin">
                      <div class="checkbox mb-3">
                        <label>
                          <input type="checkbox" value="remember-me"> I am in a nursing home
                        </label>
                      </div>
                    <div class="checkbox mb-3">
                        <label>
                            <input type="checkbox" value="remember-me"> I have kids and need a break
                        </label>
                    </div>
                    <div class="checkbox mb-3">
                        <label>
                            <input type="checkbox" value="remember-me"> I live in my home by myself
                        </label>
                    </div>
                    <div class="checkbox mb-3">
                        <label>
                            <input type="checkbox" value="remember-me"> I am in quarantine
                        </label>
                    </div>
                    <div class="checkbox mb-3">
                        <label>
                            <input type="checkbox" value="remember-me"> I am in the hospital
                        </label>
                    </div>
                    <div class="checkbox mb-3">
                        <label>
                            <input type="checkbox" value="remember-me"> I want some company
                        </label>
                    </div>
                    <div class="form-group">
                        <label for="otherSituation">Other</label>
                        <input type="text" class="form-control" id="otherSituation" aria-describedby="emailHelp" placeholder="Enter email">
                    </div>
                    <router-link to="/signup2" tag="button" class="btn btn-lg btn-primary" type="submit">Cancel</router-link>
                    <router-link to="/signup2" tag="button" class="btn btn-lg btn-secondary" type="submit">Next</router-link>
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