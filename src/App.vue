<template>
    <div class="container mx-auto">
        <Nav />
        <router-view/>
    </div>
</template>

<script>
import Nav from './components/Nav'

export default {
    components: {
        Nav
    }
}
</script>

<style>

</style>