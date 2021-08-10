<template>
    <div class="invite-private">
        <div class="invite-private__main">
            <p class="invite-private-title">Приглашения в 
закрытую трансляцию</p>
            <div class="invite-private__list">
                <div class="user">
                    <div class="user__about">
                        <img class="user__img" src="https://shutniki.club/wp-content/uploads/2020/01/Multyashnye_kartinki_s_devushkami__dlya_profilya_3_27181708.jpg">
                        <p class="user__nick">Adison Siphron</p>
                    </div>
                    <div class="user__btn">
                        <button class="user__yes">
                            <svg width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <path d="M11.549 1.42827L11.2277 1.15222C10.6944 0.693879 9.89287 0.744969 9.42198 1.26714L4.04678 7.2272L2.42425 5.82977C1.89145 5.37092 1.08985 5.42098 0.618402 5.9426L0.334303 6.25696C0.103911 6.51175 -0.0157134 6.84784 0.00165897 7.19116C0.0192026 7.53427 0.172275 7.8564 0.427453 8.08669L3.40163 10.8103C3.65913 11.0521 4.00423 11.1782 4.35696 11.1595C4.70969 11.1408 5.03947 10.9788 5.26989 10.711L11.6865 3.2553C11.9107 2.99482 12.0222 2.65598 11.9963 2.31338C11.9705 1.97053 11.8097 1.6522 11.549 1.42827Z" fill="#FF1988"/>
                            </svg>
                        </button>
                        <button class="user__no">
                            <svg width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <path d="M11.5944 2.36357L7.95846 5.99987L11.5944 9.636C12.1352 10.177 12.1352 11.0534 11.5944 11.5945C11.3242 11.8647 10.9699 11.9999 10.6158 11.9999C10.2611 11.9999 9.90677 11.8649 9.63675 11.5945L6.00003 7.95792L2.36357 11.5944C2.09338 11.8647 1.73907 11.9999 1.38465 11.9999C1.03033 11.9999 0.676258 11.8649 0.405827 11.5944C-0.135 11.0536 -0.135 10.1772 0.405827 9.63597L4.04166 5.99984L0.40562 2.36357C-0.135207 1.82274 -0.135207 0.946135 0.40562 0.405309C0.946344 -0.135103 1.82244 -0.135103 2.36337 0.405309L5.99999 4.04161L9.63634 0.405309C10.1774 -0.135103 11.0536 -0.135103 11.5942 0.405309C12.1352 0.946135 12.1352 1.82274 11.5944 2.36357Z" fill="#C5C5C5"/>
                            </svg>
                        </button>
                    </div>
                </div>
            </div>
            <button class="invite-private-btn">Принять все и запустить</button>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    .invite-private{
        background: rgba(0, 0, 0, 0.8);
        position: relative;
        width: 100%;
        height: 100vh;
        .invite-private__main{
            position: absolute;
            left: 0;
            right: 0;
            bottom: 0;
            background: white;
            border-radius: 25px 25px 0px 0px;
            display: flex;
            flex-direction: column;
            align-items: center;
            .invite-private-title{
                font-family: SF Pro Display;
                font-style: normal;
                font-weight: 600;
                font-size: 16px;
                line-height: 150%;
                text-align: center;
                color: #15151E;
                width: 275px;
                margin: 35px auto;
            }
            .invite-private__list{
                padding: 0 35px;
                width: calc(100% - 70px);
            }
        }
        .invite-private-btn{
            margin: 25px auto 40px;
            padding: 18px 69px;
            background: #FF1988;
            border-radius: 13px;
            color: white;
            border: none;
            font-family: SF Pro Display;
            font-style: normal;
            font-weight: 500;
            font-size: 15px;
            line-height: 18px;
            text-align: center;
            width: calc(100% - 70px);
        }
    }
    .user{
       display: flex;
       flex-direction: row;
       align-items: center;
       justify-content: space-between;
       padding: 0 0 23px;
       border-bottom: 1px solid linear-gradient(90deg, rgba(242, 242, 242, 0) 0%, #F7F7F7 48.96%, rgba(242, 242, 242, 0) 100%);
      
       width: 100% !important;
       .user__about{
           display: flex;
           flex-direction: row;
           align-items: center;
           .user__nick{
                font-family: SF Pro Display;
                font-style: normal;
                font-weight: 600;
                font-size: 15px;
                line-height: 130%;
                color: #15151E;
           }
           .user__img{
                width: 42px;
                height: 42px;
                border-radius: 50%;
                margin-right: 14px;
            }
       }
       .user__btn{
           display: flex;
           flex-direction: row;
           align-items: center;
           .user__yes{
                width: 42px;
                height: 42px;
                border-radius: 50%;
                border: 2px solid #FF1988;
                background: white;
                margin-right: 12px;
            }
            .user__no{
                width: 42px;
                height: 42px;
                border-radius: 50%;
                border: 2px solid #EFEFEF;
                background: white;
            }
       }
    }
</style>