<template>
    <div class="d-flex flex-column flex-shrink-0 p-3 text-white bg-dark" style="width: 280px;">
        <a href="/" class="d-flex align-items-center mb-3 mb-md-0 me-md-auto text-white text-decoration-none">
            <svg class="bi me-2" width="40" height="32"><use xlink:href="#bootstrap"></use></svg>
            <span class="fs-4">Sidebar components</span>
        </a>
        <hr>
        <ul class="nav nav-pills flex-column mb-auto">
            <li class="nav-item">
                <nuxtLink exact active-class="active" class="nav-link text-white" to="/">
                    <svg class="bi me-2" width="16" height="16"><use xlink:href="@/node_modules/bootstrap-icons/bootstrap-icons.svg#house"></use></svg>
                    Home
                </nuxtLink>
            </li>
            <li>
                <nuxtLink active-class="active" class="nav-link text-white" to="/logger">
                    <svg class="bi me-2" width="16" height="16"><use xlink:href="@/node_modules/bootstrap-icons/bootstrap-icons.svg#arrow-right-square"></use></svg>
                    Log in page
                </nuxtLink>
            </li>
        </ul>
        <hr>
  </div>

</template>
  
<script>
import { Component, Vue } from 'nuxt-property-decorator';

export default @Component({
  name: 'Sidebar',
  components: {}
})

class Sidebar extends Vue {
  
}
</script>

<style>
    svg {
        color: white;
    }
</style>