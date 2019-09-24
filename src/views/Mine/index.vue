<template>
    <div id="main">
        <Header title="我的喵喵"/>
        <div id="content">
            <Lg></Lg>
        </div>
        <TabBar/>
    </div>
</template>

<script>
    import Header from '@/components/Header'
    import TabBar from '@/components/TabBar'
    import Lg from '@/components/Login'
    export default {
        name : 'Mine',
        components:{
            Header,
            TabBar,
            Lg
        }
    }
</script>

<style scoped>

</style>