<template>
  <div class="home">
    <b-card>
      <b-card-header>
        <b-card-title>Tales Monteiro Melquiades</b-card-title>
      </b-card-header>
      <b-card-body>
        Olá mundo!;
      </b-card-body>
    </b-card>
  </div>
</template>

<script>
// @ is an alias to /src
import {BCard, BCardBody, BCardHeader, BCardTitle} from "bootstrap-vue-3";

export default {
  name: 'HomeView',
  components: {
    BCardTitle,
    BCardHeader,
    BCardBody,
    BCard,
  }
}
</script>
