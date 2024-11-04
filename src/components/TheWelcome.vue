<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
   <div style="margin-bottom:20px;">
    <SButton color="blue">
      主要按钮
    </SButton>
    <SButton color="green">
      绿色按钮
    </SButton>
    <SButton color="gray">
      灰色按钮
    </SButton>
    <SButton color="yellow">
      黄色按钮
    </SButton>
    <SButton color="red">
      红色按钮
    </SButton>
  </div>
  <div style="margin-bottom:20px;">
    <SButton color="blue" plain>
      朴素按钮
    </SButton>
    <SButton color="green" plain>
      绿色按钮
    </SButton>
    <SButton color="gray" plain>
      灰色按钮
    </SButton>
    <SButton color="yellow" plain>
      黄色按钮
    </SButton>
    <SButton color="red" plain>
      红色按钮
    </SButton>
  </div>
  <div style="margin-bottom:20px;">
    <SButton size="small" plain>
      小按钮
    </SButton>
    <SButton size="medium" plain>
      中按钮
    </SButton>
    <SButton size="large" plain>
      大按钮
    </SButton>
  </div>
  <div style="margin-bottom:20px;">
    <SButton color="blue" plain round icon="search">
      搜索按钮
    </SButton>
    <SButton color="green" round plain icon="edit">
      编辑按钮
    </SButton>
    <SButton color="gray" round plain icon="check">
      成功按钮
    </SButton>
    <SButton color="yellow" round plain icon="message">
      提示按钮
    </SButton>
    <SButton color="red" round plain icon="delete" style="margin-top:20px;">
      删除按钮
    </SButton>
  </div>
  <div style="margin-bottom:20px; ">
    <SButton color="blue" round plain icon="search" />
    <SButton color="green" round plain icon="edit" />
    <SButton color="gray" round plain icon="check" />
    <SButton color="yellow" round plain icon="message" />
    <SButton color="red" round plain icon="delete" />
  </div>
  <!-- <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Documentation</template>

    Vue’s
    <a href="https://vuejs.org/" target="_blank" rel="noopener">official documentation</a>
    provides you with all information you need to get started.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Tooling</template>

    This project is served and bundled with
    <a href="https://vite.dev/guide/features.html" target="_blank" rel="noopener">Vite</a>. The
    recommended IDE setup is
    <a href="https://code.visualstudio.com/" target="_blank" rel="noopener">VSCode</a> +
    <a href="https://github.com/johnsoncodehk/volar" target="_blank" rel="noopener">Volar</a>. If
    you need to test your components and web pages, check out
    <a href="https://www.cypress.io/" target="_blank" rel="noopener">Cypress</a> and
    <a href="https://on.cypress.io/component" target="_blank" rel="noopener"
      >Cypress Component Testing</a
    >.

    <br />

    More instructions are available in <code>README.md</code>.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Ecosystem</template>

    Get official tools and libraries for your project:
    <a href="https://pinia.vuejs.org/" target="_blank" rel="noopener">Pinia</a>,
    <a href="https://router.vuejs.org/" target="_blank" rel="noopener">Vue Router</a>,
    <a href="https://test-utils.vuejs.org/" target="_blank" rel="noopener">Vue Test Utils</a>, and
    <a href="https://github.com/vuejs/devtools" target="_blank" rel="noopener">Vue Dev Tools</a>. If
    you need more resources, we suggest paying
    <a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">Awesome Vue</a>
    a visit.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Community</template>

    Got stuck? Ask your question on
    <a href="https://chat.vuejs.org" target="_blank" rel="noopener">Vue Land</a>, our official
    Discord server, or
    <a href="https://stackoverflow.com/questions/tagged/vue.js" target="_blank" rel="noopener"
      >StackOverflow</a
    >. You should also subscribe to
    <a href="https://news.vuejs.org" target="_blank" rel="noopener">our mailing list</a> and follow
    the official
    <a href="https://twitter.com/vuejs" target="_blank" rel="noopener">@vuejs</a>
    twitter account for latest news in the Vue world.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Support Vue</template>

    As an independent project, Vue relies on community backing for its sustainability. You can help
    us by
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener">becoming a sponsor</a>.
  </WelcomeItem> -->

</template>
