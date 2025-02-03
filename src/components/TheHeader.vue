<template>
    <header class="">
        <div class="container">
            <div class="flex justify-center items-center py-1 bg-[#11111180]">
                <p class="text-white"><i class="fa-solid fa-location-dot"></i> МАГАЗИНЫ ОТКРЫТЫ ПО НОВОМУ АДРЕСУ</p>
            </div>
            <div class="flex justify-between">
                <div><img class="logo" src="@/assets/img/Logo.png" alt=""></div>
                <div class="flex gap-3">
                    <div class="flex p-1"><i class="fa-solid fa-location-dot px-2 py-1 text-[#fff]"></i>
                        <p class="text-[#fff]"> Санкт-Петербург</p>
                    </div>
                    <div class="flex">
                        <i class="fa-solid fa-phone text-[#fff] px-2 py-2.5"></i>
                        <h3 class="text-[#fff] py-1.5">8 (999) 888-77-66</h3>
                    </div>
                </div>
            </div>
        </div>
    </header>
</template>

<style>
    header {
        background-image: url("@/assets/img/header-bg.png");
        min-height: 128px;
        background-size: cover;
        background-repeat: no-repeat;
    }
</style>
