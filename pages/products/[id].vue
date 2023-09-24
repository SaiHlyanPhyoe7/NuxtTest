<template>
  <div>
    <p>Products detials for {{ id }}</p>
    <p>
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quisquam
      asperiores qui aut debitis sit voluptates ipsam labore, itaque quibusdam?
      Veritatis placeat, quaerat labore non molestias rerum qui enim atque
      possimus!
    </p>
  </div>
</template>

<script setup>
const { id } = useRoute().params;
</script>

<style scoped></style>
