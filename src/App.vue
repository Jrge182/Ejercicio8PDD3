<template>
  <div id="app">
    <UserCard
      userName="Jorge Enrique"
      userEmail="jorgee@example.com"
      userBio="Ing. En Sistemas De Información"
    />
  </div>

  <div id="app2">
    <UserCard
      userName="Jorge Enrique 2"
      userEmail="jorgee2@example.com"
      userBio="Ing. En Sistemas De Información"
    />
  </div>
</template>

<script>
import UserCard from "./UserCard.vue";


export default {
  components: {
    UserCard,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #000;
  margin-top: 60px;
}
</style>
