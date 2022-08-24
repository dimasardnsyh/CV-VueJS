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
    <template #heading>Profil</template>

    Hallo
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Education</template>

    <h4>2020-2023</h4>
    <a href="http://portal.smktarunabhakti.net/login/index.php" target="_blank">SMK TARUNA BHAKTI</a>
    <h4>
      Web Developer
    </h4>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Experience</template>
    <ul>
      <li>Hotel Design</li>
      <li>Food Delivery Design</li>
      <li>Wordpress kartu undangan</li>
      <li>Wordpress kartu undangan</li>
    </ul>
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>language</template>

    <ul>
      <li>English</li>
      <li>Bahasa</li>
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Contact</template>

    <h4>
      No tlp: +6285779654993
    </h4>
    <h4>
      Email:dimasyapemri206@gmail.com
    </h4>
    <h4>
      GitHub: <a href="https://github.com/dimasardnsyh" target="_blank">Click To Show</a>
    </h4>
  </WelcomeItem>
</template>
