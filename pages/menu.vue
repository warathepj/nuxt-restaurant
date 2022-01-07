<template lang="">
    <div>
        <Nav />
        Menu
        <div>
            <ul v-for="menu in menus" :key="menu.id">
                <li>{{ menu.id }} {{ menu.name }} {{ menu.price }}</li>
            </ul>
        </div>
    </div>
</template>
<script>
export default {
    name: 'Menu',
    data () {
        return {
            menus: [
                {"id": 1, "name": "A", "price": 35},
                {"id": 2, "name": "B", "price": 40},
                {"id": 3, "name": "C", "price": 45},
                {"id": 4, "name": "D", "price": 50}
            ]
        }
    }
}
</script>
<style lang="">
    
</style>