<template>
  <div>
    <h1>¿Quien es este pokemon?</h1>
    <PokemonPicture :pokemonId="6" :showPokemon="true" />
    <PokemonOptions />
  </div>
</template>

<script>

import PokemonPicture from "@/components/PokemonPicture";
import PokemonOptions from "@/components/PokemonOptions"

export default {
  name: "PokemonPage",
  components: {
    PokemonPicture, PokemonOptions
  }

}
</script>

<style scoped>

</style>