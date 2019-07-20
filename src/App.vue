<template>
  <v-app id="inspire">
    <v-content>
      <v-container fluid fill-height>
        <v-layout justify-center>
          <v-flex xs12 sm10 md6>
            <v-card class="elevation-12">
              <Toolbar></Toolbar>
              <v-card-text>
                <v-form>
                  <!-- <v-text-field prepend-icon="person" name="login" label="Login" type="text"></v-text-field>
                  <v-text-field id="password" prepend-icon="lock" name="password" label="Password" type="password"></v-text-field> -->
                </v-form>
              </v-card-text>
              <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn color="primary">Login</v-btn>
              </v-card-actions>
            </v-card>
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

export default {
  name: 'App',
  components: {
    Toolbar,
    Footer
  },
  data () {
    return {
      //
    }
  }
}
</script>
