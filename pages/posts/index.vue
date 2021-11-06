<script setup lang="ts"></script>

<template>
  <div>
    <h1>Articles</h1>

    <section class="articles">
      <article>
        <h3>
          <NuxtLink to="/posts/sample">
            How to make commits and dispatches type safe in Vuex 4 w/ Vue 3
          </NuxtLink>
        </h3>

        <pre>Wedensday, July 7th</pre>

        <summary>
          Now that we know how to initiate our store with types modules, it's
          time to make those commits and dispatches type safe
          <br />
          <!--  <CodeSnippet src="https://carbon.now.sh/embed/R5Hl16iWrRFEA9ugevrz" /> -->
        </summary>
      </article>
    </section>
  </div>
</template>

<style lang="scss" scoped>
.articles {
  text-align: start;

  h3 {
    a {
      text-decoration: underline;
    }
  }
}
</style>
