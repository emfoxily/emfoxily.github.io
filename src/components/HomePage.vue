<template>
    
    <container>
        <NavBar />
        <div class="header">
            
        </div>
    </container>
</template>

<script>

import NavBar from './NavBar.vue'

export default {
    name: 'HomePage',
    components: {
        NavBar
    },
    props: {
        msg: String
    }
}
</script>

<style scoped>
    
    container {
        display: block;
        margin: 0 auto;
        /* background-color: black; */
        width: 50vw;
        height: auto;
    }

    .header {
        display: block;
        background-color: rgb(252, 252, 252);
        width: 100%;
        height: 50vh;
        border-radius: .65em;
    }

</style>
