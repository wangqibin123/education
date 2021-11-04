<template>
    <div>
        <wwh></wwh>
        <kuangjia/>
    </div>
</template>
<script>
import wwh from "@/views/wwh.vue";
import kuangjia from './kuangjia/kuang.vue'
export default {
    components:{
        kuangjia,
        wwh
    }
}
</script>

<style lang='scss' scoped>
div{
    width: 100%;
    height: 100%;
    background-color: #F5F7F9;
}
</style>
