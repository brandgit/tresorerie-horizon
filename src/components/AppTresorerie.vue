<script setup>
let recettes = 1000
</script>
<template class=" h-screen  bg-sky-500" >

  <div class="global-container bg-slate-300 font-mono">
      <div class="flex bloc1 bg-black justify-center">
        <div class="flex  justify-between wrapper-bloc1 pr-10 pl-10 bg-slate-300  w-4/6 " > 
          <h1 class="flex self-center  text-3xl ">Tresorerie</h1>
          <button class=" flex self-center pl-3 pt-1 bg-sky-600 w-28 h-9 rounded-3xl" >+ Ajouter</button>
        </div>
      </div>

      <div class="flex bloc2  justify-center">
        <div class="flex wrapper-bloc2 w-4/6 " > 
            <div class="basis-1/2 bg-red-400 recettes-wrapper">

            </div>
            <div class="basis-1/2 bg-amber-300 depenses-wrapper">

            </div>
            <div class="basis-1/2 bg-lime-400 solde-wrapper">
              
            </div>
        </div>
      </div>
      
       <div class="flex bloc3 justify-center">
        <div class="wrapper-bloc3 bg-white w-4/6 " > 
          <div>><span>Filtres</span></div>
        </div>
      </div>
       <div class="flex bloc4 justify-center">
        <div class="wrapper-bloc4 bg-white w-4/6 " > 

             <table class="table-fixed w-full">
                <thead >
                  <tr  >
                    <th  >DATE D'OPERATION</th>
                    <th  >MONTANT</th>
                    <th>TYPE DE PAIEMENT</th>
                    <th >CATEGORIES</th>
                    <th >DESCRIPTION</th>
                  </tr>
                </thead>
                <tbody>
                  <tr>
                    <td>27 oct. 2021</td>
                    <td>- <span>56,38</span></td>
                    <td>Cart bancaire</td>
                    <td>Dépenses géné</td>
                    <td>Commande Amazon pour le ReName ZEvent #124 : Cachet de cire</td>
                    <td class="flex  justify-end"><span>Info</span> <span>Upd</span></td>
                  </tr>

                  <tr>
                    <td>1 avr. 2021</td>
                    <td>+ <span>1 500,00</span></td>
                    <td>Cart bancaire</td>
                    <td>Subvention</td>
                    <td>OVH Domaines</td>
                    <td class="flex  justify-end"><span>Info</span> <span>Upd</span></td>
                  </tr>

                  <tr>
                    <td>4 mars 2021</td>
                    <td>- <span>16,7>8</span></td>
                    <td>Cart bancaire</td>
                    <td>Dépenses géné</td>
                    <td class="flex  justify-end"><span>Info</span> <span>Upd</span></td>
                  </tr>

                  
                  <tr>
                    <td>11 janv. 2021</td>
                    <td>- <span>63,75</span></td>
                    <td>Cart bancaire</td>
                    <td>Dépense généréles</td>
                    <td>Prix carte bleue à l'année</td>
                    <td class="flex  justify-end"><span>Info</span> <span>Upd</span></td>
                  </tr>

                  
                  <tr>
                    <td>7 janv. 2021</td>
                    <td>- <span>18,00</span></td>
                    <td>Cart bancaire</td>
                    <td>Produit dérivé</td>
                    <td>Achat de stikers sticj=kermule</td>
                   <td class="flex  justify-end"><span>Info</span> <span>Upd</span></td>
                  </tr>

                  
                  <tr>
                    <td>11 dec. 2020</td>
                    <td>- <span>22,00</span></td>
                    <td>Cart bancaire</td>
                    <td>Don</td>
                    <td>Remboursement à Timoté Chauvet pour un don de 22 € au nom de ReName pour le</td>
                    <td class="flex  justify-end"><span>Info</span> <span>Upd</span></td>
                   
                  </tr>

                
                </tbody>
              </table>

        </div>
      </div>
  </div>
</template>



<style scoped>
.global-container{
  width: 100%;
  height: 100%;
  
}

.bloc1{
   width: 100%;
  height: 10%;
}

.bloc2{
   width: 100%;
  height: 15%;
  background: wheat;
}
.bloc3{
   width: 100%;
  height: 8%;
  background: yellow;
}
.bloc4{
  width: 100%;
  height: 67%;
  background: red;
}

</style>