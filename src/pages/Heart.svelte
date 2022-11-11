<script lang="ts">
  import Layout from "../lib/Layout.svelte";
  import Heart from "../lib/Heart.svelte";
  import Love from "../lib/Love.svelte";

  const urlParams = new URLSearchParams(window.location.search);
  const name = urlParams.get("loveu");

  console.log("name:", name);
</script>

<!-- class="flex flex-col justify-center items-center" -->
<Layout say={"你是 口中情 眼中喜 心中爱 意中人"}>
  <!-- <div class="text-center">
    <Heart {name} />
  </div> -->
  <Love />
</Layout>
