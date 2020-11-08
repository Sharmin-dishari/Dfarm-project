<template>
  <q-page class="flex flex-center">
    <roundedButton />
  </q-page>
</template>

<script>
export default {
  name: "PageIndex",
  components: {
    roundedButton: () => import("../components/Button"),
  },
};
</script>
