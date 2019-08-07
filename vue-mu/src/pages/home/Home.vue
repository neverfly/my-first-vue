<template>
    <div>
        <homeHeader></homeHeader>
    </div>
</template>
<script>
import homeHeader from './component/header'
export default {
    name:'Home',
    components:{
        homeHeader
    }
}
</script>
<style>
.home{
    color: aqua;
    font-size:50px;
    text-align:center;
}
</style>
