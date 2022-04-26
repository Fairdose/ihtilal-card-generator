<script>
import Sidebar from "./lib/layout/Sidebar.svelte";
</script>

<div class="app-wrapper">
  <Sidebar />
  <div id="ihtilal-canvas">

  </div>
</div>

<style>
.app-wrapper {
  background: grey;
  width: 100vw;
  height: 100vh;
  position: relative;
}
:global* {
  color: #cecece;
}
</style>
