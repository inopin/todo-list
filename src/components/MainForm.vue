<template>
  <div>
    <label for="task">MainInput</label>
    <input type="text" v-model="taskText" id="task" name="task">
    <button id="addTask">add task</button>
  </div>
</template>

<script lang="ts">
    import { defineComponent } from 'vue';
    export default defineComponent({
        data() {
            return {
                taskText: ''
            }
        }
    })
</script>

<style>

</style>