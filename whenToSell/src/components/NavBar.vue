<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="secondary">
      <b-navbar-brand href="/">SEK</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item href="/" style="color: white;">Home</b-nav-item>
        </b-navbar-nav>

        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-nav-item-dropdown style="color: white;" right>
            <!-- Using 'button-content' slot -->
            <template #button-content>
              <em>Account</em>
            </template>
            <b-dropdown-item href="my-page">My Page</b-dropdown-item>
            <b-dropdown-item href="login">Login</b-dropdown-item>
            <b-dropdown-item href="sign-up">Sign Up</b-dropdown-item>
            <b-dropdown-item href="logout">Logout</b-dropdown-item>
          </b-nav-item-dropdown>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>



