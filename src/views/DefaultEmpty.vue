<template>
    <router-view />
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

@Component({ components: {} })
export default class DefaultEmpty extends Vue { }
</script>
