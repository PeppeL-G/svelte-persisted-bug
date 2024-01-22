<script>
	
	import { persisted } from 'svelte-persisted-store'
	
	const store1 = persisted(`store`, 1)
	
</script>

<h1>Page 1</h1>

<p>store1: {$store1} </p>

<button on:click={() => $store1 += 1}>Inc</button>

<a href="/page-2">To Page 2</a>