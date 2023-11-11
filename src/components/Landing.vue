<script lang="ts">

import { defineComponent } from 'vue';

export default defineComponent({
    name: 'Landing',
    setup() {
        return {

        }
    }
})

</script>

<template>
    <div class="main-box">
        <div class="img-box">
            <div class="image"></div>
        </div>
        <div class="text-box">
            <h1>Young Souls</h1>
            <h3>PROXIMAMENTE...</h3>
        </div>
    </div>
</template>

<style scope lang="scss">

    .border {
        border: 1px solid;
    }

    .main-box {
        top: 90px;
        position: relative;
        display: flex;
        align-items: center;
        justify-content: space-between;
        width: 100%;
        height: 89vh;
    }
    
    .img-box {
        display: flex;
        align-items: center;
        justify-content: center;
        width: 100%; 
        height: 100%;
    }

    .image {
        display: flex;
        align-items: center;
        justify-content: center;
        background-image: url('/public/assets/shop-background.png');
        background-repeat: no-repeat;
        background-position: 50%;
        background-size: 70%;
        width: 100% !important;
        height: 100% !important;
    }

    .text-box {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        width: 100%;
        height: 100%;
    }

    @media only screen and (min-width: 114px) and (orientation: portrait) {
        .main-box {
            flex-direction: column;
        }

        h1 {
            font-size: 35px;
        }
    }
    
</style>
