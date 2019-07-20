<template>
    <v-card class="elevation-12">
        <v-card-text>
            <Stepper></Stepper>
            <RegisterForm></RegisterForm>
        </v-card-text>
    </v-card>
</template>
<script>
import Stepper from "./Stepper.vue";
import RegisterForm from "./RegisterForm.vue";

export default {
  name: 'Card',
  components: {
    Stepper,
    RegisterForm
  },
  data () {
    return {
      //
    }
  }
}
</script>
