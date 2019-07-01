<script>
  export let controlType;
  export let id;
</script>

<div class="form-control">
  <label for={id}>Description</label>
  {#if controlType === 'textarea'}
    <textarea rows="3" {id} binnd:value={id} />
  {:else}
    <input type="text" {id} binnd:value={id} />
  {/if}
</div>
