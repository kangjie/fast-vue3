<template>
    <a-layout-footer class="footer">
<!--        <SvgIcon name="svg-github" size="24" style="margin-right: 10px;" />-->
        <router-link to="">
          © 1983-2021 Advantech Co., Ltd. All rights reserved.
        </router-link>
    </a-layout-footer>
</template>

<script setup lang="ts">
import SvgIcon from '@components/SvgIcon/index.vue'
</script>

<style lang="less" scoped>
.footer {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 40px;
    color: var(--color-text-2);
    text-align: center;
}
</style>
