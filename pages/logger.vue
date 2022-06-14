<template>
    <div class="signIn">
        <accordion />
        <hr>
        <sign-in />
    </div>
</template>

<script>
import { Component, Vue } from 'nuxt-property-decorator';

import SignIn from '@/components/signIn';
import Accordion from '@/components/accordion'

export default @Component ({
    name: 'LogInPage',
    components: {
        SignIn,
        Accordion,
    }
})

class LogInPage extends Vue {
    
}

</script>

<style>
.signIn {
    margin: 0 auto;
    max-width: 500px;
} 

</style>

