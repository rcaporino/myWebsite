<template>
  <div class="py-1">
        <b-navbar toggleable="md" type="light" class="nav-header neumorphism">
            <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

            <b-collapse id="nav-collapse" is-nav>
                <b-navbar-brand to="/" v-bind="showMedPlus">
                    <img src="../assets/R.Caporino_logo5.png" alt="logo" class="d-inline-block align-center">
                    
                </b-navbar-brand>
                <b-navbar-nav align="center">
                    <b-nav pills vertical align="center">
                        <b-nav-item vertical align="center" to="/" exact-active-class="active">About Me</b-nav-item>
                    </b-nav>
                    <b-nav pills vertical align="center">
                        <b-nav-item vertical align="center" to="/educationandskills" exact-active-class="active">Education and Skills</b-nav-item>
                    </b-nav>
                    <b-nav pills vertical align="center">
                        <b-nav-item vertical align="center" to="/projects" exact-active-class="active">Projects</b-nav-item>
                    </b-nav>
                    <b-nav pills vertical align="center">
                        <b-nav-item vertical align="center" to="/contactme" exact-active-class="active">Contact Me</b-nav-item>
                    </b-nav>
                    <b-nav pills vertical align="center">
                        <b-nav-item vertical align="center" to="/vuejs" exact-active-class="active">Vuejs</b-nav-item>
                    </b-nav>
                </b-navbar-nav>
            </b-collapse>
        </b-navbar>
  </div>
</template>

<script>
export default {
    data() {
        return {
            showMedPlus: {
                class: "d-none d-md-block"
            }
        }
    }
}
</script>

<style>
.nav-header{
    background-color: #8092ac !important;
}

.active {
    /* background-color: #f59e5d !important; */
    background-color: #405b82 !important;
    color: #e1e1e1 !important;
}

.nav-pills:hover {
    background-color: #bfc8d5 !important;
    border-radius: 5px;
}
</style>