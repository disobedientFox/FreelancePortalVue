<template>
    <default-empty />
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import DefaultEmpty from "./views/DefaultEmpty.vue";

@Component({ components: { DefaultEmpty } })
export default class App extends Vue {
    metaInfo: {
        title: 'About Us'
    }
}

</script>

<style lang="scss">
@import "vue-select/src/scss/vue-select.scss";

#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
}

#nav {
    padding: 30px;

    a {
        font-weight: bold;
        color: #2c3e50;

        &.router-link-exact-active {
            color: #42b983;
        }
    }
}
</style>
