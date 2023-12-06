<template>
  <v-app-bar>
    <v-app-bar-title>
      <img src="../../assets/uern.png" width="100" alt="">
    </v-app-bar-title>
    <v-app-bar-title>
      Home
    </v-app-bar-title>
    <v-app-bar-title>
      Comissão
    </v-app-bar-title>
    <v-app-bar-title>
      Contato
    </v-app-bar-title>
  <v-app-bar-title>
    <v-btn @click="toggleTheme">theme</v-btn>
  </v-app-bar-title>
</v-app-bar>


</template>

<script setup>
 import { useTheme } from 'vuetify'

const theme = useTheme()

function toggleTheme () {
  theme.global.name.value = theme.global.current.value.dark ? 'light' : 'dark'
}
</script>
<style>
v-app-bar-title {
  margin-top: 20px;
  justify-content: center;
  text-align: center;
  margin: 0 auto;
}
v-app-bar-title img{
  margin: 0 auto;
}
</style>
