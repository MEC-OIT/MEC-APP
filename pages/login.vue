<template id="">
  <section class="hero is-fullheight ">
    <div class="hero-body login_screen_background">
      <div class="container">
        <div class="container has-text-centered">
          <img
            id="mec_logo"
            class="is-3by2"
            src="images/mec_logo.png"
            height="300px"
            width="200px"
            alt="">
        </div>
        <div class="field">
          <p class="control has-icons-left has-icons-right">
            <input
              class="input is-large transparent"
              type="email"
              placeholder="Email Address">
            <span class="icon is-small is-left">
              <i class="fas fa-envelope"/>
            </span>
          </p>
        </div>
        <div class="field ">
          <p class="control has-icons-left">
            <input
              class="input is-large transparent"
              type="password"
              placeholder="Password">
            <span class="icon is-small is-left">
              <i class="fas fa-lock"/>
            </span>
          </p>
        </div>
        <div class="loginContainer">
          <a
            href="dashboard.html"
            class=" loginButton button is-rounded is-large is-fullwidth is-size-5">
            LOGIN
          </a>
        </div>
        <div class="container has-text-centered createAccountContainer ">
          <a
            href="createAccount.html"
            class="createAccount ">
            Create An Account
          </a>
        </div>
      </div>
    </div>
  </section>
</template>

<style media="screen">
.login_screen_background {
  background: url('~assets/mec_library.jpg') no-repeat;
  height: 100%;
  width: 100%;
  background-position: center;
  background-size: cover;
}

#mec_logo {
  position: relative;
  bottom: 10vh;
}

.transparent {
  background: rgba(255, 255, 255, 0.5);
  border: none;
  color: black;
}

.transparent::placeholder {
  color: #171d22;
  font-size: 20px;
}

.fas {
  color: #171d22;
}

.loginButton {
  background-color: $primary;
  border: none;
  outline: none;
  color: white;
}

.createAccount {
  color: $primary;
  padding: 25px;
  position: relative;
}

.createAccountContainer {
  margin: 25px;
}

.loginContainer {
  margin: 25px 0px;
}
</style>
