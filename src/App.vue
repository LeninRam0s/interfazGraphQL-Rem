<template>
  <main>
    <px-header/>
    <px-table class="container px-5 sm:px-20 justify-center"/>
  </main>
</template>

<script>
import PxHeader from '@/components/PxHeader';
import PxTable from '@/components/PxTable';


export default {
  name: "App",
  components: {
    PxHeader,
    PxTable
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
