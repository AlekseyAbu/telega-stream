<template>
    <div class="private-modal">
        <div class="private-modal__main">
            <p class="private-modal-title">Пообщаться наедине</p>
            <p class="private-modal-text">Будет списана сумма за первые 5 минут, если вы  находитесь на трансляции меньше - остаток от этой суммы вернётся вам на карту.</p>
            <div class="private-modal__group">
                <div class="private-modal__group-header">
                    <p class="private-modal__group-title">Групповая</p>
                    <p class="private-modal__group-price">120 ₽ в мин</p>
                </div>
                <p class="private-modal__group-text">Групповая трансляция будет доступна только для зрителей, которые готовы заплатить </p>
            </div>
            <div class="private-modal__group">
                <div class="private-modal__group-header">
                    <p class="private-modal__group-title private-modal__group-title-private">Закрытая</p>
                    <p class="private-modal__group-price">250 ₽ в мин</p>
                </div>
                <p class="private-modal__group-text">Закрытая трансляция будет видна только вам</p>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    .private-modal{
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
        .private-modal__main{
            background: white;
            border-radius: 20px 20px 0px 0px;
            padding: 0 23px;
            .private-modal-title{
                font-family: SF Pro Display;
                font-style: normal;
                font-weight: 600;
                font-size: 18px;
                line-height: 21px;
                color: #15151E;
                margin: 30px auto 10px 0;
            }
            .private-modal-text{
                font-family: SF Pro Display;
                font-style: normal;
                font-weight: normal;
                font-size: 14px;
                line-height: 135%;
                color: #15151E;
                opacity: 0.4;
                margin: 0 auto 20px 0;
            }
            .private-modal__group{
                padding: 18px 23px 20px;
                border: 1px solid rgba(0, 0, 0, 0.05);
                box-sizing: border-box;
                border-radius: 13px;
                margin-bottom: 15px;
                .private-modal__group-header{
                    display: flex;
                    flex-direction: row;
                    justify-content: space-between;
                }
                .private-modal__group-title{
                    font-family: SF Pro Display;
                    font-style: normal;
                    font-weight: 600;
                    font-size: 16px;
                    line-height: 19px;
                    color: #15151E;
                    margin: 0;
                }
                .private-modal__group-title-private{
                        color: #3790F5;
                    }
                .private-modal__group-price{
                    font-family: SF Pro Display;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 14px;
                    line-height: 135%;
                    text-align: right;
                    color: #15151E;
                    opacity: 0.25;
                    margin: 0;
                }
                .private-modal__group-text{
                    font-family: SF Pro Display;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 14px;
                    line-height: 135%;
                    color: #15151E;
                    opacity: 0.4;
                    margin: 9px auto 0;
                    text-align: justify;
                }
            }
        }
    }
</style>