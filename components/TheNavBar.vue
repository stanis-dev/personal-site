<template>
  <div class="navbar">
    <h2 class="logo">
      <NuxtLink class="link" to="/">Stan.dev</NuxtLink>
    </h2>
    <nav>
      <NuxtLink class="link" to="/">Main</NuxtLink>
      <NuxtLink class="link" to="/posts">Articles</NuxtLink>
    </nav>
  </div>
</template>

<style lang="scss" scoped>
.navbar {
  margin-top: 20px;
  display: flex;
  align-items: center;
  justify-content: space-between;

  nav {
    .link {
      margin-left: 20px;
      font-size: 1.2rem;
      font-weight: 600;
      position: relative;

      &:after {
        content: '';
        background-color: white;
        width: 0;
        height: 3px;
        position: absolute;
        bottom: -10px;
        left: 0;
        transition: all 0.5s ease-in-out;
      }

      &.router-link-active {
        color: rgb(156, 186, 211);

        &:after {
          transition: all 0.2s ease-in-out;
          width: 100%;
        }
      }
    }
  }
}
</style>
