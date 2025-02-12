<script setup lang="ts">
const text = 'Hello, Vue 3 + Vite!'
</script>

<template>
  <v-container>
    <v-form>
      <v-row align="center">
        <v-col cols="6">
          <v-text-field label="Nickname"></v-text-field>
        </v-col>
      </v-row>
      <v-row align="center">
        <v-col cols="5">
          <v-btn color="primary">Play</v-btn>
        </v-col>
      </v-row>
    </v-form>
  </v-container>
</template>

<style scoped>
main {
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 2rem;
}
</style>
