<script setup>
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
    <template #heading>Pengalaman kerja</template>

    Web Developer i'm a passionate developer in HTML,CSS,and JavaScript
    <a href="https://vuejs.org/" target="_blank" rel="noopener"></a>
    provides you with all information you need to get started.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Kemampuan</template>

    
    <a href="https://vitejs.dev/guide/features.html" target="_blank" rel="noopener"></a>* HTML, CSS, javaScript
    <a href="https://code.visualstudio.com/" target="_blank" rel="noopener"></a>* Node.js, Express.js
    <a href="https://github.com/johnsoncodehk/volar" target="_blank" rel="noopener"></a>
    <a href="https://www.cypress.io/" target="_blank" rel="noopener"></a>*React, Vue.js
    <a href="https://on.cypress.io/component" target="_blank" rel="noopener"
      ></a
    >

    <br />

     <code></code>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Pendidikan</template>

    Universitas Islam Riau
    <a href="https://pinia.vuejs.org/" target="_blank" rel="noopener"></a>
    <a href="https://router.vuejs.org/" target="_blank" rel="noopener"></a>
    <a href="https://test-utils.vuejs.org/" target="_blank" rel="noopener"></a>
    <a href="https://github.com/vuejs/devtools" target="_blank" rel="noopener"></a> Teknik Informatika (2022)
    <a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener"></a>
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Kontak</template>

    Email:melisasahira30@gmail.com
    <a href="https://chat.vuejs.org" target="_blank" rel="noopener"></a>
    <a href="https://stackoverflow.com/questions/tagged/vue.js" target="_blank" rel="noopener"
      ></a
    >
    <a href="https://news.vuejs.org" target="_blank" rel="noopener"></a> 
    <a href="https://twitter.com/vuejs" target="_blank" rel="noopener"></a>
    Telepon: +628 13 3456 890
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Skills</template>

    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener"></a> HTML,CSS,JavaScript
  </WelcomeItem>
</template>
