<script>
	import '../scss/styles.scss';
	import Nav from './Nav.svelte';
	import Title from '$lib/components/Title.svelte';
	import Footer from './Footer.svelte';
</script>

<header>
	<Nav />
	<Title
		title="Afaste o frio com os collants polares mais quentes do mercado"
		subtitle="Conheça o collant que está fazendo sucesso entre as mulheres"
	/>
</header>

<main>
	<slot />
</main>

<Footer />

<style>
</style>
