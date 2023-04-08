<template>
    <div>
        <h1>{{data}}{{ msg }}</h1>
    </div>
    
</template>

<script>
export default {
    name:' HomeMy',
    props : {
        data : String,
        msg : String
    }
}
</script>