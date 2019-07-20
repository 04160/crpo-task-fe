<template>
  <v-app id="inspire">
    <v-content>
      <v-container fluid fill-height>
        <v-layout justify-center>
          <v-flex xs12 sm10 md6>
            <Toolbar></Toolbar>
            <Card></Card>
              <Footer></Footer>
          </v-flex>
        </v-layout>
      </v-container>
    </v-content>
  </v-app>
</template>

<script>
import Toolbar from './components/Toolbar.vue';
import Footer from './components/Footer.vue';
import Card from './components/Main/Card.vue';

export default {
  name: 'App',
  components: {
    Toolbar,
    Footer,
    Card
  },
  data () {
    return {
      //
    }
  }
}
</script>
