<script lang="ts">
  import Seo from "$lib/components/Seo.svelte";
  import WritingList from "./WritingList.svelte";
  import writing from "./writing.yaml";
</script>

<Seo
  title="Martin Kim – Writing"
  description="Description here."
/>

<section class="layout-md py-12">
  <h2 class="heading2">Papers</h2>
  <WritingList data={writing.notes} />
</section>
