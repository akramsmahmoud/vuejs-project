<template>
<div>
    <h1>Ay kalam <span>{{ msg }}</span></h1>
    </div>    
</template>


<script>
export default {
    data(){
        return{
            msg: 'fady'
        }
    }
}
</script>

<style lang="scss" scoped>
h1{
    color: aqua;
    span{
        color: brown;
        font-weight: bold;
    }
}
</style>