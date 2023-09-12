<template>
  <v-container id="about">
    <v-row>
      <v-col cols="12">
        <v-card title="SOBRE MIM">
          <v-container>
            <v-row>
              <v-col cols="6" class="d-flex align-center justify-center">
                <v-img
                  left
                  max-height="300px"
                  src="../../src/assets/img/perfil.jpeg"
                >
                </v-img>
              </v-col>
              <v-col cols="6" class="d-flex align-center justify-center">
                <v-card-text>
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
                  do eiusmod tempor incididunt ut labore et dolore magna aliqua.
                  Ut enim ad minim veniam, quis nostrud exercitation ullamco
                  laboris nisi ut aliquip ex ea commodo consequat. Duis aute
                  irure dolor in reprehenderit in voluptate velit esse cillum
                  dolore eu fugiat nulla pariatur. Excepteur sint occaecat
                  cupidatat non proident, sunt in culpa qui officia deserunt
                  mollit anim id est laborum.
                </v-card-text>
              </v-col>
            </v-row>
          </v-container>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "AboutView",
};
</script>
