<template>
  <h1>This is a login page</h1>
  <div id="loginMock">
    <span>
      <input placeholder="name" />
    </span>
    <br />
    <span>
      <input placeholder="password" />
    </span>
  </div>
  <button @click="handleClick">go to home page</button>
</template>

<script>
export default {
  methods: {
    handleClick() {
      this.$router.push('/')
    }
  }
}
</script>
