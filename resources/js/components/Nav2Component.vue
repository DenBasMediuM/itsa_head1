<script setup>
// import logoPath from '../../../public/logo.png';
</script>

<template>
    <div class="container">
        <div class="content">
            <div class="content_logo">
<!--                <img :src="logoPath" alt="Логотип">-->
            </div>
            <div class="content_panel panel">
                <div class="panel_menu menu">
                    <nav>
                        <ul>
                            <li><a href="#">Портфолио</a></li>
                            <li><a href="#">Оферта</a></li>
                            <li><a href="#">Отзывы</a></li>
                            <li><a href="#">Отправка НП</a></li>
                            <li><a href="#">Франшиза</a></li>
                            <li><a href="#">Блог</a></li>
                            <li><a href="#">Контакты</a></li>
                        </ul>
                    </nav>
                </div>
                <div class="panel_buttons-panel panel-buttons">
                    <div class="panel-buttons_buttons">
                        <button type="button" class="btn btn-primary">Записаться на диагностику</button>
                        <button type="button" class="btn btn-danger">Жалоба директору</button>
                        <button type="button" class="btn btn-primary">Вызвать курьера</button>
                    </div>
                    <div class="panel-buttons_social">
                        <div class="social-icons">
                            <a href="#" target="_blank"><i class="fab fa-facebook"></i></a>
                            <a href="#" target="_blank"><i class="fab fa-instagram"></i></a>
                            <a href="#" target="_blank"><i class="fab fa-youtube"></i></a>
                            <a href="#" target="_blank"><i class="fab fa-telegram"></i></a>
                            <a href="#" target="_blank"><i class="fab fa-viber"></i></a>
                            <!-- Добавьте другие иконки по необходимости -->
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
    .container {
    }

    .content {
        display: flex;
        gap: 10px;
        margin: 10px 0 10px 0;
    }

    .content_logo {
        display: flex;
    }

    .content_panel {
        width: 100%;
    }

    .panel {
    }

    .panel_menu {
    }

    .menu {
        margin: 10px;
    }

    ul {
        list-style-type: none;
        margin: 0;
        padding: 0;
        display: flex;
        justify-content: space-around;
        font-size: 16px;
    }

    a {
        text-decoration: none;
        color: black;
        transition: color 0.3s;

        &:hover {
            color: blue;
        }
    }

    .panel_buttons-panel {
        display: flex;
        gap: 10px;
        justify-content: space-around;
    }

    .panel-buttons {
    }

    .panel-buttons_buttons {
        display: flex;
        width: 70%;
        justify-content: space-between;
        gap: 5px;
    }

    .btn {
        white-space: nowrap;
    }

    .btn-primary {
    }

    .btn-danger {
    }

    .panel-buttons_social {
    }

    .social-icons {
        display: flex;
        justify-content: space-between;
        gap: 5px;
        font-size: 30px;
    }

    .fab {
    }

    .fa-facebook {
    }

    .fa-instagram {
    }

    .fa-youtube {
    }

    .fa-telegram {
    }

    .fa-viber {
    }
</style>
