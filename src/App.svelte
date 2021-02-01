<main>
  <h1>Hello Svelte!</h1>
</main>

<style lang="scss">
  :global(*) {
    box-sizing: border-box;
  }

  :global(body) {
    padding: 0;
    margin: 0;
  }

  
  :global(h1, h2, h3, h4, h5) {
    font-family: "Montserrat", sans-serif;
  }

  :global(p, span, div, ul, li) {
    font-family: "Roboto", sans-serif;
  }

  main {
    height: 100%;
    padding: 0;
    overflow: hidden;
  }
</style>
