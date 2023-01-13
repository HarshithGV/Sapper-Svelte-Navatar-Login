<script>
	import Nav from '../components/Nav.svelte';

	export let segment;
</script>


	

<Nav {segment}/>

<main class="form-signin w-100 m-auto">
	<slot></slot>
</main>