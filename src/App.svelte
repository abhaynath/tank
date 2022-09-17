<script lang="ts">
  import svelteLogo from "@assets/svelte.svg";
  import Test from "@components/Test.svelte";
</script>

<div>
  <img src={svelteLogo} alt="logo" />
  <h1>Tank</h1>
  <Test />
</div>

<style>
  h1 {
    color: green;
  }
</style>
