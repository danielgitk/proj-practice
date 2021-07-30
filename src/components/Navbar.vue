<template>
  <nav>
      <v-app-bar app flat>
   <v-app-bar-nav-icon class="grey--text" @click="drawer = !drawer"></v-app-bar-nav-icon>
      </v-app-bar>
  </nav>
</template>

<script>
export default {
    data(){
        return {
            drawer : false
                    }
    

},
}
</script>

<style>

</style>