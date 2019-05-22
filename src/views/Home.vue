<template>
    <my-page title="团队">
        <div class="common-container container">
            <ui-article>
                <h2>团队介绍</h2>
                <p>云设团队是一个基于 <a href="https://github.com/yunser" target="_blank">GitHub</a> 的互联网团队，任何人都可以参与进来，无需申请。</p>
                <h2>参与流程</h2>
                <p>0. 首先，你要有一个 IDEA，明确自己想要做什么类型的项目。</p>
                <p>1. 在 <a href="https://github.com/yunser" target="_blank">GitHub</a> 上找到你感兴趣的项目，Fork 下来。
                    或者 <a href="https://github.com/yunser/team-front/issues" target="_blank">申请</a> 一个新的类型的项目。</p>
                <p>2. 了解团队的相关<router-link to="/standard">规范</router-link>。</p>
                <p>3. 设计或直接开发项目。</p>
                <p>4. Pull Request。</p>
                <p><del>5. 弃坑</del></p>
            </ui-article>
        </div>
    </my-page>
</template>

<script>
    export default {
        data () {
            return {
            }
        }
    }
</script>

<style scoped>
</style>
