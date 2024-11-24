<script setup lang="ts">
const typebotInitScript = document.createElement("script");
typebotInitScript.type = "module";
typebotInitScript.innerHTML = `import Typebot from 'https://cdn.jsdelivr.net/npm/@typebot.io/js@0.3/dist/web.js'

Typebot.initBubble({
  typebot: "imobiliaria-0nozlkx",
  previewMessage: {
    message: "Bem-vindo!",
    avatarUrl: "https://www.millionray.com/assets/MillionRay-CqRFZ9h_.png",
  },
  theme: { button: { backgroundColor: "#128C7E", size: "large" } },
});
`;
document.body.append(typebotInitScript);
</script>

<template>
</template>

<style scoped></style>
