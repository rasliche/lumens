<script setup lang="ts">
import type { ButtonProps } from "@nuxt/ui";

const links = ref<ButtonProps[]>([
  {
    label: "Courses",
    to: "/courses",
    icon: "i-lucide-square-play",
  },
//   {
//     label: "Learn more",
//     to: "/docs/getting-started/theme/design-system",
//     color: "neutral",
//     variant: "subtle",
//     trailingIcon: "i-lucide-arrow-right",
//   },
]);
</script>

<template>
  <div>
    <UPageHero
      title="A New Learning Management System"
      description="A Nuxt-based LMS built from the ground up for a quick standup and easy student management."
      headline="Under active development"
      :links="links"
    />
  </div>
</template>
