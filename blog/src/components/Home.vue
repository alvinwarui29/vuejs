<template>
    <div>
        <button v-on:click="hello" >Call hello function</button>
    </div>
    
</template>

<script>
export default {
    name:' HomeMy',
    props : {
        data : String,
        msg : String
    },
    methods : {
        hello(){
            alert("Function called")
        }
    }
}
</script>