<template>
  <div class="dashboard">
    <h1 class="subtitle-1 grey--text">Dashboard</h1>
    <v-container class="my-5"
      ><v-card flat outlined class="pa-3">
        <v-layout row wrap class="pa-3">
          <v-flex xs12 md6>
            <div class="caption grey--text">Project Title</div>
            <div>create a new website</div>
          </v-flex>
          <v-flex caption xs6 sm4 md2
            >Person
            <div>Holy Moly</div></v-flex
          >
          <v-flex caption xs6 sm4 md2
            >Due By
            <div>day after tomorrow</div></v-flex
          >
          <v-flex caption xs2 sm4 md2
            >Status
            <div>Ongoing</div></v-flex
          >
        </v-layout>
      </v-card>
    </v-container>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {}
};
</script>
