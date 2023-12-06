<template>
  <div class="cards-comissao">
    <h1>Comissão</h1>
    <div class="container">
      <comissao-card
        v-for="(member, index) in comissaoMembers"
        :key="index"
        :name="member.name"
        :role="member.role"
        :image-src="member.imageSrc"
        :bio="member.bio"
      />
    </div>
  </div>
</template>

<script>
import ComissaoCard from "../components/comissaoCard.vue";

export default {
  components: {
    ComissaoCard,
  },
  data() {
    return {
      comissaoMembers: [
        {
          name: "Artemísia Kimberlly",
          role: "Graduanda em ciência da computação",
          imageSrc: "https://i.imgur.com/tQ6kDGz.jpeg",
          bio: "Desenvolvedora web fullstack a 1 ano e meio, atualmente no oitavo período de ciência da computação",
        },
        {
          name: "Maria Clara",
          role: "Graduanda em ciência da computação",
          imageSrc: "https://i.imgur.com/kqwbugN.jpeg",
          bio: "Desenvolvedora web fullstack a 1 ano e meio, atualmente no oitavo período de ciência da computação",
        },
        {
          name: "Emilly",
          role: "Graduanda em ciência da computação",
          imageSrc: "https://i.imgur.com/mEfpWbc.jpg",
          bio: "Desenvolvedora web fullstack a 1 ano e meio, atualmente no oitavo período de ciência da computação",
        },
        {
          name: "Yuri",
          role: "Graduando em ciência da computação",
          imageSrc: "https://i.imgur.com/8nua8WN.jpg",
          bio: "Desenvolvedora web fullstack a 1 ano e meio, atualmente no oitavo período de ciência da computação",
        },
        {
          name: "Bertulino",
          role: "Doutor em ciÊncias da computaç",
          imageSrc: "https://i.imgur.com/8vIadRJ.jpg",
          bio: "Desenvolvedora web fullstack a 1 ano e meio, atualmente no oitavo período de ciência da computação",
        },
        {
          name: "Ismael",
          role: "Graduando em ciência da computação",
          imageSrc: "https://i.imgur.com/fyfyOHE.jpg",
          bio: "Desenvolvedora web fullstack a 1 ano e meio, atualmente no oitavo período de ciência da computação",
        },
        // Adicione outros membros da comissão conforme necessário
      ],
    };
  },
};
</script>

<style scoped>
.cards-comissao {
  text-align: center; /* Centralizar o conteúdo */
}

.container {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between; /* Distribuir os cards ao redor do centro */
  margin: 20px;
}

.comissao-card {
  flex: 0 0 300px; /* Largura fixa dos cards (ajuste conforme necessário) */
  width: 100px;
  margin-bottom: 20px; /* Adicionar espaço entre os cards */

}
.img{
  width: 100%;
}
</style>
