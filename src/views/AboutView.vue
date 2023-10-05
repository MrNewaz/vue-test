<template>
  <main>
    <h1>About Todos App</h1>

    <ul class="todo-list">
      Vue is a framework and ecosystem that covers most of the common features
      needed in frontend development. But the web is extremely diverse - the
      things we build on the web may vary drastically in form and scale. With
      that in mind, Vue is designed to be flexible and incrementally adoptable.
      Depending on your use case, Vue can be used in different ways:
      <li>Enhancing static HTML without a build step</li>
      <li>Embedding as Web Components on any page</li>
      <li>Single-Page Application (SPA)</li>
      <li>Fullstack / Server-Side Rendering (SSR)</li>
      <li>Jamstack / Static Site Generation (SSG)</li>
      <li>Targeting desktop, mobile, WebGL, and even the terminal</li>
      If you find these concepts intimidating, don't worry! The tutorial and
      guide only require basic HTML and JavaScript knowledge, and you should be
      able to follow along without being an expert in any of these.
    </ul>
  </main>
</template>

<style lang="scss" scoped>
main {
  display: flex;
  flex-direction: column;
  max-width: 700px;
  width: 100%;
  margin: 0 auto;
  padding: 40px 16px;

  h1 {
    margin-bottom: 16px;
    text-align: center;
  }

  .todo-list {
    display: flex;
    flex-direction: column;
    margin-top: 24px;
    gap: 20px;
    text-align: justify;
    list-style-position: inside;
  }
}
</style>
