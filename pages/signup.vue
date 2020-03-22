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
                    <div class="form-group">
                        <label for="nameInput">Name (required)</label>
                        <input type="text" class="form-control" id="nameInput" aria-describedby="nameHelp" placeholder="Enter name">
                    </div>
                    <div class="form-group">
                        <label for="phoneInput">Phone number (required)</label>
                        <input type="text" class="form-control" id="phoneInput" aria-describedby="phoneHelp" placeholder="Enter phone number">
                    </div>
                    <div class="form-group">
                        <label for="locationInput">Location</label>
                        <input type="text" class="form-control" id="locationInput" aria-describedby="locationHelp" placeholder="Enter location">
                    </div>
                    <router-link to="/" tag="button" class="btn btn-lg btn-primary" type="submit">Cancel</router-link>
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
</style>