<template>
    <div class="give-gift">
        <div class="give-gift__main">
            <p class="give-gift-title">Выбрать подарок</p>
            <ul class="gifts">
                <li class="gift gift-active">
                    <img class="gift-img" src="../assets/image.png">
                    <p class="gift-price">100₽</p>
                    <button class="gidt-send">Отправить</button>
                </li>
                <li class="gift">
                    <img class="gift-img" src="../assets/image.png">
                    <p class="gift-title">Шоколодка</p>
                    <p class="gift-price">100₽</p>
                </li>
                <li class="gift">
                    <img class="gift-img" src="../assets/image.png">
                    <p class="gift-title">Шоколодка</p>
                    <p class="gift-price">100₽</p>
                </li>
                <li class="gift">
                    <img class="gift-img" src="../assets/image.png">
                    <p class="gift-title">Шоколодка</p>
                    <p class="gift-price">100₽</p>
                </li>
                <li class="gift">
                    <img class="gift-img" src="../assets/image.png">
                    <p class="gift-title">Шоколодка</p>
                    <p class="gift-price">100₽</p>
                </li>
                <li class="gift">
                    <img class="gift-img" src="../assets/image.png">
                    <p class="gift-title">Шоколодка</p>
                    <p class="gift-price">100₽</p>
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
                display: flex;
                flex-flow: row wrap;
                .gift{
                    list-style-type: none;
                    width: calc(25% - 30px);
                    margin-right: 10px;
                }
                .gift-active{
                    border: 1.5px solid #3790F5;
                    box-sizing: border-box;
                    border-radius: 13px;
                }
            }
        }
    }
</style>