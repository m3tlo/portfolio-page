<template>
    <div class="container footer__container">
        <ul class="footer__content">
            <li class="footer__contact-info">
                <p>Тел: +7(961)-617-47-59</p>
                <p>Telegram: @DYuMikheev</p>
                <p>E-mail: <a href="mailto:daniil.mikheev228@gmail.com">daniil.mikheev228@gmail.com</a></p>
            </li>
            <li class="footer__web-site-info">
                <p>Voronezh</p>
                <p>2023</p>
            </li>
            <li class="footer__web-site-stack">
                <p>Сайт создан при использовании:</p>
                <p>HTML5, CSS3, JavaScript(ES6), Vue3</p>
            </li>
        </ul>
    </div>
</template>


<style>
ul {
    display: flex;
    justify-content: space-between;
}

ul li {
    justify-content: space-evenly;
    display: flex;
}

.footer__contact-info, .footer__web-site-info, .footer__web-site-stack {
    display: flex;
    flex-direction: column;
}
.footer__web-site-info{
    text-align: center;
}
ul p, a{
    margin:2px 0;
    font-size: 13px;
}
</style>
