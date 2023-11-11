<script lang="ts">

import { defineComponent } from 'vue';

export default defineComponent({
    name: 'NavBarA',
    setup() {
        return {

        }
    }
})

</script>

<template>
    <div class="nav-bar-box">
        <div class="icons-box">
            <img src="/public/feathers/shopping-bag.svg">
            <img src="/public/feathers/heart.svg">
            <img src="/public/feathers/search.svg">
        </div>
        <div>
            <img src="/public/icons/young-s-text.png" style="height: 50px;">
        </div>
        <div class="icon">
            <img src="/public/icons/black-ghost.png" style="height: 50px;">
        </div>
        
    </div>
</template>

<style>

.nav-bar-box {
    top: 0;
    left: 0;
    right: 0;
    position: fixed;
    display: flex;
    align-items: center;
    justify-content: space-between;
    border-color: rgb(233, 228, 228);
    padding: 10px 0 10px 0;
    z-index: 9;
    background-color: white;
}

.icons-box {
    display: flex;
    align-items: center;
    justify-content: space-around;
    padding-left: 20px;
    width: 10%;
}

.iconify {
    color: white;
}

.icon {
    width: 10%;
    margin-right: 20px;
}

</style>