<template>
    <div class="invite">
        <div class="invite__content">
            <img class="invite__content-img" src="https://shutniki.club/wp-content/uploads/2020/01/Multyashnye_kartinki_s_devushkami__dlya_profilya_3_27181708.jpg">
            <p class="invite__content-nick">Vasya Pupkin</p>
            <p class="invite__content-text">Приглашает вас в закрытую трансляцию</p>
            <button class="invite__content-btn">Принять приглашение</button>
        </div>
        <button class="invite__close">Отклонить</button>
    </div>
</template>

<style lang="scss" scoped>
    .invite{
        background: rgba(0, 0, 0, 0.8);
        backdrop-filter: blur(70px);
        width: 100%;
        height: 100vh;
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        padding: 9px;
        display: flex;
        flex-direction: column;
        justify-content: flex-end;
        .invite__content{
            background: white;
            border-radius: 13px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: flex-end;
            .invite__content-img{
                width: 92px;
                height: 92px;
                border-radius: 50%;
                margin: 40px auto 20px;
            }
            .invite__content-nick{
                font-family: SF Pro Display;
                font-style: normal;
                font-weight: 600;
                font-size: 16px;
                line-height: 130%;
                text-align: center;
                color: #15151E;
                margin: 0;
            }
            .invite__content-text{
                font-family: SF Pro Display;
                font-style: normal;
                font-weight: normal;
                font-size: 15px;
                line-height: 140%;
                text-align: center;
                color: #15151E;
                margin: 10px auto 35px;
            }
            .invite__content-btn{
                font-family: SF Pro Display;
                font-style: normal;
                font-weight: 500;
                font-size: 16px;
                line-height: 19px;
                text-align: center;
                color: #FF1988;
                border: none;
                width: 100%;
                background: white;
                padding: 18px 0;
                border-radius: 0 0 13px 13px;
                border-top: 1px solid rgba(0, 0, 0, 0.03);
            }
        }
        .invite__close{
            font-family: SF Pro Display;
            font-style: normal;
            font-weight: 500;
            font-size: 16px;
            line-height: 19px;
            text-align: center;
            color: #3790F5;
            padding: 18px 0;
            width: 100%;
            border: none;
            background: white;
            border-radius: 13px;
            margin-top: 10px;
        }
    }
</style>