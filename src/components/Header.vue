<template>
    <header class="header">
        <div class="header__container-big">
            <img src="@/assets/img/logo.svg" alt="Logo" class="logo">
            <div class="header__menu">
                <nav class="header__menu__body">
                    <ul class="header__menu__list">
                        <li class="header__menu__item"><a href="#order" class="header__menu__link">замовити</a></li>
                        <li class="header__menu__item"><a href="#about_us" class="header__menu__link">про нас</a></li>
                        <li class="header__menu__item"><a href="#contacts" class="header__menu__link">контакти</a></li>
                    </ul>
                </nav>
            </div>
            <button class="icon-menu"><span></span></button>
        </div>
    </header>
</template>

<script>
export default {
    name: "Header"
    }
</script>
