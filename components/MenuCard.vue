<template lang="">
    <div>
        <img class="h-96 mx-auto" :src="menu.image" alt="">
        <p class="text-center ">{{ menu.id }}</p>
        <h2 class="text-center ">{{ menu.name }}</h2>
        <h3 class="text-center ">{{ menu.price }} Baht</h3>
    </div>
</template>
<script>
export default {
    name: 'MenuCard',
    props: {
        menu: Object
    }
}
</script>
<style lang="">
    
</style>