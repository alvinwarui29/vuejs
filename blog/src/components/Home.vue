<template>
    <div>
        <h1 v-if="show">Conditional rendering</h1>
        <h1 v-else>Else side</h1>
        <button v-on:click="display" >Toggle</button>
    </div>
    
</template>

<script>
export default {
    name:' HomeMy',
    props : {
        data : String,
        msg : String
    },
    data(){
        return{
            show:true
        }

    },
    methods : {
        display(){
            this.show = !this.show
        }
    }
}
</script>