<template>
  <nav class="deep-purple darken-2">
    <div class="nav-wrapper container">
      <router-link to="/" class="brand-logo">Tasks</router-link>
      <ul class="right hide-on-med-and-down">
        <router-link
          tag="li"
          to="/"
          exact
          active-class="active"
        >
          <a href="#">Create</a>
        </router-link>
        <router-link
          tag="li"
          to="/list"
          exact
          active-class="active"
        >
          <a href="#">List</a>
        </router-link>
      </ul>
    </div>
  </nav>
</template>