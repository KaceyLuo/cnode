<template>
    <div class="header">
        <router-link :to="{ name: 'root' }">
            <img src="../assets/cnodejs_light.svg" alt="" sizes="" srcset="">

        </router-link>
        <ul>
            <li><a href="#">首页</a></li>
            <li><a href="https://cnodejs.org/getstart">新手入门</a></li>
            <li><a href="https://cnodejs.org/api">API</a></li>
            <li><a href="https://cnodejs.org/about">关于</a></li>
            <li><a
                    href="https://github.com/login/oauth/authorize?response_type=code&redirect_uri=https%3A%2F%2Fcnodejs.org%2Fauth%2Fgithub%2Fcallback&client_id=0625d398dd9166a196e9">注册</a>
            </li>
            <li><a href="https://cnodejs.org/signin">登录</a></li>



        </ul>

    </div>
</template>

<script>
export default {
    name: "Header"
}

</script>
<!-- scoped只对当前页面有效 -->
<style scoped>
.header {
    background-color: #5a5555;
    height: 50px;
}

img {
    max-width: 120px;
    margin-left: 50px;
    margin-top: 10px;
}

ul {
    list-style: none;
    float: right;
    margin: 4px;
}

li {
    display: inline-block;
    padding: 10px 15px;
}

a {
    text-decoration: none;
    color: #ccc;
    font-size: 14px;
    text-shadow: none;
}
</style>