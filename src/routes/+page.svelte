<script>
	import logo from '$lib/assets/logo.png';
	import Wrench from 'lucide-svelte/icons/wrench';
	import CircleGauge from 'lucide-svelte/icons/gauge';
	import Disc3 from 'lucide-svelte/icons/disc-3';
	import Car from 'lucide-svelte/icons/car';
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

	<div class="actions">
		<a class="call-btn" href="tel:+96872006001">
			Call Now
		</a>

		<a class="contact-btn" href="/contact">
			Contact Us
		</a>
	</div>

</section>

<section class="services">
	<h2>Our Services</h2>

	<div class="service-list">
		<div class="card">
			<Wrench size={36} />
			<h3>Tire Replacement</h3>
		</div>

		<div class="card">
			<CircleGauge size={36} />
			<h3>Wheel Balancing</h3>
		</div>

		<div class="card">
			<Disc3 size={36} />
			<h3>Rim Services</h3>
		</div>

		<div class="card">
			<Car size={36} />
			<h3>Vehicle Accessories</h3>
		</div>
	</div>
</section>

<section class="business-info">
	<h2>Business Information</h2>

	<p><strong>Phone:</strong> +968 7200 6001</p>

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
		border-radius: 12px;
		padding: 1.5rem;
		text-align: center;
		display: flex;
		flex-direction: column;
		align-items: center;
		gap: 0.75rem;
		transition: 0.2s ease;
	}

	.card:hover {
		transform: translateY(-3px);
	}

	.business-info {
		margin-top: 3rem;
		padding-top: 2rem;
		border-top: 1px solid #ddd;
	}

	.actions {
		display: flex;
		justify-content: center;
		gap: 1rem;
		margin-top: 1.5rem;
		flex-wrap: wrap;
	}

	.call-btn,
	.contact-btn {
		padding: 0.9rem 1.5rem;
		border-radius: 10px;
		text-decoration: none;
		font-weight: 600;
	}

	.call-btn {
		background: #111;
		color: white;
	}

	.contact-btn {
		border: 1px solid #ccc;
		color: inherit;
	}
</style>