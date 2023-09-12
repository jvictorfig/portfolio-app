<template>
  <v-container id="education">
    <v-row>
      <v-col cols="12">
        <v-card title="EDUCAÇÃO">
          <v-container>
            <v-card-item
              title="Universidade Federal de Sergipe"
              subtitle="jul-2017 atual"
            >
              <v-row>
                <v-col cols="6" class="d-flex align-center justify-center">
                  <v-img
                    left
                    max-height="200px"
                    src="../../src/assets/img/ufs.png"
                  >
                  </v-img>
                </v-col>
                <v-col cols="6" class="d-flex align-center justify-center">
                  <v-card-text>
                    <p>
                      Na <strong>UFS</strong>, faço
                      <strong>Ciência da Computação (9º)</strong>. O curso
                      encontra-se trancado por razões pessoais.
                    </p>
                  </v-card-text>
                </v-col>
              </v-row>
            </v-card-item>
            <v-card-item title="Cruzeiro do Sul" subtitle="fev-2023 atual">
              <v-row>
                <v-col cols="6" class="d-flex align-center justify-center">
                  <v-img
                    left
                    max-height="200px"
                    max-width="400px"
                    src="../../src/assets/img/cruzeiro.png"
                  >
                  </v-img>
                </v-col>
                <v-col cols="6" class="d-flex align-center justify-center">
                  <v-card-text>
                    <p>
                      Cursando
                      <strong
                        >Anállise e desenvolvimento de sistemas (2º)</strong
                      >
                      com previsão de término em 2023.
                    </p>
                  </v-card-text>
                </v-col>
              </v-row>
            </v-card-item>
          </v-container>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "EducationView",
};
</script>

<style></style>
