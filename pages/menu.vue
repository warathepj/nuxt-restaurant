<template lang="">
    <div class="m-auto space-y-8">
        <Nav />
        <h1 class="text-center text-2xl">Menu</h1>
        <div class="flex flex-col gap-y-16">
           <MenuCard
            v-for="menu in menus"
            v-bind:key="menu.id"
            :menu="menu"
            />
        </div>
        <Footer />

    </div>
</template>
<script>
import MenuCard from '~/components/MenuCard.vue'

export default {
    name: 'Menu',
    data () {
        return {
            menus: [
                {
                    id: 1, 
                    name: "Burger", 
                    price: 150, 
                    image: "https://images.unsplash.com/photo-1618538768832-fbd192fe94fc?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=962&q=80"
                },
                {
                    id: 2, 
                    name: "Noodle", 
                    price: 100, 
                    image: "https://images.unsplash.com/photo-1612927601601-6638404737ce?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=387&q=80"
                },
                {
                    id: 3, 
                    name: "Cake", 
                    price: 110, 
                    image: "https://images.unsplash.com/photo-1589385973461-eaa9b0ae2830?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=387&q=80"
                },
                {
                    id: 4, 
                    name: "Coffee", 
                    price: 90, 
                    image: "https://images.unsplash.com/photo-1557142046-c704a3adf364?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=387&q=80"
                }
            ],
        }
    },
}
</script>
<style lang="">
    
</style>