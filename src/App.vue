
<template>
  <mdb-container id = "app">
    <mdb-row>
      <mdb-col col="sm"><navbar/></mdb-col>      
    </mdb-row>
    <mdb-row>
      <mdb-col col="sm"><router-view/></mdb-col>      
    </mdb-row>
  </mdb-container>
</template>

<script>
// import Navbar from './components/Navbar.vue'
import Navbar from '@/components/Navbar';
import {mdbContainer, mdbRow, mdbCol} from 'mdbvue';

export default {
  // components: { Navbar },
  name: 'App',
   components: {
      Navbar,
      mdbContainer,
      mdbRow,
      mdbCol,
       
    }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Roboto:300,400,500,700&display=swap');
</style>
