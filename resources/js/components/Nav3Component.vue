<script setup>

</script>

<template>
    <div class="content">
        <div class="container">
            <nav>
                <ul>
                    <li><a href="#">Телефоны, ноутбуки, гаджеты</a></li>
                    <li><a href="#">ТВ и бытовая техника</a></li>
                    <li><a href="#">Принтеры, картриджи, офисная техника</a></li>
                    <li><a href="#">Коммерческая электроника</a></li>
                    <li><a href="#">Прочие услуги</a></li>
                </ul>
            </nav>
        </div>
    </div>
</template>

<style scoped>
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
        color: white;
    }
    nav {
    }
    .content {
        padding: 10px 0;
        margin: 20px 0 10px 0;
        background-color: #1fafc9;
    }
</style>
