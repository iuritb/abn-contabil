<template>
  <div>
    <v-row >
      <v-col>
        <ImageCard
          description="Com estratégias personalizadas, ajudamos você a identificar oportunidades para economizar dinheiro, maximizando os benefícios fiscais que você merece."
          title="Economize Mais"
          image="../../assets/img/image-1.jpeg"
        />
      </v-col>
      <v-col>
        <ImageCard
          description="Reduza sua carga tributária de forma legal e ética, aproveitando as leis e regulamentos mais recentes para otimizar suas obrigações fiscais."
          title="Otimização Fiscal"
        />
      </v-col>
      <v-col>
        <ImageCard
          description="Não se trata apenas de pagar menos impostos, mas também de estruturar suas finanças de maneira inteligente. Nossas estratégias visam impulsionar seu crescimento financeiro a longo prazo."
          title="Estratégias Inteligentes"
        />
      </v-col>
    </v-row>
  </div>
</template>

<script>
import ImageCard from "./card.vue";
// import batata from "../../assets/img/"
export default {
  components: {
    ImageCard,
  },
};
</script>

<style lang="scss" scoped>
</style>