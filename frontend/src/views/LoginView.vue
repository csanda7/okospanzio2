<template>
    <div>
        <p class="display-1 text-center">Login page</p>
        <navbar/>
        <div class="container">
            <login-form/>
        </div>
    </div>
</template>

<script setup>
    import navbar from '../components/NavbarComponent.vue';
    import LoginForm from '../components/LoginFormComponent.vue';
</script>

<style lang="scss" scoped>

</style>