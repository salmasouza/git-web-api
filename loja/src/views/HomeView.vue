<template>

    <section>
      <h1> 👍👎 Compre ou Venda</h1>
      <ProdutosLista />
      <ProdutosBusca />
   </section>

</template>

<script>
import ProdutosBusca from "@/components/ProdutosBusca.vue";
import ProdutosLista from "@/components/ProdutosLista.vue";

export default {
  name: 'HomeView',

  components: {
    ProdutosBusca,
    ProdutosLista
  },
  
};

</script>

<style scoped>
h1 {
  color: #87f;
  margin-top: 40px;
  font-size: 2rem;
  text-align: center;
}


</style>
