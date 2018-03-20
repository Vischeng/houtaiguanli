<template>
<!-- <main> 标签规定文档的主要内容。 -->
<!-- <main> 元素中的内容对于文档来说应当是唯一的。它不应包含在文档中重复出现的内容，比如侧栏、导航栏、版权信息、站点标志或搜索表单。 -->
<!-- 注释：在一个文档中，不能出现一个以上的 <main> 元素。<main> 元素不能是以下元素的后代：<article>、<aside>、<footer>、<header> 或 <nav>。 -->
    <main>
        <h1>
            {{ title }}
        </h1>
    </main>
</template>

<script>
    // 导出组件配置
    export default {
        data () {
            return {
                title:'Hello World!'
            }
        }
    }
</script>

<style scoped>
h1{
    font-size: 30px;
    color: red;
}
</style>