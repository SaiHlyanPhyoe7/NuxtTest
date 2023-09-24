<template>
  <div>
    Index Product
    <ul>
      <li>
        <NuxtLink to="/">ProductHome</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/about">ProductAbout</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/products/haha">ProductProductd</NuxtLink>
      </li>
    </ul>
  </div>

  <div>
    <slot />
  </div>
</template>

<script setup></script>

<style scoped>
.router-link-exact-active {
  color: #12b488;
}
</style>
