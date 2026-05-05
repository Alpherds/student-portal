<template>
  <v-app id="inspire">
    <v-navigation-drawer v-model="drawer">
        <v-list>
            <v-list-item 
                prepend-icon="mdi-view-dashboard" 
                title="Home" 
                value="home"></v-list-item>
        </v-list>
    </v-navigation-drawer>

  </v-app>
</template>

<script setup>
  import { ref } from 'vue'

  const drawer = ref(null)
</script>

<script>
  export default {
    data: () => ({ drawer: null }),
  }
</script>