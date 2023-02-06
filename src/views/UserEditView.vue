<template>
    <div>
        Usuário
        <p>Id {{ $route.params.id }}</p>
    </div>

    <button @click="login()">
        Login
    </button>
</template>

<script>
export default {
    methods: {
        login() {
            this.$router.push('/about');
            console.log('chegou');
        }
    }
}
</script>