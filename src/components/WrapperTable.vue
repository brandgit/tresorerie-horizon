<script setup>
import logoInfo from '../assets/iconeInfo.png'
import logoUpdate from '../assets/iconeUpdate.png'
let test = 'test'
let DATE = '01-28-2022'
const data = [
    { date: (DATE), amount: -56, mean: 'Carte bancaire', categories: test, description: 'Commande Amazon pour le ReName ZEvent #124 : Cachet de cire' },
    { date: new Date('01-27-2021'), amount: -56, mean: 'Carte bancaire', categories: ['test'], description: 'Commande Amazon pour le ReName ZEvent #124 : Cachet de cire' },
    { date: new Date('01-27-2021'), amount: -56, mean: 'Carte bancaire', categories: ['test'], description: 'Commande Amazon pour le ReName ZEvent #124 : Cachet de cire' },
    { date: new Date('01-27-2021'), amount: -56, mean: 'Carte bancaire', categories: ['test'], description: 'Commande Amazon pour le ReName ZEvent #124 : Cachet de cire' },
    { date: new Date('01-27-2021'), amount: -56, mean: 'Carte bancaire', categories: ['test'], description: 'Commande Amazon pour le ReName ZEvent #124 : Cachet de cire' },
    { date: new Date('01-27-2021'), amount: -56, mean: 'Carte bancaire', categories: ['test'], description: 'Commande Amazon pour le ReName ZEvent #124 : Cachet de cire' },
]
</script>


<template>
    <div class="flex bloc4 justify-center">
        <div class="mx-10 bg-white " > 

             <table class="table-fixed w-full ">
                <thead >
                  <tr  class="border-b-2 h-16" >
                    <th>DATE D'OPERATION</th>
                    <th>MONTANT</th>
                    <th>TYPE DE PAIEMENT</th>
                    <th>CATEGORIES</th>
                    <th>DESCRIPTION</th>
                  </tr>
                </thead>
                <tbody>
                    <tr v-for="(line, i) in data" :key="i" class="border-b-2 h-20 mr-5">
                        <td class="" >{{ line.date }}</td>
                        <td class=" flex justify-center">{{ line.amount }}</td>
                        <td class="">{{ line.mean }}</td>
                        <td class="">{{ line.categories }}</td>
                        <td>{{ line.description }}</td>
                    <td class="flex  justify-end  h-20 place-items-center">
                        <span><button class=" flex justify-center w-10 h-10 place-items-center rounded-full" ><img :src="logoInfo" class="h-7"></button></span> 
                        <span><button class=" flex justify-center w-10 h-10 place-items-center rounded-full bg-slate-300 mr-5" ><img :src="logoUpdate" class="h-7"></button></span>
                    </td>
                    </tr>
                </tbody>
              </table>

        </div>
      </div>
</template>
