<script>
	import logo from '$lib/assets/logo.png';
</script>

<svelte:head>
	<title>Alarabiya Tyre</title>
	<meta
		name="description"
		content="Professional tire sales, wheel services and automotive accessories in Muscat, Oman."
	/>
</svelte:head>

<section class="hero">
	<img src={logo} alt="Alarabiya Tyre Logo" class="logo" />

	<h1>Alarabiya Tyre</h1>

	<p class="subtitle">
		Professional Tire & Wheel Services in Muscat, Oman
	</p>

	<a class="cta" href="/contact">
		Contact Us
	</a>
</section>

<section class="services">
	<h2>Our Services</h2>

	<div class="service-list">
		<div class="card">Tire Replacement</div>
		<div class="card">Wheel Balancing</div>
		<div class="card">Rim Services</div>
		<div class="card">Vehicle Accessories</div>
	</div>
</section>

<section class="business-info">
	<h2>Business Information</h2>

	<p><strong>Phone:</strong> +968 7209 5000</p>

	<p><strong>Email:</strong> alarabiyatire@gmail.com</p>

	<p>
		<strong>Location:</strong>
		Al Maabilah Industrial Area 1, Muscat, Oman
	</p>
</section>

<style>
	.hero {
		text-align: center;
		padding: 3rem 1rem;
	}

	.logo {
		width: 220px;
		max-width: 100%;
		margin: 0 auto 1rem;
		display: block;
	}

	h1 {
		margin-bottom: 0.5rem;
	}

	.subtitle {
		font-size: 1.1rem;
		margin-bottom: 1.5rem;
	}

	.cta {
		display: inline-block;
		padding: 0.8rem 1.4rem;
		border-radius: 8px;
		text-decoration: none;
		border: 1px solid #ccc;
	}

	.services {
		margin-top: 3rem;
	}

	.service-list {
		display: grid;
		grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
		gap: 1rem;
		margin-top: 1rem;
	}

	.card {
		border: 1px solid #ddd;
		border-radius: 10px;
		padding: 1rem;
		text-align: center;
	}

	.business-info {
		margin-top: 3rem;
		padding-top: 2rem;
		border-top: 1px solid #ddd;
	}
</style>