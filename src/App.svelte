<script>
  export let name;
</script>

<style lang="scss">
  @import "./myFolder/variables";

  .my-headline {
    color: $blueish;
    box-shadow: 2px 2px 2px 1px rgba(0, 0, 0, 0.2);
  }
</style>

<h1 class="my-headline">Hello {name}!</h1>
