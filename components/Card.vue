<template>
  <div class="card">
    <h2>{{name}}</h2>
  </div>
</template>

<script lang="ts">
import Vue from "vue"
import { Person } from "~/types";

export default Vue.extend({
    data(): Person {
        return {
            id: 1,
            name: "fuga"
        }
    }
})
</script>

<style scoped>
.card {
  font-family: "Segoe UI", Tahoma, Geneva, Verdana,
    sans-serif;
  padding: 1rem;
  margin: 0.25rem;
  border: 0.25rem solid gainsboro;
}
</style>