<template>
  <div>
    <ul>
      <li>
        <router-link :to="{name: 'Member', params:{id: 1}}">1へ進む</router-link>
      </li>
      <li>
        <router-link :to="{name: 'Member', params:{id: 2}}">2へ進む</router-link>
      </li>
      <li>
        <router-link :to="{name: 'Member', params:{id: 3}}">2へ進む</router-link>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  
};
</script>

<style scoped>
ul {
  padding: 0px;
}
li {
  list-style: none;
}
</style>
