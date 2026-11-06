<script setup lang="ts">
import { useSiteConfig, useValaxyI18n } from 'valaxy'

const siteConfig = useSiteConfig()
const { $t } = useValaxyI18n()
</script>

<template>
  <a
    class="site-author-name font-black font-serif text-$va-c-text op-80 hover:op-100 flex-center"
    href="https://saikai.moe/"
    target="_blank"
  >
    {{ $t(siteConfig.author.name) }}
</a>
</template>
