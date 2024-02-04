<template>
    <div class="repair">
        <div class="container mt-[10px]">
            <h2 class="title text-[30px]">Проведение ТО и мелкий ремонт</h2>
            <TabProducts/>
            <div class="add-product p-[20px]">
                <button class="btn bg-[#2f8cff] text-white py-[10px] px-[15px] flex items-center gap-[7px] rounded-[5px]">
<img src="../../../assets/icons/plus-icon.svg" alt="">
Добавить строку
                </button>
            </div>
        </div>
    </div>
</template>
<script>
import TabProducts from '../components/TabProducts.vue';

export default{
    components: { TabProducts }
}
</script>