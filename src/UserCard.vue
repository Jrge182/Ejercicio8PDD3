<template>
  <div class="user-card">
    <div class="user-avatar">
    <img src="https://i.ibb.co/gMGHDnz/imagen-2023-10-13-163835566.png"
  style="width: 50px;
        height: 50px;
        border-radius: 50%;
        background-color: #ddd;
        margin-right: 15px;">

    </div>
    <div class="user-info">
      <h2>{{ userName }}</h2>
      <p>{{ userEmail }}</p>
      <p>{{ userBio }}</p>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    userName: {
      type: String,
      required: true,
    },
    userName2: {
      type: String,
      required: true,
    },
    userEmail: {
      type: String,
      required: true,
    },
    userEmail2: {
      type: String,
      required: true,
    },
    userBio: {
      type: String,
      required: true,
    },
    userBio2: {
      type: String,
      required: true,
    },
  },
};
</script>

<style scoped>
.user-card {
  border: 1px solid #ddd;
  padding: 15px;
  margin: 10px;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  display: flex;
  align-items: center;
}


.user-info {
  flex-grow: 1;
}

.user-info h2 {
  margin: 0;
}

.user-info p {
  margin: 5px 0;
}

.user-info2 {
  flex-grow: 1;
}

.user-info2 h2 {
  margin: 0;
}

.user-info2 p {
  margin: 5px 0;
}
</style>
