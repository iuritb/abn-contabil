<template>
  <div>
    <div class="cards">
      <div class="cards">
        <ImageCard
          description="Com estratégias personalizadas, ajudamos você a identificar oportunidades para economizar dinheiro, maximizando os benefícios fiscais que você merece."
          title="Economize Mais"
          image="image-1.jpeg"
        />
      </div>
      <div class="cards">
        <ImageCard
          description="Reduza sua carga tributária de forma legal e ética, aproveitando as leis e regulamentos mais recentes para otimizar suas obrigações fiscais."
          title="Otimização Fiscal"
          image="image-2.jpeg"
        />
      </div>
      <div class="cards">
        <ImageCard
          description="Não se trata apenas de pagar menos impostos, mas também de estruturar suas finanças de maneira inteligente. Nossas estratégias visam impulsionar seu crescimento financeiro a longo prazo."
          title="Estratégias Inteligentes"
          image="image-3.jpeg"
        />
      </div>
    </div>
    <v-btn class="help-button" color="#1F334B">
      Saiba como podemos ajudar!
    </v-btn>
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
.cards {
  margin-top: 65px;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  align-items: center;
  flex-wrap: wrap;
}
.help-button {
  color: #fff;
  margin: 35px 70px;
  width: 490px;
  height: 70px  !important; 
  border-radius: 8px;
  font-size: 14px;
  font-style: normal;
  font-weight: 700;
  line-height: 28px; /* 140% */
  gap: 10px;
}
</style>