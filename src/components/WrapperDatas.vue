<script setup>
let sommeRecette = 2390.09;
let sommeDepenses = 2336.40;
let sommeSolde = 54.05;
import logoRecettes from '../assets/iconeRecettes.png'
import logoSolde from '../assets/iconeSolde.png'
import logoDepenses from '../assets/iconeDepenses.png'
</script>


<template>
    <div class="flex flex-row justify-center place-items-center space-x-6 h-full">
        <div class="bloc1 bg-white flex justify-between place-items-center  ">
            <div class="wrapperRecettes ml-10 ">
                <p>Recettes</p>
               <h1 class="flex font-bold text-black text-old text-3xl ">{{sommeRecette}} <span> €</span> </h1>
                
            </div>
            <div class="logoRecettes flex justify-center w-14 h-14 place-items-center rounded-full bg-slate-300 mr-10">
                <img :src="logoRecettes" class="w-8">
            </div>
        </div>

        <div class="bloc2  bg-white flex justify-between place-items-center">
             <div class="wrapperRecettes ml-10 ">
                <p>Depenses</p>
               <h1 class="flex font-bold text-black text-old text-3xl ">{{sommeDepenses}} <span> €</span> </h1>
                
            </div>
            <div class="logoRecettes flex justify-center w-14 h-14 place-items-center rounded-full bg-slate-300 mr-10">
                <img :src="logoDepenses" class="w-8">
            </div>
        </div>

        <div class="bloc3  bg-white flex justify-between place-items-center">
             <div class="wrapperRecettes ml-10 ">
                <p>Solde</p>
               <h1 class="flex font-bold text-black text-old text-3xl ">{{sommeSolde}} <span> €</span> </h1>
                
            </div>
            <div class="logoRecettes flex justify-center w-14 h-14 place-items-center rounded-full bg-slate-300 mr-10">
                <img :src="logoSolde" class=" w-8">
            </div>
        </div>
    </div>
</template>


<style>
    .bloc1, .bloc2, .bloc3 {
    width: 30.5%;
    height: 85%;
    overflow: hidden;
    }
</style>