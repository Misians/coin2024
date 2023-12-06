<template>
  <div class="container">


  <v-card     class="mx-auto"
    max-width="344">
    <v-img
      :src="imageSrc"
      height="200px"
      cover
    ></v-img>

    <v-card-title>
      {{ name }}
    </v-card-title>

    <v-card-subtitle>
      {{ role }}
    </v-card-subtitle>

    <v-card-actions>
      <v-btn
        color="orange-lighten-2"
        variant="text"
      >
        Explore
      </v-btn>

      <v-spacer></v-spacer>

      <v-btn
        :icon="show ? 'mdi-chevron-up' : 'mdi-chevron-down'"
        @click="show = !show"
      ></v-btn>
    </v-card-actions>

    <v-expand-transition>
      <div v-show="show">
        <v-divider></v-divider>

        <v-card-text>
          {{ bio }}
        </v-card-text>
      </div>
    </v-expand-transition>
  </v-card>
  </div>
</template>

<script>
export default {
  props: {
    name: String,
    role: String,
    imageSrc: String,
    bio: String,
  },
  data: () => ({
    show: false,
  }),
};
</script>

<style scoped>
.container {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  margin: 20px;
  padding: 10px;
}
.img{
  width: 100%;
}

</style>
