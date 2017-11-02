<template>
    <div id="endorsementfrom">
        <upLoad :data="item" typeArr="image/png,image/jpg,image/gif,image/jpeg"></upLoad>
    </div>
</template>
<script>
    import upLoad from 'upLoad'
    export default {
        props     : ['imgs'],
        components: {
            upLoad
        },
        methods   : {}
    }
</script>
<style scoped lang="less">
    #endorsementfrom {}
</style>