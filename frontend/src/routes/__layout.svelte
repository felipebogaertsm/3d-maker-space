<script context="module">
	// Components:
	import Navbar from '../components/modules/navbar.svelte';

	// Styles:
	import '../app.css';
</script>

<svelte:head>
	<title>3D Maker Space</title>
	<link rel="preconnect" href="https://fonts.googleapis.com" />
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
	<link
		href="https://fonts.googleapis.com/css2?family=Fira+Sans:wght@100;200;300;400;500;600;700;800;900&display=swap"
		rel="stylesheet"
	/>
</svelte:head>

<Navbar />

<slot />
