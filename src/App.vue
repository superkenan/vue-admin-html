<template>
    <div id="app">
        <router-view/>
    </div>
</template>

<script>
export default {
    name: "app"
};
</script>

<style rel="stylesheet/scss" lang="scss">
@import "./styles/base";
html {
    height: 100%;
}
body {
    height: 100%;
    overflow: hidden;
}
#app {
    height: 100%;
}

.menu .svg-icon {
    font-size: 20px;
    margin-right: 5px;
}
</style>
