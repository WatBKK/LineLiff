<template>
  <div class="container">
    <div class="row">
      <div class="cols">
        <h1>THIS MY LIFF</h1>
      </div>
    </div>
    <div class="row">
      <div class="cols">
        <img src="~/static/user.png" alt="" class="userImage" />
      </div>
    </div>
    <div class="row">
      <div class="cols loginUser">
        <input type="text" class="login" placeholder="username" />
        <input type="password" class="login" placeholder="password" />
      </div>
    </div>
    <div class="row">
      <div class="cols">
        <button class="login-btn">Login</button>
      </div>
    </div>
    <div class="row">
      <div class="cols">
        <p>or</p>
      </div>
    </div>
    <div class="row">
      <div class="cols">
        <button class="register-btn">Register</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.row {
  display: flex;
  justify-content: center;
  width: 100%;
  margin: 20px 10px;
}
.cols {
  display: flex;
  justify-content: center;
  width: 100%;
}
.userImage {
  width: 150px;
  height: 150px;
}
.loginUser {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
.login {
  margin-top: 4px;
  width: 75%;
  font-size: 12px;
  padding: 8px;
  /* border-radius: 5px; */
}
.login-btn {
  background-color: rgb(95, 144, 247);
  color: white;
  border-radius: 25px;
  width: 75%;
  padding: 8px;
  border: none;
}
.register-btn {
  background-color: rgb(87, 190, 55);
  color: white;
  border-radius: 25px;
  width: 75%;
  padding: 8px;
  border: none;
}
</style>
