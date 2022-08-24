<script setup>
import WelcomeItem from './WelcomeItem.vue'
import IconHtml from './icons/IconHtml.vue';
import IconCss from './icons/IconCss.vue';
import IconBootstrap from './icons/IconBootstrap.vue';
import IconFigma from './icons/IconFigma.vue';

</script>

<template>
  <WelcomeItem>
    <template #icon>
      <IconHtml />
    </template>
    <div class="flex">
        <h3>Html</h3>
        <h3>85%</h3>
        </div>
        <progress max="100" value="85"></progress> 
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <IconCss />
    </template>
    <div class="flex">
        <h3>CSS</h3>
        <h3>85%</h3>
        </div>
        <progress max="100" value="85"></progress>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <IconBootstrap />
    </template>
    <div class="flex">
        <h3>Bootstrap</h3>
        <h3>80%</h3>
        </div>
        <progress max="100" value="80"></progress>
    
  </WelcomeItem>
  <WelcomeItem>
    <template #icon>
      <IconFigma />
    </template>
    <div class="flex">
        <h3>Figma</h3>
        <h3>90%</h3>
        </div>
        <progress max="100" value="90"></progress>
    
  </WelcomeItem>
</template>

<style>
.flex{
    display: flex;
    justify-content: space-between;
}

progress[value] {
  width: 100%;
  height: 20px;
}
</style>
