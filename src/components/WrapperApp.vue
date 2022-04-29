<script setup>
import WrapperOnYourMind from './WrapperOnYourMind.vue'
import WrapperFilters from './WrapperFilters.vue'
import WrapperTable from './WrapperTable.vue'
import WrapperDatas from './WrapperDatas.vue'
</script>


<template>
   <div class="flex flex-col h-screen w-screen bg-slate-300 ">

        <div class=" wrapperOnYourMind  ">
            <WrapperOnYourMind/>
        </div>

        <div class="wrapperDatas  ">
            <WrapperDatas/>
        </div>
        <div class="wrapperFilters flex justify-center place-items-center ml-8 ">
            <WrapperFilters/>
        </div>
         <div class="wrapperTable scroll-auto ">
            <WrapperTable/>
         </div>
   </div>
</template>


<style>
    .wrapperOnYourMind{
        width:100%;
        height: 10%;
    }
    .wrapperDatas{
        width:100%;
        height: 24%;
    }
    .wrapperFilters{
        width:96%;
        height: 12%;
    }
    .wrapperTable{
        width:100%;
        height:54%;
    }
</style>