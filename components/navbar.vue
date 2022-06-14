<template>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
        <nuxtLink class="navbar-brand" to="/">
            Navbar components
        </nuxtLink>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                <li class="nav-item">
                    <nuxtLink exact active-class="active" class="nav-link" to="/">
                        Home
                    </nuxtLink>
                </li>
                <li class="nav-item">
                    <nuxtLink active-class="active" class="nav-link" to="/logger">
                        Sign-in
                    </nuxtLink>
                </li>
            </ul>
        </div>
    </div>
    </nav>
</template>

<script>
import { Component, Vue } from 'nuxt-property-decorator';

export default @Component({
  name: 'Navbar',
  components: {}
})

class Navbar extends Vue {
  
}
</script>