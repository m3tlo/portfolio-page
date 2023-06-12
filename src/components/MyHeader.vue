<template>
    <div class="container header__container">
        <div class="header__icon"></div>
            <menu class="header__menu">
                <li>Главная</li>
                <li>Мои работы</li>
                <li>Обо мне</li>
            </menu>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="css" scoped>
.header__container{
    align-items: center;
    display: flex;
}
.header__icon{
    height: 75px;
    width: 75px;
    border-radius: 50%;
    background: #111;

}
menu{
    width: 100%;
    justify-content: space-evenly;
    display: flex;
}
menu li {
    list-style: none;
    padding: 5px 10px;
    border-radius: 20px;
    cursor: pointer;
}
menu li:hover{
    background: #e7d8c7;
    transition: all ease 0.3s;
}
</style>