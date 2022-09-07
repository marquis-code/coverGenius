<template>
    <div>
        <b-navbar toggleable="lg" type="dark" variant="light">
            <b-container class="px-1 px-lg-0">
                <b-navbar-brand href="#"><img src="@/static/img/logo.svg" alt="logo" /></b-navbar-brand>

                <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

                <b-collapse id="nav-collapse" is-nav class="">
                    <b-navbar-nav>
                        <b-nav-item href="#"><span class="text-dark">For Individuals</span></b-nav-item>
                        <b-nav-item href="#"><span class="text-dark">For Business</span></b-nav-item>
                    </b-navbar-nav>

                      <b-navbar-nav class="ml-auto">
                            <b-nav-item href="#"><span class="text-dark">Claims</span></b-nav-item>
                            <b-nav-item href="#"><span class="text-dark">Resources</span></b-nav-item>
                            <b-nav-item href="#"><span class="text-dark">Company</span></b-nav-item>
                    </b-navbar-nav>

                  
                    <b-navbar-nav class="ml-auto">
                        <b-nav-form>
                            <b-button size="md" class="my-2 my-sm-0 mr-2" type="submit">Login</b-button>
                            <b-button size="md" class="my-2 my-sm-0 ml-2" type="submit">Get Covered</b-button>
                        </b-nav-form>

                    </b-navbar-nav>
                </b-collapse>
            </b-container>
        </b-navbar>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
button {
    background-color: #439687;
    border: none;
    outline: none;
}
</style>