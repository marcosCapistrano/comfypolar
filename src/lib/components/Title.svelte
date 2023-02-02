<script>
	// @ts-nocheck

	export let title;
	export let subtitle;
</script>

<div class="wrapper">
		<h1>{title}</h1>
		<h2>{subtitle}</h2>

	<span class="author">Por Redação G8</span>
	<span class="date">22/01/2023 09h01</span>
	<span class="updated">Atualizado há 1 dia</span>
	<hr />
</div>

<style>
	h1 {
		margin-top: 4rem;
		font-size: var(--step-5);
	}

	h2 {
		font-size: var(--step-2);
		font-weight: 300;
		line-height: 1.4;
		letter-spacing: -0.02em;
		color: #555;
		margin: 1rem 0 2rem 0;
	}

	span.author {
		font-size: var(--step-1);
		letter-spacing: -0.015em;
		line-height: 1.1;
		font-weight: bold;
		color: #555;
		display: block;
		margin-bottom: 0.5em;
	}

	span.date,
	span.updated {
		font-size: var(--step-1);
		letter-spacing: -0.02em;
		color: #555;
	}

	span.updated::before {
		content: '\B7';
		margin-right: 0.2em;
	}

	hr {
		border: 0;
		border-top: 1px solid #ccc;
		margin: 1.5rem 0 3rem 0;
	}
</style>
