<template>
  <div class="col-md-12">
    <div class="card card-container">
      <form name="form" @submit.prevent="handleRegister">
        <input type="text" name="email">
        <input type="text" name="usermane">
        <input type="password" name="password">
      </form>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Register'
}
</script>

<style>

</style>
