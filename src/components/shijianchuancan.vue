<template>
    <div class="shijianchuancan">
        <h3>事件传参</h3>
        <button @click="count1">add 454</button>
        <p>count is {{ countNum }}</p>

        <button @click="newCount('hello syxy')">newCount 222</button>
        <hr>
    </div>
</template>


<script>
export default {
    name: 'shijianchuanran',
    data() {
        return {
            countNum: 0,
            newCountNum: 20
        }
    },
    methods: {
        count1(e) {
            console.log(e,'45454545456565656565')
        }
    }
}
</script>