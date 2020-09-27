<script>
  export let url;
</script>

<style>
  a {
    display: block;
    padding: 20px;
    text-decoration: none;
  }

  div {
    border: 1px solid var(--main-color);
    color: var(--main-color);
    border-radius: 4px;
    margin: 0 30px;
  }

  div:hover {
    background-color: var(--main-color);
    color: black;
  }
</style>

<div>
  <a href={url} target="_blank">
    <slot />
  </a>
</div>
