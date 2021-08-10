<template>
    <div class="give-gift">
        <div class="give-gift__main">
            <p class="give-gift-title">Выбрать подарок</p>
            <ul class="gifts">
                <li class="gift gift-active">
                    <img class="gift-img" src="../assets/image.png">
                    <p class="gift-price gift-price-active">100 ₽</p>
                    <button class="gidt-send">Отправить</button>
                </li>
                <li class="gift">
                    <img class="gift-img" src="../assets/image.png">
                    <p class="gift-title">Шоколодка</p>
                    <p class="gift-price">100 ₽</p>
                </li>
                <li class="gift">
                    <img class="gift-img" src="../assets/image.png">
                    <p class="gift-title">Шоколодка</p>
                    <p class="gift-price">100 ₽</p>
                </li>
                <li class="gift">
                    <img class="gift-img" src="../assets/image.png">
                    <p class="gift-title">Шоколодка</p>
                    <p class="gift-price">100 ₽</p>
                </li>
                <li class="gift">
                    <img class="gift-img" src="../assets/image.png">
                    <p class="gift-title">Шоколодка</p>
                    <p class="gift-price">100 ₽</p>
                </li>
                <li class="gift">
                    <img class="gift-img" src="../assets/image.png">
                    <p class="gift-title">Шоколодка</p>
                    <p class="gift-price">100 ₽</p>
                </li>
            </ul>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    .give-gift{
        background: rgba(0, 0, 0, 0.8);
        backdrop-filter: blur(70px);
        width: 100%;
        height: 100vh;
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        display: flex;
        flex-direction: column;
        justify-content: flex-end;
        .give-gift__main{
            background: white;
            border-radius: 20px 20px 0px 0px;
            padding: 30px 23px;
            .give-gift-title{
                font-family: SF Pro Display;
                font-style: normal;
                font-weight: 600;
                font-size: 18px;
                line-height: 21px;
                color: #15151E;
                margin: 0 0 20px;
            }
            .gifts{
                padding: 0;
                display: grid;
                grid-template-columns: 1fr 1fr 1fr 1fr;
                grid-gap: 10px;
                .gift{
                    list-style-type: none;
                    display: flex;
                    flex-direction: column;
                    align-items: center;
                    .gift-price{
                        margin: 5px auto 0;
                        font-family: SF Pro Display;
                        font-style: normal;
                        font-weight: normal;
                        font-size: 10px;
                        line-height: 12px;
                        text-align: center;
                        color: #15151E;
                        opacity: 0.5;
                    }
                    .gift-title{
                        margin: 0 auto;
                        font-family: SF Pro Display;
                        font-style: normal;
                        font-weight: normal;
                        font-size: 10px;
                        line-height: 12px;
                        text-align: center;
                        color: #15151E;
                    }
                    .gift-price-active{
                        margin: 0 auto 5px;
                        color: #3790F5;
                    }
                }
                .gift-active{
                    border: 1.5px solid #3790F5;
                    box-sizing: border-box;
                    border-radius: 13px;
                }
                .gidt-send{
                    background: #3790F5;
                    border-radius: 0px 0px 13px 13px;
                    color: white;
                    border: none;
                    width: calc(100% + 3px);
                    padding: 6px 0;
                    margin-bottom: -1px;
                }
            }
        }
    }
</style>