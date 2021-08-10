<template>
    <div class="broadcast">
        <div class="broadcast__header">
            <div class="broadcast__indicator">
                <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M0.25574 7.37801L6.0339 1.59972C6.19885 1.43477 6.41868 1.34424 6.65308 1.34424C6.88775 1.34424 7.10746 1.4349 7.2724 1.59972L7.79701 2.12446C7.96182 2.28914 8.05262 2.50911 8.05262 2.74364C8.05262 2.97805 7.96182 3.20543 7.79701 3.37011L4.42611 6.74842H15.1356C15.6185 6.74842 16 7.12644 16 7.60942V8.35127C16 8.83426 15.6185 9.25039 15.1356 9.25039H4.38787L7.79688 12.6476C7.96169 12.8125 8.05249 13.0265 8.05249 13.261C8.05249 13.4953 7.96169 13.7124 7.79688 13.8772L7.27227 14.4003C7.10733 14.5652 6.88762 14.6551 6.65296 14.6551C6.41855 14.6551 6.19872 14.564 6.03377 14.3991L0.25561 8.62093C0.0902777 8.45546 -0.000648499 8.23459 2.86102e-06 7.99979C-0.000516891 7.76422 0.0902777 7.54321 0.25574 7.37801Z" fill="white"/>
                </svg>
            </div>

            <div class="broadcast__right">
                <div class="broadcast__time">
                    <p class="broadcast__time-number">57:24</p>
                    <p class="broadcast__time-text">вы в эфире</p>
                </div>
            </div>
        </div>

        <div class="broadcast__stream">
            <div class="broadcast__content">
                <div class="message">
                    <img class="message__img" src="https://shutniki.club/wp-content/uploads/2020/01/Multyashnye_kartinki_s_devushkami__dlya_profilya_3_27181708.jpg">
                    <div class="message__text">
                        <p class="message__nick">Ivasdasddsad</p>
                        <p class="message__text">computers have become ubiquitous in almost</p>
                    </div>
                </div>
                <div class="message">
                    <img class="message__img" src="https://shutniki.club/wp-content/uploads/2020/01/Multyashnye_kartinki_s_devushkami__dlya_profilya_3_27181708.jpg">
                    <div class="message__text">
                        <p class="message__nick">Oleg</p>
                        <p class="message__text">computers have become ubiquitous in almost</p>
                    </div>
                </div>
                <div class="message">
                    <img class="message__img" src="https://shutniki.club/wp-content/uploads/2020/01/Multyashnye_kartinki_s_devushkami__dlya_profilya_3_27181708.jpg">
                    <div class="message__text">
                        <p class="message__nick">NavalnyOleg</p>
                        <p class="message__text">computers have become ubiquitous in almost</p>
                    </div>
                </div>
                <div class="message">
                    <img class="message__img" src="https://shutniki.club/wp-content/uploads/2020/01/Multyashnye_kartinki_s_devushkami__dlya_profilya_3_27181708.jpg">
                    <div class="message__text">
                        <p class="message__nick">NavalnyAleksey</p>
                        <p class="message__text">Computers have become ubiquitous in almost every However, help is at hand in the facet of our lives.</p>
                    </div>
                </div>
            </div>

            <div class="broadcast__users">
                <div class="broadcast__users-commons">
                    <div class="user">
                        <img class="user__avatar" src="https://shutniki.club/wp-content/uploads/2020/01/Multyashnye_kartinki_s_devushkami__dlya_profilya_3_27181708.jpg">
                        <div class="user__footer">LIVE</div>
                    </div>
                </div>
            </div>
        </div>

        <div class="broadcast__make-friends">
            <button class="broadcast__make-friends-btn">Подружиться чтобы смотреть </button>
        </div>
    </div>
</template>

<script>

export default {
    
}
</script>

<style lang='scss' scoped>
    .broadcast{
        background: url('../assets/MaskGroup.png');
        max-width: 600px;
        width: 100%;
        height: 100vh;
        background-size: cover;
        position: relative;
        .broadcast__header{
            max-width: 552px;
            padding: 30px 16px 0;
            display: flex;
            flex-direction: row;
            justify-content: space-between;
            align-items: flex-start;
            .broadcast__indicator{
                width: 40px;
                height: 40px;
                border-radius: 50%;
                background: rgba(0, 0, 0, 0.6);
                backdrop-filter: blur(20px);
                display: flex;
                justify-content: center;
                align-items: center;              
                .broadcast__indicator-connection{
                    padding: 12px 14px;
                    background: rgba(0, 0, 0, 0.3);
                    backdrop-filter: blur(20px);
                    border-radius: 50px;
                    margin-left: 8px;
                }
            }
            .broadcast__right{
                display: flex;
                flex-direction: row;
                .broadcast__time{
                    color: white;
                    .broadcast__time-number{
                        font-family: SF Pro Display;
                        font-style: normal;
                        font-weight: bold;
                        font-size: 18px;
                        line-height: 21px;
                        text-align: right;
                        margin: 0;
                    }
                    .broadcast__time-text{
                        font-family: SF Pro Display;
                        font-style: normal;
                        font-weight: 500;
                        font-size: 14px;
                        line-height: 17px;
                        text-align: right;
                        margin: 0;
                    }
                }
                .broadcast__control{
                    display: flex;
                    flex-direction: column;
                    align-items: center;
                    margin-left: 15px;
                    .broadcast__control-button{
                        width: 45px;
                        height: 45px;
                        background: rgba(0, 0, 0, 0.6);
                        backdrop-filter: blur(20px);
                        border: none;
                        border-radius: 50%;
                        margin-bottom: 15px;
                    }
                    .broadcast__control-button-ping{
                        background: #FF1A88;
                    }
                }
            }
        }

        .broadcast__stream{
            display: flex;
            flex-direction: row;
            justify-content: space-between;
            align-items: flex-end;
            position: absolute;
            left: 16px;
            right: 16px;
            bottom: 90px;
            .broadcast__content{
                width: 70%;
                .message{
                    display: flex;
                    flex-direction: row;
                    align-items: flex-start;
                    margin-bottom: 13px;
                    .message__img{
                        width: 30px;
                        height: 30px;
                        border-radius: 50%;
                        margin-right: 7px;
                    }
                    .message__text{
                        display: flex;
                        flex-direction: column;
                        .message__nick{
                            font-family: SF Pro Display;
                            font-style: normal;
                            font-weight: normal;
                            font-size: 12px;
                            line-height: 135%;
                            color: #FFFFFF;
                            opacity: 0.6;
                            margin: 0;
                        }
                        .message__text{
                            font-family: SF Pro Display;
                            font-style: normal;
                            font-weight: normal;
                            font-size: 12px;
                            line-height: 135%;
                            color: #FFFFFF;
                            margin: 0;
                            text-align: left;
                        }
                    }
                }
            }
            .broadcast__users{
                display: flex;
                flex-direction: column;
                .user{
                    .user__avatar{
                        width: 45px;
                        height: 45px;
                        border-radius: 50%;
                        border: 3px solid #FF1988;
                        z-index: 1;
                    }
                    .user__footer{
                        width: 41px;
                        height: 16px;
                        background: #FF1A88;
                        border-radius: 7.5px;
                        display: flex;
                        justify-content: center;
                        align-items: center;
                        margin: -10px auto 15px;
                        z-index: 5;
                        font-family: SF Pro Display;
                        font-style: normal;
                        font-weight: 600;
                        font-size: 8px;
                        line-height: 10px;
                        display: flex;
                        align-items: center;
                        text-align: center;
                        color: #FFFFFF;
                    }
                }
            }
        }
        .broadcast__make-friends{
            position: absolute;
            left: 16px;
            right: 16px;
            bottom: 30px;
            display: flex;
            flex-direction: row;
            justify-content: space-between;
            .broadcast__make-friends-btn{
                font-family: SF Pro Rounded;
                font-size: 15px;
                line-height: 18px;
                text-align: center;
                color: #FFFFFF;
                padding: 13px 0 14px;
                width: 100%;
                background: #FF1A88;
                border-radius: 25px;
                border: none;
            }
        }
    }
</style>