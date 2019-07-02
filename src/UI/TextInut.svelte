<script>
  export let controlType;
  export let id;
  export let label;
  export let rows;
</script>

<div class="form-control">
  <label for={id}>{label}</label>
  {#if controlType === 'textarea'}
    <textarea {rows} {id} bind:value={id} />
  {:else}
    <input type="text" {id} bind:value={id} />
  {/if}
</div>
