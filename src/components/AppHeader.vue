<script>
    import NavLink from './NavLink.vue';

    export default{
        name: 'AppHeader',
        components:{
            NavLink,
        },

    data(){
        return{
            linkList:[
                {
                    text: 'Home',
                },
                {
                    text: 'Home',
                },
                {
                    text: 'Home',
                }
            ],
        }
    }
}
</script>

<template>
    <header>
        <NavLink v-for="linkObj in linkList"
                :linkElement="linkObj"
        />

    </header>
</template>

<style>

</style>