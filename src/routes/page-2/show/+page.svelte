<script>
	
	import { persisted } from 'svelte-persisted-store'
	
	const store2 = persisted(`store`, 1)
	
</script>

<p>store2: {$store2} </p>