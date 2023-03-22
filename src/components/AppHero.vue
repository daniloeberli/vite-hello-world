<script>
export default {
    data() {
        return {
            message: 'Jumbo: Lorem ipsum dolor sit amet, consectetur'
        }
    }
}
</script>

<template>
    <div>
        <p>{{ message }}</p>
    </div>
</template>

<style scoped>
p {
    font-size: 2rem;
}

div {
    background-color: coral;
    height: 200px;
    display: flex;
    align-items: center;
    padding: 40px;
}
</style>