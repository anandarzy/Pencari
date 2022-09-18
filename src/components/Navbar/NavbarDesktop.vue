<template>
  <nav class="navbar-container">
    <div class="navbar-content-container">
      <div class="navbar-content">
        <ul>
          <li>Github</li>
          <li>Linkedin</li>
          <li>Icon</li>
          <li>Pictures</li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "NavbarDesktop",
  props: "listMenus",
  mounted() {},
  methods: {},
};
</script>

<style>
.navbar-container {
  display: block;
}

.navbar-content-container {
  max-width: 800px;
  padding: 12px 24px;
  display: flex;
  justify-content: flex-end;
}
.navbar-content > ul {
  display: flex;
}

.navbar-content > ul > li {
  text-decoration: none;
}
.navbar-content > ul {
  display: flex;
}

@media screen and (max-width: 600px) {
  .navbar-container {
    display: hidden;
  }
}
</style>
