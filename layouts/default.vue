<template>
  <div>
    <header>

    </header>
    <slot />
    <br />
    <footer>
      <NuxtLink>
        <NuxtImg src="/svg/github-original.svg" height="50px" width="50px"/>
      </NuxtLink>
    </footer>
  </div>
</template>

<script lang="ts" setup>
  import '/assets/index.css';
  const img = useImage();
</script>