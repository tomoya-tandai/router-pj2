<template>
  <div>
    <router-link :to="{name:'Member'}">{{id}}</router-link>
  </div>
</template>

<script>
export default {
  props: ["id"]
};
</script>