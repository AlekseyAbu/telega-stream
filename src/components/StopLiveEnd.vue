<template>
    <div class="broadcast">
        <div class="broadcast__blur">
            <p class="broadcast__blur-text">Эфир завершён</p>
            <p class="broadcast__blur-earned">1565,56 ₽ заработано</p>
            <button class="broadcast__blur-btn">ОК</button>
        </div>
        <div class="broadcast__header">
            <div class="broadcast__indicator">
                <div class="broadcast__indicator-view">
                    <svg width="13" height="13" viewBox="0 0 13 13" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M6.41771 6.26212C7.28389 6.26212 8.03393 5.95356 8.64676 5.34479C9.2596 4.73611 9.57026 3.99136 9.57026 3.13096C9.57026 2.27086 9.2596 1.52601 8.64666 0.91713C8.03373 0.308553 7.28379 0 6.41771 0C5.55143 0 4.80159 0.308553 4.18875 0.91723C3.57591 1.52591 3.26515 2.27076 3.26515 3.13096C3.26515 3.99136 3.57591 4.73621 4.18885 5.34489C4.80179 5.95346 5.55173 6.26212 6.41771 6.26212Z" fill="white"/>
                        <path d="M11.9335 9.99629C11.9158 9.74298 11.8801 9.46666 11.8274 9.17487C11.7743 8.8809 11.7059 8.60299 11.624 8.34899C11.5395 8.08646 11.4244 7.82719 11.2822 7.57875C11.1346 7.32087 10.9613 7.09633 10.7667 6.91155C10.5633 6.71825 10.3143 6.56283 10.0263 6.44947C9.73929 6.3367 9.42124 6.27957 9.08102 6.27957C8.94741 6.27957 8.81819 6.33402 8.56865 6.49539C8.41506 6.59487 8.23541 6.70992 8.0349 6.83717C7.86344 6.94567 7.63117 7.04733 7.34427 7.13937C7.06437 7.22933 6.78017 7.27495 6.49966 7.27495C6.21916 7.27495 5.93506 7.22933 5.65485 7.13937C5.36826 7.04743 5.13599 6.94577 4.96473 6.83727C4.76611 6.71121 4.58636 6.59616 4.43048 6.49529C4.18123 6.33392 4.05191 6.27947 3.9183 6.27947C3.57798 6.27947 3.26003 6.3367 2.97314 6.44957C2.68534 6.56273 2.43619 6.71815 2.23258 6.91165C2.03815 7.09653 1.8647 7.32097 1.71731 7.57875C1.57521 7.82719 1.46017 8.08636 1.37549 8.34909C1.2937 8.60309 1.2253 8.8809 1.17218 9.17487C1.11955 9.46627 1.0838 9.74269 1.06613 9.99659C1.04875 10.2453 1.03996 10.5035 1.03996 10.7643C1.03996 11.4429 1.25716 11.9922 1.68545 12.3974C2.10846 12.7972 2.66817 13 3.34881 13H9.65112C10.3318 13 10.8913 12.7973 11.3144 12.3974C11.7428 11.9925 11.96 11.4431 11.96 10.7642C11.9599 10.5022 11.951 10.2438 11.9335 9.99629Z" fill="white"/>
                    </svg>
                    <p class="broadcast__indicator-number">12</p>
                </div>
                <div class="broadcast__indicator-connection">
                    <svg width="17" height="19" viewBox="0 0 17 19" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M0 13.1188C0 11.8696 1.00147 10.8569 2.23684 10.8569C3.47222 10.8569 4.47368 11.8696 4.47368 13.1188V16.7379C4.47368 17.9871 3.47222 18.9998 2.23684 18.9998C1.00147 18.9998 0 17.9871 0 16.7379V13.1188Z" fill="white"/>
                        <path d="M6.26315 7.69062C6.26315 6.4414 7.26462 5.42871 8.49999 5.42871C9.73537 5.42871 10.7368 6.4414 10.7368 7.69062V16.7382C10.7368 17.9875 9.73537 19.0001 8.49999 19.0001C7.26462 19.0001 6.26315 17.9875 6.26315 16.7382V7.69062Z" fill="white"/>
                        <path opacity="0.25" d="M12.5263 2.26191C12.5263 1.01269 13.5278 0 14.7631 0C15.9985 0 17 1.01269 17 2.2619V16.7381C17 17.9873 15.9985 19 14.7631 19C13.5278 19 12.5263 17.9873 12.5263 16.7381V2.26191Z" fill="white"/>
                    </svg>
                </div>
            </div>

            <div class="broadcast__right">
                <div class="broadcast__time">
                    <p class="broadcast__time-number">57:24</p>
                    <p class="broadcast__time-text">вы в эфире</p>
                </div>
                 <div class="broadcast__control">
                    <button class="broadcast__control-button broadcast__control-button-ping">
                        <svg width="19" height="19" viewBox="0 0 19 19" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M1.9408 4.7092C2.1521 3.26269 3.26254 2.15225 4.70905 1.94096C5.97099 1.75662 7.64893 1.5835 9.50001 1.5835C11.3511 1.5835 13.029 1.75662 14.291 1.94096C15.7375 2.15225 16.8479 3.26269 17.0592 4.7092C17.2436 5.97114 17.4167 7.64909 17.4167 9.50016C17.4167 11.3512 17.2436 13.0292 17.0592 14.2911C16.8479 15.7376 15.7375 16.8481 14.291 17.0594C13.029 17.2437 11.3511 17.4168 9.50001 17.4168C7.64893 17.4168 5.97098 17.2437 4.70905 17.0594C3.26254 16.8481 2.1521 15.7376 1.9408 14.2911C1.75647 13.0292 1.58334 11.3512 1.58334 9.50016C1.58334 7.64909 1.75647 5.97114 1.9408 4.7092Z" fill="white"/>
                        </svg>
                    </button>
                    <button class="broadcast__control-button">
                        <svg width="19" height="19" viewBox="0 0 19 19" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M1.58334 3.16683C1.58334 2.29238 2.29223 1.5835 3.16668 1.5835H6.33334C7.20779 1.5835 7.91668 2.29238 7.91668 3.16683V15.8335C7.91668 16.7079 7.20779 17.4168 6.33334 17.4168H3.16668C2.29223 17.4168 1.58334 16.7079 1.58334 15.8335V3.16683Z" fill="white"/>
                            <path d="M11.0833 3.16683C11.0833 2.29238 11.7922 1.5835 12.6667 1.5835H15.8333C16.7078 1.5835 17.4167 2.29238 17.4167 3.16683V15.8335C17.4167 16.7079 16.7078 17.4168 15.8333 17.4168H12.6667C11.7922 17.4168 11.0833 16.7079 11.0833 15.8335V3.16683Z" fill="white"/>
                        </svg>
                    </button>
                    <button class="broadcast__control-button">
                        <svg width="19" height="19" viewBox="0 0 19 19" fill="none" xmlns="http://www.w3.org/2000/svg"><g clip-path="url(#clip0)">
                            <path d="M17.2079 6.03603L16.4208 0.525617C16.3561 0.0738477 15.8008 -0.113889 15.476 0.210893L14.3296 1.35735C12.8553 0.468023 11.1816 0 9.4606 0C4.28503 0 0.129783 4.05086 0.000420217 9.22209C-0.00663056 9.50475 0.198844 9.74719 0.47824 9.78741L2.70261 10.1054C3.03422 10.1538 3.34271 9.89343 3.33811 9.54661C3.29198 6.13366 6.04854 3.33984 9.4606 3.33984C10.2868 3.33984 11.1033 3.5078 11.8579 3.82906L10.7528 4.93417C10.43 5.25691 10.6132 5.81389 11.0675 5.87894L16.5779 6.66607C16.941 6.7208 17.26 6.40504 17.2079 6.03603Z" fill="white"/>
                            <path d="M18.522 9.25559L16.2992 8.93812C16.0121 8.90175 15.6638 9.14783 15.6638 9.53718C15.6638 12.9134 12.917 15.6602 9.54072 15.6602C8.71882 15.6602 7.90613 15.4939 7.15436 15.1759L8.22415 14.1061C8.54689 13.7834 8.36372 13.2264 7.90943 13.1613L2.39902 12.3736C2.03709 12.3219 1.71658 12.6323 1.76898 13.0037L2.55607 18.5141C2.62086 18.9664 3.17565 19.1529 3.50084 18.8289L4.67501 17.6552C6.14217 18.5364 7.8148 19.0001 9.54072 19.0001C14.6913 19.0001 18.846 14.9693 18.9998 9.82366C19.008 9.54044 18.8025 9.29582 18.522 9.25559Z" fill="white"/></g><defs><clipPath id="clip0"><rect width="19" height="19" fill="white"/></clipPath></defs>
                        </svg>
                    </button>
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
                        <div class="user__footer">
                            <svg width="11" height="11" viewBox="0 0 11 11" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <path d="M5.49998 5.39755C6.53958 5.39755 7.38244 4.37387 7.38244 3.11114C7.38244 1.84838 7.10567 0.824707 5.49998 0.824707C3.89423 0.824707 3.61752 1.84838 3.61752 3.11114C3.61755 4.37387 4.46038 5.39755 5.49998 5.39755Z" fill="white"/><path d="M9.05133 8.7961C9.01651 6.59634 8.7292 5.96954 6.53077 5.57275C6.53077 5.57275 6.22125 5.96708 5.49995 5.96708C4.77865 5.96708 4.46919 5.57275 4.46919 5.57275C2.29472 5.96518 1.98991 6.58271 1.94984 8.72461C1.94659 8.89952 1.94508 8.9087 1.94449 8.88838C1.9446 8.92643 1.94477 8.99679 1.94477 9.1195C1.94477 9.1195 2.46819 10.1746 5.49998 10.1746C8.53177 10.1746 9.05524 9.1195 9.05524 9.1195C9.05524 9.04068 9.0553 8.98582 9.05536 8.94856C9.05476 8.96112 9.05354 8.93678 9.05133 8.7961Z" fill="white"/><path d="M8.11229 4.98937C8.95667 4.98937 9.64116 4.15797 9.64116 3.1324C9.64116 2.10679 9.41641 1.27539 8.11229 1.27539C7.89293 1.27539 7.70417 1.29899 7.54178 1.34305C7.843 1.89834 7.88428 2.5728 7.88428 3.11117C7.88428 3.72075 7.71904 4.30273 7.41473 4.78461C7.6239 4.91522 7.86091 4.98937 8.11229 4.98937Z" fill="white"/><path d="M10.9967 7.74978C10.9684 5.96318 10.7351 5.45411 8.94952 5.13184C8.94952 5.13184 8.69817 5.45212 8.11234 5.45212C8.08811 5.45212 8.06462 5.45139 8.0415 5.45034C8.41373 5.61816 8.75235 5.85183 9.00171 6.19376C9.43281 6.78489 9.53193 7.57898 9.55238 8.74557C10.7537 8.50819 10.9999 8.01249 10.9999 8.01249C10.9999 7.94789 10.9999 7.90358 11 7.87329C10.9995 7.88394 10.9985 7.86484 10.9967 7.74978Z" fill="white"/><path d="M2.88752 4.98935C3.13893 4.98935 3.37588 4.9152 3.58513 4.78461C3.28082 4.30273 3.11558 3.72075 3.11558 3.11118C3.11558 2.57277 3.15686 1.89831 3.45802 1.34305C3.29567 1.29899 3.10694 1.27539 2.88752 1.27539C1.58339 1.27539 1.3587 2.10679 1.3587 3.1324C1.3587 4.15794 2.04319 4.98935 2.88752 4.98935Z" fill="white"/><path d="M2.9584 5.45034C2.93534 5.45139 2.91185 5.45212 2.88757 5.45212C2.30174 5.45212 2.05039 5.13184 2.05039 5.13184C0.264894 5.45411 0.0315357 5.96315 0.0032584 7.74978C0.0014167 7.86487 0.000481677 7.88394 0 7.87326C5.66679e-05 7.90355 0.000113336 7.94786 0.000113336 8.01246C0.000113336 8.01246 0.246335 8.50816 1.44752 8.74555C1.46807 7.57898 1.56712 6.78489 1.99828 6.19374C2.24762 5.85186 2.58618 5.61816 2.9584 5.45034Z" fill="white"/>
                            </svg>
                        </div>
                    </div>
                </div>
                <div class="broadcast__users-paid">
                    <div class="user">
                        <img class="user__avatar" src="https://shutniki.club/wp-content/uploads/2020/01/Multyashnye_kartinki_s_devushkami__dlya_profilya_3_27181708.jpg">
                        <div class="user__footer">
                            <svg width="21" height="13" viewBox="0 0 21 13" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <path d="M1.19992 5.95141C8.01992 -1.69002 14.5299 -0.558725 19.7999 6.23443C16.9066 10.4798 9.13592 16.3668 1.19992 5.95141Z" fill="white"/><g clip-path="url(#clip0)"><path d="M12.281 5.79632H12.1757V5.391C12.1757 4.64134 11.4529 4.01511 10.5495 4.00174C10.5248 4.00137 10.4755 4.00137 10.4508 4.00174C9.54738 4.01511 8.82458 4.64134 8.82458 5.391V5.79632H8.71935C8.55719 5.79632 8.42493 5.93403 8.42493 6.10412V8.13701C8.42493 8.30691 8.55719 8.44591 8.71936 8.44591H12.281C12.4431 8.44591 12.5754 8.30691 12.5754 8.13701V6.10412C12.5754 5.93404 12.4431 5.79632 12.281 5.79632ZM10.8338 7.1185V7.73276C10.8338 7.8031 10.7623 7.86263 10.6768 7.86263H10.3236C10.238 7.86263 10.1665 7.8031 10.1665 7.73276V7.1185C10.0835 7.0513 10.0353 6.95837 10.0353 6.85557C10.0353 6.66076 10.2182 6.49337 10.4508 6.48564C10.4755 6.48482 10.5249 6.48482 10.5495 6.48564C10.7821 6.49337 10.9651 6.66076 10.9651 6.85557C10.9651 6.95837 10.9168 7.0513 10.8338 7.1185ZM11.4822 5.79632H10.5495H10.4508H9.5181V5.391C9.5181 4.94444 9.95903 4.5752 10.5002 4.5752C11.0413 4.5752 11.4822 4.94444 11.4822 5.391V5.79632H11.4822Z" fill="#FF1988"/></g><defs><clipPath id="clip0"><rect width="5.4" height="4.44444" fill="white" transform="translate(7.80029 4.00146)"/></clipPath></defs>
                            </svg>
                        </div>
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
            padding: 30px 16px 0 24px;
            display: flex;
            flex-direction: row;
            justify-content: space-between;
            align-items: flex-start;
            z-index: 5;
            .broadcast__indicator{
                display: flex;
                flex-direction: row;
                align-items: center;
                .broadcast__indicator-view{
                    background: rgba(0, 0, 0, 0.3);
                    backdrop-filter: blur(20px);
                    border-radius: 50px;
                    display: flex;
                    flex-direction: row;
                    align-items: center;
                    padding: 12px 15px;
                    .broadcast__indicator-number{
                        color: white;
                        margin: 0 0 0 9px;
                        font-family: SF Pro Display;
                        font-style: normal;
                        font-weight: bold;
                        font-size: 18px;
                        line-height: 21px;
                    }
                }
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
            .broadcast__send-input{
                background: rgba(0, 0, 0, 0.3);
                backdrop-filter: blur(20px);
                border-radius: 50px;
                border: none;
                padding: 13px 0 14px 18px;
                margin-right: 8px;
                width: 100%;
            }
            .broadcast__send-btn{
                background: rgba(0, 0, 0, 0.3);
                backdrop-filter: blur(20px);
                border-radius: 50px;
                width: 45px;
                height: 45px;
                border: none;
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
                margin: 8px auto 29px;
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
        }
    }
</style>