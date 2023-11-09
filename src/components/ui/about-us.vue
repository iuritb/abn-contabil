<template>
  <div class="about">
    <div class="about">
      <div class="about__title">Conheça a nossa equipe</div>
      <div class="about__description">
        A ABN Contábil tem um compromisso sólido com o seu sucesso financeiro.
        Somos uma equipe de profissionais contábeis altamente especializados,
        dedicados a oferecer soluções de planejamento tributário que transcendem
        o comum. Nossa experiência é sua vantagem competitiva, e nosso foco é
        transformar complexidades tributárias em oportunidades estratégicas.
      </div>
    </div>

    <div class="about__section">
      <div class="about__image"></div>
      <div class="about__text">
        <p class="about__text-item">
          <span class="about__text-item-bold">Confiança Construída:</span>Com
          anos de atuação no setor, conquistamos a confiança de nossos clientes
          ao longo de inúmeras situações fiscais desafiadoras. Acreditamos que a
          base de um relacionamento bem-sucedido é a confiança mútua, e estamos
          empenhados em ser o parceiro confiável que você merece.
        </p>
        <p class="about__text-item">
          <span class="about__text-item-bold"
            >Experiência que Impulsiona Resultados:</span
          >Nossa equipe é composta por especialistas apaixonados pelo que fazem.
          Dominamos as complexidades em constante evolução do cenário
          tributário, utilizando nossa expertise para maximizar seus ganhos e
          minimizar suas obrigações fiscais. Não apenas compreendemos as regras
          - estamos à frente delas.
        </p>
        <p class="about__text-item">
          <span class="about__text-item-bold"
            >Soluções Personalizadas para Você:</span
          >Sabemos que cada empresa é única. Portanto, não adotamos uma
          abordagem genérica. Em vez disso, trabalhamos lado a lado com você,
          entendendo suas metas e desafios específicos. Nossas soluções de
          planejamento tributário são adaptadas às suas necessidades exclusivas,
          garantindo que suas finanças estejam em conformidade e otimizadas para
          o sucesso.
        </p>
        <p class="about__text-item">
          Estamos empenhados em ser seu guia no mundo complexo dos impostos e
          das finanças. Junte-se a nós para uma jornada de descoberta,
          estratégia e prosperidade. Sua visão é nossa missão, e estamos prontos
          para transformar suas aspirações em realidade financeira.
        </p>
        <p class="about__text-item">
          Descubra como nosso planejamento tributário pode fazer a diferença.
        </p>
      </div>
    </div>

    <v-btn class="help-button" color="#D6C7B4">
      Entrar em contato
    </v-btn>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
p {
  margin: 0px;
}
.about {
  margin: 5px 72px;
  display: flex;
  flex-direction: column;
  justify-content: start;

  &__title {
    color: #333;
    font-size: 48px;
    font-style: normal;
    font-weight: 700;
    line-height: 52.8px; /* 110% */
    text-align: left;
  }
  &__description {
    margin-top: 35px;
    color: #000;
    font-size: 18px;
    font-style: normal;
    font-weight: 400;
    line-height: 25.2px; /* 140% */
    text-align: left;
  }
  &__section {
    margin: 56px 72px;
    display: flex;
    flex-direction: row;
  }
  &__image {
    background: #d9d9d9;
    border-radius: 8px;
    width: 448px;
    height: 555px;
    flex-shrink: 0;
  }
  &__text {
    display: flex;
    flex-direction: column;
    justify-content: space-around;

    margin-left: 72px;
    text-align: left;
  }
  &__text-item {
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 22.4px;
  }
  &__text-item-bold {
    font-weight: 700;
  }
}
.help-button {
  align-self: center;
  color: #fff;
  width: 370px;
  height: 70px  !important; 
  border-radius: 8px;
  font-size: 14px;
  font-style: normal;
  font-weight: 700;
  line-height: 28px; /* 140% */
  gap: 10px;
}
</style>