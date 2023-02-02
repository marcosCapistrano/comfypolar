<script>
	const comments = [
		{
			author: 'Bells Fargo',
			timestamp: new Date(),
			content: 'Conheço amigos que possuem o produto e recomendam, vou aproveitar a promoção!'
		},
        {
			author: 'Rafael Carvalho',
			timestamp: new Date(),
			content: 'O produto é ótimo, não me arrependo'
		}
	];
</script>

<section class="wrapper">
	<h2>Comentários dos leitores (2)</h2>

	{#each comments as comment}
		<div class="comment">
			<div class="header">
				<span class="author">{comment.author}</span>
				<span class="timestamp">há 3 horas</span>
			</div>
			<div class="content">
				<p>{comment.content}</p>
			</div>
			<div class="footer">
				<div class="icon-btn">
					<i class="fa-solid fa-thumbs-up" />
					<span>Curtir</span>
				</div>

				<div class="icon-btn">
					<i class="fa-solid fa-reply" />
					<span>Responder</span>
				</div>
			</div>
		</div>
	{/each}
</section>

<style lang="scss">
    section {
        margin: 4rem auto;
    }
    .comment {
        margin: 2rem 0;
    }
	.header {
		display: inline-flex;
		align-items: baseline;
		gap: 10px;
		margin-bottom: 10px;

		.author {
			font-weight: bold;
		}

		.timestamp {
			font-size: 0.75em;
		}
	}

	.footer {
		display: inline-flex;
		gap: 16px;
		margin-top: 20px;
		.icon-btn {
			display: inline-flex;
			gap: 6px;
		}
	}
</style>
