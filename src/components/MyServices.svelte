<script>
	import Atome from '../Assets/atome.png';
	import Design from '../Assets/designLogo.png';
	import Flex from '../Assets/flexLogo.png';
	import Rocket from '../Assets/rocketLogo.png';
	import Seo from '../Assets/seoLogo.png';
</script>

<main class="main">
	<h2 class="title">Pourquoi choisir nos services ?</h2>
	<p class="subtitle">
		Parce que nous apportons des solutions modernes à votre entreprise en répondant à vos besoins.
		<br />Nous concevons des sites internet avec Wordpress pour des sites internet pros, livrés sous 3 jours, clés en main avec CMS, <br /> pour un budget défiant toute concurrence, c'est <a href="/creation-site-internet" class="maillage">notre produit d'appel</a>. <br> Nous vous proposons également des sites internet sous d'autres formes, avec ou sans CMS pour vos projets e-commerces, vitrines, évenementiels <br /> ou encore des <a href="/creation-application" class="maillage">applications web et mobiles</a>, pour vous aider à développer votre activité.
		<br /><br />Et nous allons plus loin, grâce à notre expertise en programmation informatique, en vous proposant une offre complète d'outils digitaux.
		<br />Que ce soit pour des sites internet sur mesure, codés ou des applications natives, <br />nos audits sur vos besoins spécifiques sont 100% gratuit et nous saurons à l'issue, vous proposer un outil digital qui vous apportera entière satisfaction.
		<br /> Nos <a href="/tarifs" class="maillage">tarifs </a> sont très élaborés grâce à notre adaptablité, pour que vous puissiez obtenir le meilleur rapidement, à des prix très doux et très raisonnables. <br />

	</p>
	<div class="container">
		<div class="wrapper__cards">
			<div class="wrapper__sectionByThree">
				<div class="wrapper__cards-card">
					<img class="logo" src={Rocket} alt="fusée" />
					<h3 class="subtitle-h3">Performance</h3>
					<h4 class="subtitle-h4">Le meilleur des technologies pour un code léger <br /> et ultra-rapide</h4>
				</div>

				<div class="wrapper__cards-card">
					<img class="logo" src={Flex} alt="une personne danse et représente la flexibilté" />
					<h3 class="subtitle-h3">Flexibilité</h3>
					<h4 class="subtitle-h4">Avec ou sans gestion de contenu. <br /> Avec ou sans forfait de maintenance</h4>
				</div>
			</div>
			<div class="wrapper__sectionByThree">
				<div class="wrapper__cards-card">
					<img class="logo" src={Seo} alt="illustration sur le SEO" />
					<h3 class="subtitle-h3">SEO audit</h3>
					<h4 class="subtitle-h4">Nous sommes experts en stratégie SEO, <br /> pour une visibilié optimale de votre business.</h4>
				</div>

				<div class="wrapper__cards-card">
					<img class="logo" src={Design} alt="une plume colorée" />
					<h3 class="subtitle-h3">Design moderne</h3>
					<h4 class="subtitle-h4">Une expérience utilisateur <br />fluide et intuitive, <br /> avec modèles de templates ou en total custom.</h4>
				</div>
			</div>
			<div class="wrapper__cta">
				<h2 class="call-to-action-txt">En savoir plus sur notre agence Web ?</h2>
				<a class="button" href="/creation-site-application-Lyon">En savoir +</a>
			</div>
		</div>
	</div>
</main>

<style>
	.main {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		padding: 30px;
		gap: 40px;
		height: auto;
		background-image: url('../Assets/bird.jpeg');
		background-attachment: fixed;
		background-size: cover;
		background-position: center;
		background-repeat: no-repeat;
		z-index: 0;
		position: relative;
	}
	.main::after {
		content: '';
		position: absolute;
		top: 0;
		left: 0;
		width: 100%;
		height: 100%;
		background-image: linear-gradient(to bottom, rgba(0, 0, 0, 0.861) 25%, rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.2), rgba(0, 0, 0, 0.1), rgba(0, 0, 0, 0.05), rgba(0, 0, 0, 0.01), rgba(0, 0, 0, 0));
		z-index: 1;
	}

	.container {
		display: flex;
		justify-content: center;
		align-items: center;
		height: auto;
		z-index: 2;
	}
	.wrapper__sectionByThree {
		display: flex;
		flex-wrap: wrap;
		align-items: center;
		justify-content: center;
		gap: 10px;
		height: auto;
		margin-top: 40px;
		margin-bottom: 0px;
	}
	.wrapper__cards {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex-wrap: wrap;
		gap: 50px;
		padding: 20px;
		border-radius: 20px;
		width: 100%;
		height: auto;
	}
	.wrapper__cards-card {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: space-around;
		flex: 1 1 0;
		gap: 10px;
		min-width: 350px;
		min-height: 300px;
		border-radius: 20px;
		padding: 30px;
		background-color: rgba(37, 36, 36, 0.28);
		backdrop-filter: blur(10px);
		-webkit-backdrop-filter: blur(10px);
	}
	.wrapper__cta {
		display: flex;
		flex-direction: column;
		gap: 30px;
		background-color: var(--primary);
		padding: 60px;
		border-radius: 5px;
		box-shadow: 30px 20px 10px 2px rgba(76, 76, 76, 0.35);
	}

	.title {
		font-size: 2rem;
		font-weight: 600;
		color: var(--whiteGrey);
		margin-top: 20px;
		font-family: var(--Red);
		padding: 0px;
		text-align: center;
		z-index: 2;
	}

	.subtitle {
		font-size: 1rem;
		font-weight: 400;
		line-height: 2rem;
		color: var(--whiteGrey);
		margin-top: 20px;
		font-family: var(--Red);
		padding: 0px;
		text-align: justify;
		z-index: 2;
	}

	.subtitle-h3 {
		font-size: 1.5rem;
		font-weight: 900;
		color: var(--whiteGrey);
		text-align: center;
		font-family: var(--Geologica);
		padding: 0px;
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}
	.subtitle-h4 {
		font-size: 1rem;
		font-weight: 100;
		color: var(--whiteGrey);
		text-align: center;
		font-family: var(--Geologica);
		padding: 0px;
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}
	.maillage{
		color: var(--green);
		text-decoration: none;
		font-size: 1rem;
		font-weight: 600;
		letter-spacing: 0px;
	}

	.call-to-action-txt {
		font-size: 1.5rem;
		font-weight: 700;
		color: var(--whiteGrey);
		text-align: center;
		font-family: var(--Red);
		padding: 0px;
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}

	.logo {
		width: 50px;
		height: 50px;
		/* border-radius: 50%; */
	}
	.button {
		align-self: center;
		background-color: var(--green);
		color: var(--primary);
		padding: 10px 20px;
		border-radius: 10px;
		text-decoration: none;
		font-family: var(--Red);
		font-weight: 700;
		max-width: 150px;
		text-align: center;
	}
	.button:hover {
		background-color: var(--primary);
		border: 1px solid grey;
		color: var(--whiteGrey);
		transition: 0.4s ease-in-out;
	}

	@media screen and (max-width: 768px) {
		.wrapper__sectionByThree {
			display: flex;
			flex-direction: column;
			gap: 20px;
			margin: 0;
		}
		.wrapper__cards {
			flex-wrap: nowrap;
		}
		.wrapper__cards-card {
			max-width: 80%;
			min-height: 300px;
			margin: 0px;
		}
		.wrapper__cta {
			width: 280px;
		}
		.subtitle {
			font-size: 1rem;
			font-weight: 400;
			line-height: 2rem;
			color: var(--whiteGrey);
			margin-top: 20px;
			font-family: var(--Red);
			text-align: justify;
			z-index: 2;
		}
	}
	@media screen and (max-width: 407px) {
		.wrapper__cards-card {
			min-width: 280px;
			min-height: 300px;
			margin: 0px;
		}
	}
</style>
