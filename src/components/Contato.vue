<template>
  <v-card>
    <v-layout>
      <v-navigation-drawer
        expand-on-hover
        rail
        floating
        color="amber-lighten-5"
      >
        <v-list>
          <v-list-item
            prepend-avatar="https://randomuser.me/api/portraits/women/85.jpg"
            :title="nome"
          ></v-list-item>
        </v-list>

        <v-divider></v-divider>

        <v-list density="compact" nav>
          <v-list-item
            @click="copiaTexto(email)"
            prepend-icon="fa fa-envelope"
            :title="email"
            id="email"
          ></v-list-item>
          <v-list-item
            @click="copiaTexto(telefone)"
            prepend-icon="fa fa-phone"
            :title="telefone"
            id="telefone"
          ></v-list-item>
          <v-list-item
            prepend-icon="mdi-star"
            title="Starred"
            value="starred"
          ></v-list-item>
        </v-list>
      </v-navigation-drawer>

      <v-main style="height: 250px"></v-main>
    </v-layout>
  </v-card>
</template>

<script>
export default {
  name: "ContatoView",
  data() {
    return {
      nome: "João Victor Santana",
      email: "j.v.f.f.s22@gmail.com",
      telefone: "+5579999970116",
    };
  },
  methods: {
    copiaTelefone() {
      this.copiaTexto(this.telefone);
    },
    copiaTexto(texto) {
      // Copia o texto para a área de transferência
      navigator.clipboard
        .writeText(texto)
        .then(function () {
          // Exibe uma mensagem de confirmação
          alert("Texto copiado para a área de transferência: " + texto);
        })
        .catch(function (err) {
          console.error("Erro ao copiar texto: ", err);
        });
    },
  },
};
</script>

<style scoped></style>
