<template>
  <!-- Display component here as per the url -->
  <Navbar></Navbar>
  <div>
    <router-view :key="$route.fullPath"></router-view>
  </div>  
  
</template>

<script>
import Navbar from "@/components/Navbar";
export default {
  name: 'App',
  components: {Navbar}
}
</script>

<style>

</style>
