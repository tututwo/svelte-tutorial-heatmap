<script>
  import Rects from "./components/Rects.svelte"

</script>


<figure>
  <div class = "chart-container">
    <Rects />
  </div>
</figure>


<style>
  figure {
    display: block;
    position: relative;
    width: 100%;
    height: 70vh;
    min-height: 400px;
    margin: 0;
    user-select: none;
  }

  figure > * {
    display: block;
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    overflow: hidden;
  }
</style>