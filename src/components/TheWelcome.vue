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
      <!-- <DocumentationIcon /> -->
      <img alt="Vue logo" class="logo" src="@/assets/icons8-instagram-old.gif" width="125" height="125" />
    </template>
    <template #heading>Instagram</template>

    Visit my official instagram 
    <a target="_blank" href="https://www.instagram.com">@bella&mishka</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <img alt="Vue logo" class="logo" src="@/assets/icons8-youtube.gif" width="125" height="125" />
    </template>
    <template #heading>Youtube</template>
Visit my official Youtube channel 
    <a target="_blank" href="https://www.youtube.com">@bella&mishka</a>
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <img alt="Vue logo" class="logo" src="@/assets/icons8-tiktok.gif" width="125" height="125" />
    </template>
    <template #heading>TikTok</template>

    Visit my official tiktok 
    <a target="_blank" href="https://www.tiktok.com">@bella&mishka</a>
  </WelcomeItem>

  <!-- <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Community</template>

    Got stuck? Ask your question on
    <a target="_blank" href="https://chat.vuejs.org">Vue Land</a>, our official Discord server, or
    <a target="_blank" href="https://stackoverflow.com/questions/tagged/vue.js">StackOverflow</a>.
    You should also subscribe to
    <a target="_blank" href="https://news.vuejs.org">our mailing list</a> and follow the official
    <a target="_blank" href="https://twitter.com/vuejs">@vuejs</a>
    twitter account for latest news in the Vue world.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Support Vue</template>

    As an independent project, Vue relies on community backing for its sustainability. You can help
    us by
    <a target="_blank" href="https://vuejs.org/sponsor/">becoming a sponsor</a>.
  </WelcomeItem> -->
</template>
