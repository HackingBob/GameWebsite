<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Snake</template>
    <a href="http://localhost:8080/" target="_blank" rel="noopener"><img class="displayed" src="@/assets/LOGO.png" alt="Snake" /></a>
    What's You're Best Score ?
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Flappy Bird</template>
    <a href="https://poki.com/fr/g/flappy+bird?campaign=14726801186&adgroup=140110604799&extensionid=&targetid=kwd-69646700242&location=9061031&matchtype=e&network=g&device=c&devicemodel=&creative=619956173753&keyword=flappy%20bird&placement=&target=&gclid=CjwKCAjwzuqgBhAcEiwAdj5dRojGhk3H00_tS2pqe7XzZZ0VbwvR1ccvat90xAlJjmPa3ZWW2JNRrxoCzcgQAvD_BwE" target="_blank" rel="noopener"><img class="displayed" src="@/assets/google.png" alt="Flappy Bird" /></a>
    Don't Get Hit By The Pipes !
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>2048</template>
    <a href="https://2048.ninja/" target="_blank" rel="noopener"><img class="image" src="@/assets/mouche.png" alt="2048" /></a>
    Try To Beat The Score Of 131072 !
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Dino Game</template>
    <a href="https://chromedino.com/" target="_blank" rel="noopener"><img class="displayed" src="@/assets/csdm.png" alt="dino" /></a>
    Jump Over All The Cactuses !
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Encore bob</template>

    Click dessus
    <a href="https://raw.githubusercontent.com/gist/patevs/b007a0e98fb216438d4cbf559fac4166/raw/88f20c9d749d756be63f22b09f3c4ac570bc5101/programming.gif" target="_blank" rel="noopener"><img class="image" src="@/assets/allo.gif" alt="allo" /></a>.
  </WelcomeItem>
</template>

<style>
  img {
  width: 20px;
  height: 20px;
}
.image{
  width: 50px;
  height: 50px;
}
  </style>