<template>
    <div class="broadcast">
        <div class="broadcast__blur">
            <p class="broadcast__blur-text">Эфир завершён</p>
            <p class="broadcast__blur-earned">Свайпните вверх, чтобы смотреть дальше</p>
            <div class="broadcast__blur-svg">
                <svg width="12" height="13" viewBox="0 0 12 13" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path opacity="0.5" d="M5.46967 0.46967C5.76256 0.176777 6.23744 0.176777 6.53033 0.46967L11.3033 5.24264C11.5962 5.53553 11.5962 6.01041 11.3033 6.3033C11.0104 6.59619 10.5355 6.59619 10.2426 6.3033L6 2.06066L1.75736 6.3033C1.46447 6.59619 0.989592 6.59619 0.696699 6.3033C0.403806 6.01041 0.403806 5.53553 0.696699 5.24264L5.46967 0.46967ZM5.25 1.5L5.25 1L6.75 1L6.75 1.5L5.25 1.5Z" fill="white"/>
                    <path opacity="0.5" d="M5.46967 6.26654C5.76256 5.97365 6.23744 5.97365 6.53033 6.26654L11.3033 11.0395C11.5962 11.3324 11.5962 11.8073 11.3033 12.1002C11.0104 12.3931 10.5355 12.3931 10.2426 12.1002L6 7.85754L1.75736 12.1002C1.46447 12.3931 0.989592 12.3931 0.696699 12.1002C0.403806 11.8073 0.403806 11.3324 0.696699 11.0395L5.46967 6.26654ZM5.25 7.29687L5.25 6.79687L6.75 6.79688L6.75 7.29688L5.25 7.29687Z" fill="white"/>
                </svg>
            </div>
        </div>
        <div class="broadcast__header">
            <div class="broadcast__indicator">
                <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M0.25574 7.37801L6.0339 1.59972C6.19885 1.43477 6.41868 1.34424 6.65308 1.34424C6.88775 1.34424 7.10746 1.4349 7.2724 1.59972L7.79701 2.12446C7.96182 2.28914 8.05262 2.50911 8.05262 2.74364C8.05262 2.97805 7.96182 3.20543 7.79701 3.37011L4.42611 6.74842H15.1356C15.6185 6.74842 16 7.12644 16 7.60942V8.35127C16 8.83426 15.6185 9.25039 15.1356 9.25039H4.38787L7.79688 12.6476C7.96169 12.8125 8.05249 13.0265 8.05249 13.261C8.05249 13.4953 7.96169 13.7124 7.79688 13.8772L7.27227 14.4003C7.10733 14.5652 6.88762 14.6551 6.65296 14.6551C6.41855 14.6551 6.19872 14.564 6.03377 14.3991L0.25561 8.62093C0.0902777 8.45546 -0.000648499 8.23459 2.86102e-06 7.99979C-0.000516891 7.76422 0.0902777 7.54321 0.25574 7.37801Z" fill="white"/>
                </svg>
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

        <div class="broadcast__send">
            <input class="broadcast__send-input" placeholder="Написать..">
            <button class="broadcast__send-btn">
                <svg width="18" height="17" viewBox="0 0 18 17" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M17.3017 7.42133L11.1627 0.243762C10.9625 0.0099225 10.6555 -0.063481 10.3883 0.057625C10.1201 0.179899 9.94441 0.472345 9.94441 0.797695V4.25369H9.70836C4.63103 4.25369 0.5 8.90479 0.5 14.6213V16.2163C0.5 16.5863 0.731385 16.8947 1.05148 16.9788C1.10354 16.9936 1.15542 17 1.2073 17C1.47465 17 1.73059 16.8234 1.85424 16.5459C3.1822 13.5547 5.85211 11.697 8.82242 11.697H9.94441V15.1528C9.94441 15.4784 10.1201 15.7708 10.3883 15.8919C10.6538 16.0142 10.9625 15.9398 11.1627 15.7058L17.3017 8.52823C17.5661 8.21884 17.5661 7.73189 17.3017 7.42133Z" fill="white"/>
                </svg>
            </button>
            <button class="broadcast__send-btn">
                <svg width="19" height="19" viewBox="0 0 19 19" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M18.3 3.8235H15.5886C15.8097 3.4161 15.8755 2.90799 15.7504 2.38462C15.5552 1.56841 14.8269 0.615234 13.4164 0.615234C12.377 0.615234 11.1207 1.48707 10.4644 2.00671C10.271 2.15978 9.86692 2.49228 9.49998 2.87234C9.13299 2.49228 8.72899 2.15978 8.5356 2.00671C7.87927 1.48702 6.623 0.615234 5.58353 0.615234C4.17307 0.615234 3.44473 1.56841 3.24957 2.38462C3.12441 2.90799 3.19026 3.4161 3.41137 3.8235H0.700007C0.314023 3.8235 0 4.13753 0 4.52351V7.38182C0 7.76781 0.314023 8.08183 0.700007 8.08183H1.40435C1.53301 8.08183 1.63769 8.18651 1.63769 8.31517V17.6836C1.63769 18.0696 1.95171 18.3836 2.3377 18.3836H16.6623C17.0483 18.3836 17.3623 18.0696 17.3623 17.6836V8.31517C17.3623 8.18651 17.467 8.08183 17.5956 8.08183H18.3C18.686 8.08183 19 7.76781 19 7.38182V4.52351C19 4.13753 18.6859 3.8235 18.3 3.8235ZM13.0629 11.8328C12.4923 12.7005 10.036 14.7638 9.50371 14.7638C8.98248 14.7638 6.50385 12.693 5.93704 11.8328C5.65325 11.4021 5.45188 10.9269 5.48521 10.3023C5.54447 9.19652 6.44851 8.28343 7.55582 8.28343C8.69408 8.28343 9.35703 9.4979 9.50007 9.4979C9.6635 9.4979 10.3547 8.28343 11.4443 8.28343C12.5515 8.28343 13.4555 9.19647 13.5148 10.3023C13.5481 10.9269 13.3474 11.4003 13.0629 11.8328Z" fill="white"/>
                </svg>
            </button>
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
                z-index: 10;           
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
         .broadcast__send{
            position: absolute;
            left: 16px;
            right: 16px;
            bottom: 30px;
            display: flex;
            flex-direction: row;
            justify-content: space-between;
            opacity: .5;
            .broadcast__send-input{
                background: rgba(0, 0, 0, 0.3);
                backdrop-filter: blur(20px);
                border-radius: 50px;
                border: none;
                padding: 13px 0 14px 18px;
                width: calc(100% - 90px - 16px);
            }
            .broadcast__send-btn{
                background: rgba(0, 0, 0, 0.3);
                backdrop-filter: blur(20px);
                border-radius: 50px;
                width: 45px;
                height: 45px;
                border: none;
                margin-left: 8px;
                display: flex;
                align-items: center;
                justify-content: center;
            }
        }
         .broadcast__blur{
            background: rgba(0, 0, 0, 0.8);
            backdrop-filter: blur(70px);
            width: 100%;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            position: absolute;
            top: 0;
            right: 0;
            left: 0;
            bottom: 0;
            z-index: 10;
            .broadcast__blur-text{
                font-family: SF Pro Display;
                font-style: normal;
                font-weight: 500;
                font-size: 16px;
                line-height: 130%;
                text-align: center;
                color: #FFFFFF;
                margin: 0;
                width: 240px;
            }
            .broadcast__blur-btn{
                font-family: SF Pro Display;
                font-style: normal;
                font-weight: 500;
                font-size: 15px;
                line-height: 18px;
                text-align: center;
                color: #FFFFFF;
                background: #FF1A88;
                border-radius: 25px;
                padding: 16px 47px;
                border: none;
            }
            .broadcast__blur-earned{
                font-family: SF Pro Display;
                font-style: normal;
                font-weight: normal;
                font-size: 14px;
                line-height: 130%;
                text-align: center;
                color: #FFFFFF;
                opacity: 0.5;
                margin: 8px auto 13px;
                padding: 0 23px;
            }
        }
    }
</style>