<template>
  <nav class="navbar fixed-top navbar-expand-lg navbar-light navbar-custom">
    <div class="container">
      <a class="navbar-brand" href="/">
        Novem Financial
      </a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item">
            <a class="nav-link" href="/">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/about">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/atm">ATM</a>
          </li>
        </ul>
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link" href="/account">Login</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/account">Register</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script lang="ts">
import Vue from 'vue';
export default {};
</script>
