<script>
	// @ts-nocheck

	import Comments from '$lib/components/Comments.svelte';
	import heroImg from '$lib/assets/heroImg.png';
	import gif1 from '$lib/assets/gif1.gif';
	import img1 from '$lib/assets/img1.png';
	import cliente1 from '$lib/assets/cliente1.png';
	import cliente2 from '$lib/assets/cliente2.png';
	import cliente3 from '$lib/assets/cliente3.png';
	import product from '$lib/assets/product.png';

	import { page } from '$app/stores';
	import CustomerReview from '$lib/components/CustomerReview.svelte';
	import Question from '$lib/components/Question.svelte';

	$: trafficSource = $page.url.search;

	const reviews = [
		{
			img: cliente1,
			review:
				'Inacreditável ! Estes collants permitiram-me conciliar com saias e vestidos no inverno! Eles são muito quentes e a renderização final é muito realista!',
			name: 'Elsa C.'
		},
		{
			img: cliente2,
			review: 'Suavidade, calor e espessura estão lá. A aparência também é muito bonita!',
			name: 'Vitória M.'
		},
		{
			img: cliente3,
			review:
				'É muito quente e tem um efeito de pele nua. (transparente apertado) Coloquei 5 estrelas porque é ótimo!',
			name: 'Anabelle G.'
		}
	];

	const questions = [
		{
			question: 'Essas meias são quentes?',
			answer:
				'Sim, as meias de lã ComfyPolar para mulher são muito quentes graças ao seu forro de lã grossa. Este forro permite manter a temperatura das pernas no inverno, sendo confortável e fácil de calçar.'
		},

		{
			question:
				'Estas meias podem aliviar dores musculares e inchaços causados ​​pela má circulação sanguínea?',
			answer:
				'Sim, as meias de lã femininas ComfyPolar podem ajudar a aliviar a dor muscular e o inchaço causados ​​pela má circulação sanguínea. O forro de lã grosso pode ajudar a manter a temperatura corporal e melhorar a circulação sanguínea.'
		},

		{
			question: 'Essas meias são estilosas?',
			answer:
				'Sim, estes collants são elegantes graças à sua ilusão de collants pretos transparentes de nylon. Você pode usá-los com uma saia ou um vestido para um look chique e feminino no inverno.'
		},

		{
			question: 'Essas meias são fáceis de cuidar?',
			answer:
				'Sim, essas meias são fáceis de cuidar. Basta lavar à mão ou à máquina a 30°C e pendurar para secar. Não deformam nem perdem a elasticidade, mesmo após várias lavagens.'
		},
		{
			question: 'As meias de lã ComfyPolar para mulheres estão disponíveis em tamanhos diferentes?',
			answer:
				'Sim, as meias de lã ComfyPolar para mulheres estão disponíveis em diferentes tamanhos para se adequarem a diferentes tipos de corpo. Você pode verificar nosso guia de tamanhos para encontrar o tamanho que melhor se adapta a você.'
		},
		{
			question: 'Essas meias são justas?',
			answer:
				'Sim, essas meias têm um ajuste confortável para evitar que escorreguem ou caiam enquanto você as usa. No entanto, eles são elásticos o suficiente para proporcionar o máximo de conforto sem serem muito apertados.'
		},
		{
			question: 'Estas meias são adequadas para atividades ao ar livre no inverno?',
			answer:
				'Sim, estes collants são adequados para atividades ao ar livre no inverno graças ao seu forro de lã grossa que o mantém aquecido. Eles podem ser usados ​​sob calças de esqui ou calças impermeáveis ​​para proteção extra contra o frio.'
		},
		{
			question: 'Essas meias são bem ventiladas?',
			answer:
				'Sim, estas meias são bem ventiladas graças ao seu design de malha fina. A lã usada para o forro também é respirável, permitindo que você fique aquecido sem suar. Isso lhe dá o máximo conforto no inverno.'
		}
	];
</script>

<svelte:head>
	<title>G9 Notícias - Collant Polar</title>
</svelte:head>

<figure class="wrapper-big">
	<a href={`http://headache-cap-pro.g8-portalnoticias.com.br/${trafficSource}`}>
		<img src={heroImg} alt="Usuário utilizando o produto Headache Cap Pro" />
	</a>
	<figcaption>Collant Polar ComfyPolar</figcaption>
</figure>

<div class="wrapper">
	<p>
		<strong>
			O inverno chegou e você está procurando uma meia-calça que a mantenha aquecida e elegante?
			Cansado de meias finas que não funcionam e meias grandes que fazem você parecer ter tornozelos
			e pés grandes?
		</strong>
	</p>

	<p>
		Você precisa de algo macio, confortável e quente para acompanhá-la durante toda a estação fria?
		Não quer ter de escolher entre conforto e elegância, e procura uma solução que lhe proporcione
		ambos? Então não procure mais, nós temos a solução para você!
	</p>

	<img src={gif1} alt="demonstração do produto comfypolar" />

	<h2>Por que as meias de lã ComfyPolar são a solução perfeita para o inverno?</h2>
	<p><strong>Combine calor e elegância com as meias de lã ComfyPolar</strong></p>

	<p>
		<strong>As meias de lã ComfyPolar</strong> para mulheres são a solução! Estas meias-<strong
			>calças térmicas</strong
		>
		ultra-coberturas apresentam um <strong>forro grosso de lã</strong>cor de pele de um lado e uma
		impressionante
		<strong
			>ilusão de meia-calça de náilon preto transparente do outro. Então você pode ter o melhor dos
			dois mundos: calor e estilo.</strong
		>
	</p>

	<p>
		Graças ao seu interior grosso, macio e quente , estas meias irão mantê-lo aquecido no inverno.
		Você não terá mais que se preocupar com calafrios e pernas congeladas! E graças às suas
		meias-calças de nylon transparentes ilusão, pode usá-las com uma saia ou um vestido para um look
		elegante, mesmo no tempo frio.
	</p>

	<p>
		Além de serem quentinhas e estilosas, essas meias também são muito duráveis . Graças ao seu
		design rosqueável e muito resistente, você poderá usá-los por anos sem se deteriorar. E graças à
		sua suavidade como um xadrez , você apreciará seu máximo conforto , mesmo em climas frios.
	</p>

	<p>
		<strong
			>Não hesite mais e opte por estes collants para enfrentar o inverno com estilo e conforto.</strong
		>
	</p>

	<img src={img1} alt="três mulhers usando o collant polar" />

	<h2>
		As vantagens das meias de lã ComfyPolar para mulheres: calor, elegância, durabilidade e muito
		mais
	</h2>

	<ul class="checked">
		<li>
			Quente e confortável, a meia- calça de lã para mulher tem um forro de lã grossa que garante o
			calor ideal, mesmo em climas frios. Chega de tremer ou congelar as pernas!
		</li>
		<li>Macio e elástico , tornando-os confortáveis ​​de usar o dia todo.</li>
		<li>
			Leve e economiza espaço , facilitando o transporte e armazenamento quando não estiver em uso.
		</li>
		<li>
			Fáceis de cuidar e não requerem engomar nem lavar a seco, tornando-os práticos para mulheres
			ocupadas.
		</li>
		<li>
			Chique e elegante graças à sua ilusão de meia-calça de nylon preto transparente, que oferece
			um visual sofisticado e feminino. Use-os com uma saia ou um vestido para um estilo chique,
			mesmo no frio.
		</li>
		<li>
			Durável graças ao seu design antiderrapante e resistente, essas meias podem ser usadas por
			anos sem perder sua elasticidade ou qualidade.
		</li>
		<li>
			Confortáveis, a sua suavidade como um xadrez vão oferecer-lhe o máximo conforto, mesmo nos
			dias mais frios do inverno. Você nunca mais vai querer tirá-los!
		</li>
		<li>
			Protege as pernas, tornando-as ideais para mulheres que sofrem de problemas de circulação
			sanguínea ou má circulação, ou propensas a queimaduras no inverno.
		</li>
		<li>
			Disponível em uma variedade de tamanhos , permitindo que as mulheres escolham o estilo e
			ajuste que melhor lhes convier.
		</li>
	</ul>

	<a href="" class="btn btn-featured">CLIQUE AQUI PARA VERIFICAR DISPONIBILIDADE E PREÇO</a>

	<br />
	<br />

	<hr />
	<div class="centered">
		<h4>99% das mulheres que experimentaram o ComfyPolar recomendam-no aos seus entes queridos!</h4>
		<span class="quote"><strong>"Suavidade, calor e espessura estão ai!"</strong></span>
		<span class="italic">escreve Victoria M. nos comentários</span>
	</div>
	<hr />

	<div class="customer-reviews">
		{#each reviews as review}
			<CustomerReview img={review.img} review={review.review} name={review.name} />
		{/each}
	</div>

	<a href="" class="btn btn-featured">CLIQUE AQUI PARA VERIFICAR DISPONIBILIDADE E PREÇO</a>

	<br />
	<h2>Atualização</h2>
	<p>
		ComfyPolar está atualmente em promoção, você pode encomendá-lo à um desconto de 50% e a entrega
		é GRÁTIS.
	</p>
	<p>
		O estoque pode ser incerto (eles são tão populares). Clique no botão abaixo para verificar o
		estoque e garantir sua oferta de 50% de desconto .
	</p>
	<h2>Onde conseguir essas meias de lã ComfyPolar?</h2>
	<p>Você pode encontrá-lo diretamente no site oficial <a href="">clicando aqui</a></p>
	<p>
		<strong>PS:</strong> Além disso, ComfyPolar é protegido por uma garantia de reembolso de 30 dias.
		Tudo o que você precisa fazer é enviar um e-mail para eles e será reembolsado.
	</p>

	<a href="" class="btn btn-featured">CLIQUE AQUI PARA VERIFICAR DISPONIBILIDADE E PREÇO</a>
	<br />

	<h2>Perguntas frequentes:</h2>
	{#each questions as question}
		<Question question={question.question} answer={question.answer} />
	{/each}

	<a href="" class="btn btn-featured">CLIQUE AQUI PARA VERIFICAR DISPONIBILIDADE E PREÇO</a>
	<br />

	<div class="product">
		<a href={``}>
			<div class="product__container">
				<div class="product__image">
					<img src={product} alt="Imagem e link do produto com desconto" />
				</div>
				<div class="product__details">
					<span class="product__title">Comfy Polar</span>
					<p>Enfrente o Inverno com Estilo</p>

					<span class="product__subtitle">
						<span class="product__rating">
							<i>★</i><i>★</i><i>★</i><i>★</i><i>★</i>
						</span>
						(857) avaliações
					</span>

					<a class="btn btn__featured" href={``}>Aplicar Desconto</a>
					<a class="btn" href={``}>Saiba Mais</a>
				</div>
			</div>
		</a>
	</div>

	<hr />
</div>

<Comments />

<style lang="scss">
	img {
		width: 100%;
	}
	figure {
		margin-bottom: 2rem;
		img {
			width: 100%;
		}

		figcaption {
			margin-top: 1rem;
			font-size: var(--step-0);
			line-height: 1em;
			color: #555;
		}
	}

	p {
		font-size: var(--step-1);
		letter-spacing: -0.025em;
		line-height: 1.5;
		margin-bottom: 1.5em;
		color: #333;

		strong {
			font-weight: bold;
		}

		.italic {
			font-style: italic;
		}
	}

	span {
		&.quote {
			display: block;
			font-weight: bold;
			font-size: var(--step-1);
		}

		&.italic {
			display: block;
			font-style: italic;
			margin-top: 0.35em;
		}
	}

	h2 {
		margin-bottom: 1em;
		margin-top: 1em;
	}

	a {
		font-weight: bold;
		color: $primaryColor;
	}

	a.btn {
		display: block;
		width: fit-content;
		background-color: white;
		border: 1px solid $primaryColor;
		margin: 0 auto;
	}

	a.btn__featured {
		color: #fff;
		background-color: $primaryColor;
		font-size: var(--step-2);
	}

	blockquote {
		font-size: var(--step-4);
		letter-spacing: -0.035em;
		line-height: 1.5;
		font-weight: 500;
		text-align: left;
		padding-left: 1em;

		border-left: 4px solid $primaryColor;
		margin-top: 1.5em;
		margin-bottom: 1.5em;
	}

	h3 {
		color: #111;
		letter-spacing: -0.035em;
		line-height: 1.5;
		font-weight: bold;
		font-size: var(--step-5);
		margin-top: 1.5em;
		margin-bottom: 0.5em;
	}

	.centered {
		padding: 1em;
		text-align: center;
	}

	.centered + hr {
		margin-bottom: 2rem;
	}

	h4 {
		font-weight: bold;
		font-size: var(--step-2);
		margin-bottom: 1em;
	}

	ul.checked {
		li {
			margin-top: 1em;
		}

		li::before {
			content: '✅ ';
		}
	}

	ul.featured {
		li {
			font-size: 1.15rem;
			line-height: 1.25;
		}
	}

	ul {
		margin-bottom: 1.5em;
		li {
			font-size: 1rem;
			line-height: 1.15;
			::before {
				content: '\B7';
				padding-right: 1.25em;
				font-size: 1.5rem;
				color: black;
			}
		}
	}

	.product {
		margin-bottom: 4rem;
		.product__container {
			border: 1px solid black;
			border-radius: 2em;
			padding: 1em;
			display: flex;
			flex-wrap: wrap;
			justify-content: center;
			align-items: center;
			cursor: pointer;

			img {
				width: 70%;
				margin: 0 auto;
				display: block;
			}

			.product__image {
				// flex-basis: 35%;
				max-width: 320px;
			}

			.product__details {
				display: flex;
				flex-direction: column;
				align-items: center;
				justify-content: space-between;
				margin-bottom: 1em;
				.product__title {
					font-size: var(--step-4);
					font-weight: bold;
				}

				.product__subtitle {
					font-size: var(--step-2);
					margin-top: 0.25em;
					.product__rating {
						color: #fc0;
						text-shadow: #fc0 0 0 20px;
					}
				}

				a {
					margin-top: 2rem;
				}
			}
		}
	}

	@media only screen and (min-width: 35rem) {
		.customer-reviews {
			display: flex;
		}
	}
</style>
