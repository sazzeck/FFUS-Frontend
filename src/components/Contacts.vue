<template>
    <section class="page__contacts contacts" id="contacts">
        <div class="contacts__container-big">
            <div class="contacts__container">
                <div class="contacts__wrapper">
                    <div class="contacts__lable">
                        <div class="contacts__lable__wrapper">
                            <p class="contacts__lable__email">furniturefory@gmail.com</p>
                            <div class="contacts__lable__phone-items">
                                <p class="contacts__lable__item">+38 (099) 000 00 00</p>
                                <p class="contacts__lable__item">+38 (099) 000 00 00</p>
                            </div>
                        </div>
                    </div>
                    <div class="contacts__body" id="order">
                        <div class="contacts__body__wrapper">
                            <div class="contacts__body__header">
                                <h1 class="contacts__body__header__lable">Залишіть заявку на консультацію</h1>
                                <p class="contacts__body__header__text">Заповніть форму нижче, щоб залишити заявку на консультацію.</p>
                                <p class="contacts__body__header__text">Ми зв'яжемося з Вами якнайшвидше.</p>
                            </div>
                            <div class="contacts__body__form">
                                <form action="POST" class="form">
                                    <div class="form__wrapper">
                                        <input autocomplete="off" type="text" name="form[]"
                                            data-error="Some Error" placeholder="Ваше ім’я" class="form__input">
                                        <input autocomplete="off" type="text" name="form[]" data-error="Error"
                                            placeholder="Телефон" class="form__input">
                                            <div class="form__handler"></div>
                                        </div>
                                    <button type="submit" class="form__button">залишити заявку</button>
                                </form>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "Contacts"
    }
</script>