<template>
  <h1>¿Quién es este Pokemon?</h1>
  <pokemonPicture :pokemonId="9" :showPokemon="true"/>
 <pokemonOptions/>
</template>

<script>
import pokemonPicture from '@/components/pokemonPicture';
import pokemonOptions from '@/components/pokemonOptions';


export default {
    components:{
        pokemonPicture,
        pokemonOptions,
    }
}
</script>

<style>

</style>