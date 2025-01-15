<script>
  import Test from './Test.svelte'
  let props = $props();
</script>

<style>
  div{
    background-color : black;
    padding-left : 5px;
    padding-right : 5px;
    padding-bottom : 0px;
    padding-top : 0px;
  }

  h1{
    color : white;
  }
</style>

<div>
  <h1>{props.title}</h1>
</div>
