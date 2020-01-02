<template>
    <div>
        <h3>Current count:{{count}}</h3>
        <input type="button" value="+" @click="incrementCount"/>
    </div>
</template>

<script>
    export default{
        name:'Counter',
        data(){
            return{
                count:0
            }
        },
        methods:{
            incrementCount(){
                this.count++;
            }
        }

    }
</script>

<style scoped>


</style>