<script>
  export let controlType;
  export let id;
</script>

<div class="form-control">
  <label for={id}>Description</label>
  {#if controlType === 'textarea'}
    <textarea rows="3" {id} binnd:value={description} />
  {:else}
    <input type="text" {id} binnd:value={title} />
  {/if}
</div>
