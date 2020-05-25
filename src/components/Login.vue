<template>
  <form name="form" class="form-signin mb-2" @submit.prevent="handleLogin">
    <div class="text-center mb-4">
      <img class="mb-4" src="/docs/4.4/assets/brand/bootstrap-solid.svg" alt="" width="72" height="72">
      <h1 class="h3 mb-3 font-weight-normal">Login</h1>
      <p>Please login to your account</p>
    </div>
    <div class="form-group">
      <label for="username">Username</label>
      <input type="text" name="usermane" class="form-control">
    </div>
    <div class="form-group">
      <label for="password">Password</label>
      <input type="password" name="password" class="form-control">
    </div>
    <div class="checkbox mb-3">
      <label>
        <input type="checkbox" value="remember-me"> Remember me
      </label>
    </div>
    <button class="btn btn-primary">Login</button>
  </form>
</template>

<script>
export default {
  name: 'Login'
}
</script>

<style scoped>
  form {
    width: 300px;
  }

</style>
