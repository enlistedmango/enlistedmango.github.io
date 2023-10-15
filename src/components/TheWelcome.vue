<script setup>
import MainContent from './MainContent.vue'
import AboutIcon from './icons/AboutIcon.vue'
import GithubIcon from './icons/GithubIcon.vue'
import CodeIcon from './icons/CodeIcon.vue'
import SocialsIcon from './icons/SocialsIcon.vue'
</script>

<template>
  <MainContent>
    <template #icon>
      <AboutIcon />
    </template>
    <template #heading>About Me</template>
    This is just a simple about me section for right now
  </MainContent>

  <MainContent>
    <template #icon>
      <CodeIcon />
    </template>
    <template #heading>Currently Working On</template>

    This is just some placeholder text for the time being
  </MainContent>

  <MainContent>
    <template #icon>
      <GithubIcon />
    </template>
    <template #heading>Github</template>

    Anything I work on development wise is normally shared over on
    <a href="https://github.com/jmccallum-rbi?tab=repositories" target="_blank" rel="noopener">Github</a>
  </MainContent>



  <MainContent>
    <template #icon>
      <SocialsIcon />
    </template>
    <template #heading>Socials</template>

    <a href="https://twitter.com/enlistedmango" target="_blank" rel="noopener">Twitter</a> ||
    <a href="#" target="_blank" rel="noopener">Discord</a>
  </MainContent>
</template>
