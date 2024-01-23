<script>
	let list = [];
	let item = 'xyz';
</script>

<input type="text" bind:value={item} />

<button on:click={() => list.push(item)}>AddItem</button>
<div>
	{item}
</div>
