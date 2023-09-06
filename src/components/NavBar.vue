<template>
  <VAppBar app color="black" dark flat class="px-12">
    <VCol>
      <VBtn
        ><VIcon color="yellow" left class="mr-2">fa-solid fa-code</VIcon>
        SANTANA</VBtn
      >
    </VCol>
    <VCol>
      <VBtn text right @click="scroll('home')" class="text-yellow">Home</VBtn>
      <VBtn text right @click="scroll('about')">Sobre</VBtn>
      <VBtn text right @click="scroll('experience')">Experiência</VBtn>
      <VBtn text right @click="scroll('education')">Educação</VBtn>
      <VBtn text right @click="scroll('contact')">Contato</VBtn>
    </VCol>
  </VAppBar>
</template>

<script>
export default {
  name: "NavBar",
  methods: {
    scroll(refName) {
      const element = document.getElementById(refName);
      element.scrollIntoView({ behavior: smooth });
    },
  },
};
</script>
