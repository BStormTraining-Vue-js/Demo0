<script>
export default {
    data() {
        return {
            count: 0
        }
    },
    methods: {
        increase() {
            this.count++;
        }
    }
}
</script>

<template>
    <p>{{ count }}</p>
    <button @click="increase">Click Me</button>
</template>

<style scoped>
p {
    font-weight: bold;   
}
</style>