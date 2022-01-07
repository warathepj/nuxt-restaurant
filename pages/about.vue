<template lang="">
    <div>
        <Nav />
        <h1 class="text-center">
            {{ title }}
        </h1>
        <p>{{ description }}</p>
        <p class="text-center">
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Alias,
            perferendis maiores dolor dicta quis blanditiis voluptas, 
            delectus molestiae veritatis odio asperiores tempora cumque? Debitis aspernatur
            molestias ipsam nisi reprehenderit quisquam.
            Impedit sint suscipit tempora, eius temporibus a debitis molestiae iste obcaecati aut.
            Quasi atque itaque voluptates eveniet nisi magnam dolores enim fugit voluptatem,
            assumenda ut architecto officiis, neque vitae totam!
        </p>
        <Footer />

    </div>
</template>
<script>
export default {
    name: 'About',
    data() {
        return {
            title: "About Us",
            description: ""
        }
    }
}
</script>
<style lang="">
    
</style>