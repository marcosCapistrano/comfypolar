<script>
	// @ts-nocheck

	export let img;
	export let review;
	export let name;
</script>

<div class="customer-review">
	<img src={img} alt="cliente" />
	<span class="product__rating">
		<i>★</i><i>★</i><i>★</i><i>★</i><i>★</i>
	</span>

	<p class="review">{review}</p>

	<p class="customer-name">{name}</p>
</div>

<style lang="scss">
	.customer-review {
		background-color: #f4f4f4;
		padding: 1rem;
        margin: 2em;

		img {
			width: 50%;
			margin: 0 auto;
			display: block;
		}

		.product__rating {
			display: block;
			font-size: var(--step-3);
			margin: 0.75em auto 0.75em auto;
			color: #fc0;
			text-shadow: #fc0 0 0 20px;
			width: fit-content;
		}

		.review {
			line-height: 1.25;
			margin-bottom: 1em;
		}

		.customer-name {
			text-align: center;
			font-size: var(--step-1);
			font-weight: bold;
		}
	}
</style>
