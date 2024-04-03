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
    <template #heading>Tentang Saya</template>
    Nama saya Radif Fauzi, saat ini saya berkuliah di Universitas Islam Riau jurusan Teknik Informatika. Saya lahir di Tanjung Pinang.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Hobi</template>
    <ul>
      <li>Kerja</li>
      <li>Basket</li>
      <li>Trading</li>
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Cita-Cita</template>
    Cita-cita saya ingin menjadi pengusaha muda dan membantu sesama manusia
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Riwayat Pendidikan</template>
    <ul>
      <li>TK Negri Pembina Pangkalan Kerinci</li>
      <li>SDN 010 Pangkalan Kerinci</li>
      <li>SMP IT At-Taqwa Pangkalan Kerinci</li>
      <li>MAN 1 Pekanbaru</li>
      <li>Universitas Islam Riau</li>
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Social Media</template>
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 418 502" width="2em" height="2em" fill="currentColor">
        <path d="M224.1 141c-63.6 0-114.9 51.3-114.9 114.9s51.3 114.9 114.9 114.9S339 319.5 339 255.9 287.7 141 224.1 141zm0 189.6c-41.1 0-74.7-33.5-74.7-74.7s33.5-74.7 74.7-74.7 74.7 33.5 74.7 74.7-33.6 74.7-74.7 74.7zm146.4-194.3c0 14.9-12 26.8-26.8 26.8-14.9 0-26.8-12-26.8-26.8s12-26.8 26.8-26.8 26.8 12 26.8 26.8zm76.1 27.2c-1.7-35.9-9.9-67.7-36.2-93.9s-58-34.5-93.9-36.2c-37.5-1.8-149.9-1.8-187.4 0-35.9 1.7-67.7 9.9-93.9 36.2s-34.5 58-36.2 93.9c-1.8 37.5-1.8 149.9 0 187.4 1.7 35.9 9.9 67.7 36.2 93.9s58 34.5 93.9 36.2c37.5 1.8 149.9 1.8 187.4 0 35.9-1.7 67.7-9.9 93.9-36.2s34.5-58 36.2-93.9c1.8-37.5 1.8-149.9 0-187.4zM398.8 388c-7.8 19.6-22.9 34.7-42.6 42.6-29.5 11.8-99.5 9-132.1 9s-102.7 2.8-132.1-9c-19.6-7.8-34.7-22.9-42.6-42.6-11.8-29.5-9-99.5-9-132.1s-2.8-102.7 9-132.1c7.8-19.6 22.9-34.7 42.6-42.6 29.5-11.8 99.5-9 132.1-9s102.7-2.8 132.1 9c19.6 7.8 34.7 22.9 42.6 42.6 11.8 29.5 9 99.5 9 132.1s2.8 102.7-9 132.1z"/>
      </svg> Instagram
      <a href="https://www.instagram.com/radhiffzi_/">radhiffzi_</a>
  </WelcomeItem>
</template>
