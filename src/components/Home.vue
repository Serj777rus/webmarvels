<!-- eslint-disable vue/multi-word-component-names -->
<template>
    <div class="main">
        <div class="main_main">
            <div class="left_side">
                <h2>Привет!</h2>
                <h3>На связи команда "WEB Marvels"</h3>
                <p>Сейчас наш сайт находиться на стадии глобального обновления и совсем скоро здесь будет очень много информации обо всех услугах которые мы оказываем в сфере WEB разработки<br><br>Но не отчаивайся, прямо сейчас ты можешь нам написать в мессенджерах или социальных сетях, либо оставить контакты и мы молнееносно свяжемся с Вами!</p>
                <div class="buttons">
                    <img src="../assets/tg.png">
                    <img src="../assets/whatsapp.png">
                    <img src="../assets/vk.png">
                    <img src="../assets/instagram.png">
                    <button>Связаться</button>
                </div>
            </div>
            <div class="right_side">
                <img src="../assets/8000-210.png">
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
    .main {
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .main_main {
        width: 1200px;
        height: 100vh;
        display: flex;
    }
    .left_side {
        width: 50%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        gap: 24px
    }
    .left_side h2 {
        font-size: 48px;
        line-height: 100%;
    }
    .left_side h3 {
        font-size: 32px;
        font-weight: 400;
        line-height: 100%;
    }
    .left_side p {
        font-size: 16px;
        line-height: 100%;
    }
    .right_side {
        width: 50%;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .right_side img {
        width: 100%;
        object-fit: cover;
    }
    .buttons {
        width: 100%;
        display: flex;
        flex-direction: row;
        gap: 12px;
        box-sizing: border-box
    }
    .buttons img {
        width: 32px;
        object-fit: contain;
        cursor: pointer;
        transition: all 300ms ease;
    }
    .buttons img:hover {
        transform: scale(1.1);
    }
    button {
        border: 2px solid #fff;
        border-radius: 32px;
        background: transparent;
        color: #fff;
        padding: 8px 24px;
        cursor: pointer;
        font-size: 16px;
        font-weight: 100;
        transition: 300ms all ease;
        box-sizing: border-box;
    }
    button:hover {
        background: #fff;
        border: 2px solid transparent;
        color: #333;
    }
    @media all and (max-width: 430px) {
        .main {
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        padding-bottom: 16px;
    }
    .main_main {
        width: 100%;
        height: auto;
        display: flex;
        flex-direction: column;
    }
    .left_side {
        width: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        gap: 32px;
        align-items: center;
        order: 2;
    }
    .left_side h2 {
        font-size: 48px;
        line-height: 100%;
        font-weight: 700;
    }
    .left_side h3 {
        font-size: 32px;
        font-weight: 500;
        line-height: 100%;
        text-align: center;
    }
    .left_side p {
        font-size: 12px;
        text-align: justify;
        font-weight: 300;
        line-height: 120%;
    }
    .right_side {
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .right_side img {
        width: 100%;
        object-fit: cover;
    }
    .buttons {
        width: 100%;
        display: flex;
        flex-direction: row;
        gap: 12px;
        box-sizing: border-box;
        justify-content: center;
    }
    .buttons img {
        width: 32px;
        object-fit: contain;
        cursor: pointer;
        transition: all 300ms ease;
    }
    .buttons img:hover {
        transform: scale(1.1);
    }
    button {
        border: 2px solid #fff;
        border-radius: 32px;
        background: transparent;
        color: #fff;
        padding: 8px 24px;
        cursor: pointer;
        font-size: 16px;
        font-weight: 100;
        transition: 300ms all ease;
        box-sizing: border-box;
    }
    button:hover {
        background: #fff;
        border: 2px solid transparent;
        color: #333;
    }
    }
</style>