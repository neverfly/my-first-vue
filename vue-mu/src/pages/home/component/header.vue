<template>
    <div class="header"> 
        <div class="header-left"><div class="iconfont back-icon">&#xe606;</div></div>
        <div class="header-input"><span class="iconfont">&#xe60b;</span>输入城市/景点/游玩主题</div>
        <div class="header-right">城市<span class="iconfont arrow-icon">&#xe64a;</span></div>
    </div>
</template>
<script>
export default {
    name:'Header'
}
</script>
<style lang="stylus" scoped>
.header
    line-height: 0.86rem
    display:flex
    background: #00bcd4
    color: #fff
    .header-left
        float left
        width: 0.64rem
        .back-icon
            text-align: center
            font-size: 0.4rem
    .header-input
        flex: 1
        background: #fff
        border-radius: .1rem
        margin-top: 0.12rem
        height: 0.64rem
        line-height: 0.64rem
        margin-left:0.2rem
        padding-left: 0.2rem
        color: #ccc
    .header-right
        float: right
        width:1.24rem
        text-align: center
        .arrow-icon
            font-size: 0.24rem

</style>
