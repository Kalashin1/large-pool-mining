<script>
	import Nav from '../components/Nav.svelte';
	import Footer from '../components/Footer.svelte';
	// import Spinner from '../components/Spinner.svelte';
	import BackToTop from '../components/Back-To-Top.svelte';
	export let segment;
</script>


<main>
	<Nav {segment}/>
	<slot></slot>
	<Footer />
	<BackToTop />
</main>