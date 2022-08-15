<script lang="ts">
    import "../app.css";
	import Home from '../components/Home/index.svelte'
    const items: string[] = ['list1', 'list2', 'list3']
</script>

<Home title={'Hello'} {items}/>


