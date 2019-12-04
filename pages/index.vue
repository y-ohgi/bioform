<template>
  <v-layout
    column
    justify-center
    align-center
  >
    <v-flex
      xs12
      sm8
      md6
    >
      <v-card>
        <card />
      </v-card>
    </v-flex>
  </v-layout>
</template>

<script lang="ts">
import Card from "~/components/Card.vue"

export default {
  components: {
    Card
  }
}
</script>
