<script setup lang="ts">
import { useHead } from '@vueuse/head';

useHead({ title: 'privacyPolicy' });
</script>

<template>
  <c-markdown :markdown="$t('privacyPolicy.content')" mx-auto mt-50px max-w-600px />
</template>
