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
    <template #heading>Video</template>

    Allo voici une vidéo
    <a href="https://www.youtube.com/watch?v=nvB9chNNl2s" target="_blank" rel="noopener"><img class="displayed" src="@/assets/LOGO.png" alt="LOGO" /></a>
    que j'adore
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Lien Google</template>

    Voici un lien pour ouvrir Google
    <a href="https://google.com" target="_blank" rel="noopener"><img class="displayed" src="@/assets/google.png" alt="google" /></a>

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>crayons de couleur</template>

    Tape la mouche !!!
    <a href="https://poki.com/en/g/flyordie-io#" target="_blank" rel="noopener"><img class="image" src="@/assets/mouche.png" alt="mouche" /></a>,
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Voici mon école : </template>

    L'école St-Gérard
    <a href="https://st-gerard.cssdm.gouv.qc.ca/" target="_blank" rel="noopener"><img class="displayed" src="@/assets/csdm.png" alt="ecole" /></a>
  
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