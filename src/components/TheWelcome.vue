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
    <template #heading>BiliBili</template>

    bilibili:
    <a href="https://space.bilibili.com/411569914/?spm_id_from=333.999.0.0" target="_blank" rel="noopener">个人主页</a>
    想获得更多信息请关注我
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Email</template>

    Outlook:
    <a href="e1qasdfttyg@outlook.com <e1qasdfttyg@outlook.com>" target="_blank" rel="noopener">e1qasdfttyg@outlook.com</a>
   

    <br />

  
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>steam</template>

    Steam社区: 
    <a href="https://steamcommunity.com/profiles/76561199106513900" target="_blank" rel="noopener">Steam</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>QQ</template>

    QQ号：
    <a href="" target="_blank" rel="noopener">3316483907</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Support</template>

    As an independent project, Vue relies on community backing for its sustainability. You can help
    us by
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener">becoming a sponsor</a>.
  </WelcomeItem>
</template>
