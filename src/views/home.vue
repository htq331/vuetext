<template>
    <div class="home-container">
        <h1>VUE3数学</h1>
        <hr>
        <Mobanyufa></Mobanyufa>
        <Shuxingbangding></Shuxingbangding>
        <Tiaojianxuanran></Tiaojianxuanran>
        <Liebiaoxuanran></Liebiaoxuanran>
        <Keyguanlizhuangtai></Keyguanlizhuangtai>
        <Shijianchuli></Shijianchuli>
        <Shijianchuancan></Shijianchuancan>
        <Shijianxiushifu></Shijianxiushifu>
        <Shuzubianhuazhence></Shuzubianhuazhence>
        <Jisuanshuxing></Jisuanshuxing>
        <Classbangding></Classbangding>
        <Stylebangding></Stylebangding>
        <Watchzhengting></Watchzhengting>
        <Biaodanshujvbangding></Biaodanshujvbangding>
        <Mobanyinyong></Mobanyinyong>
        <Zujianqiantao></Zujianqiantao>
        <Zujianchuanzhiprops></Zujianchuanzhiprops>
        <PropsjiaoyanA></PropsjiaoyanA>
    </div>
</template>

<script>
import Mobanyufa from '../components/mobanyufa.vue';
import Shuxingbangding from '../components/shuxingbangding.vue';
import Tiaojianxuanran from '../components/tiaojianxuanran.vue';
import Liebiaoxuanran from '../components/liebiaoxuanran.vue';
import Keyguanlizhuangtai from '../components/keyguanlizhuangtai.vue';
import Shijianchuli from '../components/shijianchuli.vue';
import Shijianchuancan from '../components/shijianchuancan.vue';
import Shijianxiushifu from '../components/shijianxiushifu.vue';
import Shuzubianhuazhence from '../components/shuzubianhuazhence.vue';
import Jisuanshuxing from '../components/jisuanshuxing.vue';
import Classbangding from '../components/classbangding.vue';
import Stylebangding from '../components/stylebangding.vue';
// import Watchzhengting from '../components/watchzhengting.vue';
import Biaodanshujvbangding from '../components/biaodanshujvbangding.vue';
// import Biaodanshujvbangding from '../components/biaodanshujvbangding.vue';
// import Watchzhengting from '../components/watchzhengting.vue';
import Watchzhengting from '../components/watchzhengting.vue';
import Mobanyinyong from '../components/mobanyinyong.vue';
import Zujianqiantao from '../components/zujianqiantao.vue';
import PropsjiaoyanA from '../components/propsjiaoyanA.vue';
import Zujianchuanzhiprops from '../components/zujianchuanzhiprops.vue';

export default {
    name: 'home',
    components: {
        Mobanyufa,
        Shuxingbangding,
        Tiaojianxuanran,
        Liebiaoxuanran,
        Keyguanlizhuangtai,
        Shijianchuancan,
        Shijianxiushifu,
        Shuzubianhuazhence,
        Shijianchuli,
        Jisuanshuxing,
        Classbangding,
        Stylebangding,
        Watchzhengting,
        Biaodanshujvbangding,
        Mobanyinyong,
        Zujianqiantao,
        Zujianchuanzhiprops,
        PropsjiaoyanA
    },
}

</script>


<style scoped>
.home-container{
    position: relative;
    z-index: 10;
}

h1 {
    z-index: 11;
    color: aqua;
}
</style>