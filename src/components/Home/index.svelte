<script>
    export let title = ''
    export let items = ['']
</script>
<h1 class='px-10 text-red-700'>{title}</h1>

<ul>
	{#each items as item}
		<li>
			{item}
		</li>
	{/each}
</ul>
