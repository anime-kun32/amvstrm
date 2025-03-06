<script setup>
useSeoMeta({
  ogTitle: "About",
  ogDescription: "About amvstrm...",
  ogImage: "logo.png",
  ogUrl: "[og:url]",
  twitterTitle: "About",
  twitterDescription: "About amvstrm...",
  twitterImage: "logo.png",
  twitterCard: "summary",
});

useHead({
  htmlAttrs: {
    lang: "en",
  },
  title: "About",
});
</script>
<template>
  <v-container>
    <div class="pa-5" style="background-color: #212121">
      <h1><img src="/logo.png" alt="loho" height="50" /></h1>
      <p>
        yo people , this webiste now belongs to me because i fixed the code my self no one else did it. So yeah it's mine but is still give credit to those who made the website but couldn't be botherd to fix it 
      </p>
      <div class="mt-2">
        <v-btn
          class="mr-2"
          color="grey-darken-1"
          prepend-icon="mdi-github"
          href="https://github.com/amvstrm"
        >
          Github
        </v-btn>
        <v-btn
          color="blue-darken-1"
          prepend-icon="mdi-file-document"
          href="https://amvdocs.pages.dev"
        >
          Documentation
        </v-btn>
      </div>
    </div>
  </v-container>
</template>
