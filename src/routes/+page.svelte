<script>
	import Comments from '$lib/components/Comments.svelte';
	import heroImg from '$lib/assets/heroImg.png';
	import gif1 from '$lib/assets/gif1.gif';
	import img1 from '$lib/assets/img1.png';
	import product from '$lib/assets/produto.jpg';

	import { page } from '$app/stores';

	$: trafficSource = $page.url.search;
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

	<!-- <p>
		Tudo começou quando especialistas norte-americanos buscaram alguma solução para reduzir a taxa
		de pessoas com crise de dores de cabeça, a <a
			href={`http://headache-cap-pro.g8-portalnoticias.com.br/${trafficSource}`}>Headache Cap Pro</a
		> chegou surpreendendo usuários, fisioterapeutas, traumatologistas e outros profissionais do ramo.
	</p>

	<h3>Quem usa aprova</h3>
	<p>
		Entre as milhares de pessoas que já usaram e aprovaram a <a
			href={`http://headache-cap-pro.g8-portalnoticias.com.br/${trafficSource}`}>Headache Cap Pro</a
		>, está João Augusto. João passou por diversos médicos e tratamentos e nunca conseguiu reduzir a
		intensidade de suas dores:
	</p>

	<blockquote>
		"Minha experiência foi completamente satisfatória, haja visto que não encontrava formas de
		reduzir as dores de cabeça, e após o uso continuo da <a
			href={`http://headache-cap-pro.g8-portalnoticias.com.br/${trafficSource}`}>Headache Cap Pro</a
		> consegui reduzir em quase 95% a frequência que sinto dores de cabeça".
	</blockquote>

	<h3>Design altamente Tecnológico</h3>
	<p>
		Quando os médicos indicam o tratamento com a <a
			href={`http://headache-cap-pro.g8-portalnoticias.com.br/${trafficSource}`}>Headache Cap Pro</a
		> não hà o que contestar, devido a sua eficácia. Todo o produto foi calculado pensando nas dores
		dos pacientes.
	</p>

	<p>
		A <a href={`http://headache-cap-pro.g8-portalnoticias.com.br/${trafficSource}`}
			>Headache Cap Pro</a
		> possui as seguintes características:
	</p>
	<ul>
		<li><span>Bloqueia as luzes na área dos olhos;</span></li>
		<li><span>Cobertura da cabeça quente ou frio;</span></li>
		<li><span>Formato exato;</span></li>
		<li><span>Material fabricado com alta tecnologia do tecido em cor preta;</span></li>
		<li><span>Bloqueia as luzes na área dos olhos;</span></li>
		<li><span>Gel no interior do tecido</span></li>
	</ul>

	<p>
		Com toda essa tecnologia a <a
			href={`http://headache-cap-pro.g8-portalnoticias.com.br/${trafficSource}`}>Headache Cap Pro</a
		> ajuda:
	</p>
	<ul>
		<li><span>Alivio das dores de cabeça;</span></li>
		<li><span>Diminuição nas crises de enxaquecas;</span></li>
		<li><span>Custo benefício excelente;</span></li>
		<li><span>Exclusão do uso de medicamentos</span></li>
	</ul>

	<h3>Como faço para adquirir?</h3>
	<p>
		A boa notícia é que o fabricante está oferecendo um desconto exclusivo em todo Brasil. Porém, <strong
			>a quantidade é limitada e o preço promocional estará disponível apenas hoje ({new Date().toLocaleDateString(
				'pt-br'
			)}).</strong
		>
	</p>
	<p>
		O produto é vendido através do revendedor oficial no país, e se encontra <a
			href={`http://headache-cap-pro.g8-portalnoticias.com.br/${trafficSource}`}>neste link</a
		>. Não perca mais tempo sofrendo com dores de cabeça e enxaquecas, a hora de comprar a
		<a href={`http://headache-cap-pro.g8-portalnoticias.com.br/${trafficSource}`}
			>Headache Cap Pro</a
		>
		é agora, visto que o desconto dura até hoje, dia
		<strong>{new Date().toLocaleDateString('pt-br')}</strong>.
	</p>

	<p>
		Com esses benefícios e essa qualidade este produto poderia custar até 10 vezes mais. Chega a ser
		um milagre para quem busca métodos para melhorar sua qualidade de vida. <br />
		Também é um presente incrível para família, amigos ou colegas de trabalho. Eles vão pensar que você
		importa com a saúde deles.
	</p>

	<p />

	<p>
		Se você não aguenta mais buscar meios para acabar com suas dores de cabeça e crises de enxaqueca
		chegou a solução, agora é a hora de comprar a <a
			href={`http://headache-cap-pro.g8-portalnoticias.com.br/${trafficSource}`}>Headache Cap Pro</a
		>.
	</p>

	<div class="product">
		<a href={`http://headache-cap-pro.g8-portalnoticias.com.br/${trafficSource}`}>
			<div class="product__container">
				<div class="product__image">
					<img src={product} alt="Imagem e link do produto com desconto" />
				</div>
				<div class="product__details">
					<span class="product__title">Headache Cap Pro</span>

					<span class="product__subtitle">
						<span class="product__rating">
							<i>★</i><i>★</i><i>★</i><i>★</i><i>★</i>
						</span>
						(857) avaliações
					</span>

					<a
						class="btn btn__featured"
						href={`http://headache-cap-pro.g8-portalnoticias.com.br/${trafficSource}`}
						>Aplicar Desconto</a
					>
					<a class="btn" href={`http://headache-cap-pro.g8-portalnoticias.com.br/${trafficSource}`}
						>Saiba Mais</a
					>
				</div>
			</div>
		</a>
	</div> -->

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
		background-color: white;
		border: 1px solid $primaryColor;
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

	ul.checked {
		li {
			margin-top: 1em;
		}

		li::before {
			content: "✅ ";
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
				width: 100%;
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
				margin-bottom: 2em;
				.product__title {
					font-size: var(--step-4);
					font-weight: bold;
				}

				.product__subtitle {
					font-size: var(--step-3);
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
</style>
