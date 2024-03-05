<template>
  <div class="home">
   <h1>Home</h1>
   <main-form></main-form>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import MainForm from '@/components/MainForm.vue'

export default defineComponent({
  name: 'HomeView',
  components: {
    'main-form': MainForm
  }
});
</script>
