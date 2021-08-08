<template>
  <v-layout align-center wrap>
    <v-flex text-center>
      <v-btn elevation="2" @click="onClick">Click Me</v-btn>
    </v-flex>
    <v-flex text-center>
      <img
        src="/v.png"
        alt="Vuetify.js"
        class="mb-5"
      >
      <blockquote class="blockquote">
        &#8220;First, solve the problem. Then, write the code.&#8221;
        <footer>
          <small>
            <em>&mdash;John Johnson</em>
          </small>
        </footer>
      </blockquote>
    </v-flex>
  </v-layout>
</template>
<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  methods: {
    onClick() {
      console.log('CLICK')
    }
  }
})
</script>
