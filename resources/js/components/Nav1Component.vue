<script setup>
    import '@fortawesome/fontawesome-free/css/all.css';
</script>

<template>
    <div class="content shadow-sm bg-body-tertiary rounded">
        <div class="container">
            <div class="blocs">
                <div class="block">
                    <div class="block_content">
                        <div class="area_block">
                            <i class="fas fa-location-dot"></i>
                            <div class="area_name">Центр</div>
                            <i class="fa-solid fa-arrow-down"></i>
                        </div>
                        <div class="area">
                            <div class="filial">пер. Каретный, 18</div>
                            <div class="filial">ул. Екатерининская, 73</div>
                        </div>
                    </div>
                    <div class="tels">
                        <i class="fa-solid fa-phone-volume"></i>
                        <a href="tel:+380931703105">+38 (093) 170 31 05</a>
                        <a href="tel:+380961154611">+38 (096) 11 546 11</a>
                    </div>
                </div>
                <div class="block">
                    <div class="block_content">
                        <div class="area_block">
                            <i class="fas fa-location-dot"></i>
                            <div class="area_name">Фонтан / пр.Шевченко</div>
                            <i class="fa-solid fa-arrow-down"></i>
                        </div>
                        <div class="area">
                            <div class="filial">ул. Сегедская, 23</div>
                        </div>
                    </div>
                    <div class="tels">
                        <i class="fa-solid fa-phone-volume"></i>
                        <a href="tel:+380931708353">+38 (093) 170 83 53</a>
                    </div>
                </div>
                <div class="block">
                    <div class="block_content">
                        <div class="area_block">
                            <i class="fas fa-location-dot"></i>
                            <div class="area_name">Поселок Котовского</div>
                            <i class="fa-solid fa-arrow-down"></i>
                        </div>
                        <div class="area">
                            <div class="filial">ул. Сахарова, 20</div>
                        </div>
                    </div>
                    <div class="tels">
                        <i class="fa-solid fa-phone-volume"></i>
                        <a href="tel:+380931707330">+38 (093) 170 73 30</a>
                    </div>
                </div>
                <div class="block">
                    <div class="block_content">
                        <div class="area_block">
                            <i class="fas fa-location-dot"></i>
                            <div class="area_name">Таирово</div>
                            <i class="fa-solid fa-arrow-down"></i>
                        </div>
                        <div class="area">
                            <div class="filial">ж\м Радужный, 19/3</div>
                            <div class="filial">Люстдорфская дорога, 142</div>
                        </div>
                    </div>
                    <div class="tels">
                        <i class="fa-solid fa-phone-volume"></i>
                        <a href="tel:+380937559626">+38 (093) 755 96 26</a>
                        <a href="tel:+380931708682">+38 (093) 170 86 82</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
    .content {
        //background-color: #1fafc9;
        //color: white;

    }
    .blocs{
        display: flex;
        flex-wrap: wrap; /* Разрешает перенос элементов на новую строку */
        justify-content: space-between;
        gap: 10px;

        padding: 10px 0 10px 0;
    }
    .block, .block_content {
        display: flex;
        flex-direction: column;
        gap: 10px;
    }
    .tels {
        display: flex;
        gap: 10px;
        align-items: center;
    }
    .area_block {
        display: flex;
        gap: 10px;
        align-items: center;
    }
</style>

<style>
/* Глобальные стили */
.area {
    opacity: 0;
    max-height: 0;
    overflow: hidden;
    margin-top: -20px;
    transition: opacity 0.3s, max-height 0.3s, margin-top 0.3s;
}
.block_content:hover .area {
    max-height: 45px;
    opacity: 1;
    margin-top: 0px;
}
</style>
