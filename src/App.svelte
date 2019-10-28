<script>
  export let name;
</script>

<style>
  @value colors from "./colors.css";
  @value myVeryNiceOrange from colors;
  h1 {
    color: myVeryNiceOrange;
    box-shadow: 2px 2px 2px 1px rgba(0, 0, 0, 0.2);
  }
</style>

<h1>Hello {name}!</h1>
