<template>
    <nav class="navbar navbar-dark navbar-expand-lg">
        <router-link to="/" class="navbar-brand">
            <img alt="Digital Services Coalition" src="@/assets/irs-dc-logo-white.png" class="logo">
            {{ msg }}
        </router-link>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbar-links" aria-controls="navbar-links" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon">              
            </span>
        </button>
        <div class="collapse navbar-collapse" id="navbar-links">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                    <router-link to="/" class="nav-link">Home
                    <span class="sr-only">(current)</span>
                    </router-link>
                </li>
                <li class="nav-item">
                    <router-link to="/mission" class="nav-link">Mission</router-link>
                </li>
                <li class="nav-item">
                    <router-link to="/story" class="nav-link">About</router-link>
                </li>
                <li class="nav-item">
                    <router-link to="/membership" class="nav-link">Membership</router-link>
                </li>               
                <li class="nav-item">
                    <router-link to="/contact" class="nav-link">Contact</router-link>
                </li>
            </ul>
        </div>
    </nav>
</template>

<script>
export default {
  name: 'Nav',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
    
</style>
