<template>
    <h1 class="text-3xl font-bold underline">Hello world!</h1>
    <n-button type="primary">Primary Button</n-button>
    <div class="home-wrap">
        <h1>Nuxt3--这是我们的首页</h1>
    </div>
    <button class="btn-primary">悬停按钮</button>
</template>

<script setup lang="ts">
import { NButton } from "naive-ui";
</script>

<style lang="scss" scoped>
.btn-primary {
    @apply tw-bg-blue-500 tw-rounded-md tw-px-4 tw-py-2 tw-text-white;
    &:hover {
        @apply tw-bg-blue-800;
        color: rgb(255, 255, 105);
    }
}

.home-wrap {
    height: 200px;
    background-color: $bgColor;
    color: $theme;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 50px;
}
</style>
