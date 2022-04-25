<script>
	import heroImg from '$lib/assets/img/home-page-bg.png';
</script>

<div class="main-hero">
	<div class="hero-content">
		<h1>Hyderabad's First Choice in Dry Cleaning</h1>
		<p>
			A tradition of unsurpassed customer service and unwavering commitment to high quality dry
			cleaning and laundry services for over 91 years.
		</p>
		<a href="/about">Signup for Free Pickup & Delivery</a>
	</div>
	<img src={heroImg} alt="EasyDry" class="hero-img" />
</div>

<style>
	.main-hero {
		background-image: url('../lib/assets/img/svgs/bg.svg');
		background-size: cover;
		background-position: center;
		background-repeat: no-repeat;
		background-color: var(--tertiary-color);
		height: 60vh;
		display: flex;
		align-items: center;
		justify-content: center;
	}

	.hero-content {
		display: flex;
		flex-direction: column;
		justify-content: center;
		width: 50%;
		max-width: 500px;
		margin-top: -20vh;
	}

	.hero-content h1 {
		font-size: 3rem;
		font-weight: 500;
		margin-bottom: 1rem;
		text-align: left;
		font-family: var(--font-mono);
	}

	.hero-content p {
		font-size: 0.8rem;
		font-weight: 300;
		margin-bottom: 1rem;
	}

	.hero-content a {
		color: #fff;
		background-color: var(--accent-color);
		padding: 1rem 2rem;
		border-radius: 8px;
		font-size: 1rem;
		font-weight: 400;
		margin-top: 1rem;
	}
</style>
