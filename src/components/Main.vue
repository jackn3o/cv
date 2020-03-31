<template>
  <v-container fill-height fluid>
    <v-row justify="center" fill-height no-gutters>
      <v-col col="12" xl="6" md="9" xs="12">
        <v-card
          style="overflow:hidden; border-radius:32px 0 32px 32px; max-height: 720px; height:100%; min-height: 600px;"
        >
          <v-row no-gutters fill-height>
            <v-col cols="3">
              <v-card height="100%" color="red" outlined></v-card>
            </v-col>
            <v-col cols="9">
              <v-card tile>222</v-card>
            </v-col>
          </v-row>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "Main",

  data: () => ({})
};
</script>

