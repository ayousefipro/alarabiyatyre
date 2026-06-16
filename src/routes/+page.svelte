<script>
	import logo from '$lib/assets/logo.png';
	import shopImage from '$lib/assets/alarabiya-shop-1.webp';
	import workshop1 from '$lib/assets/alarabiya-workshop-1.webp';
	import workshop2 from '$lib/assets/alarabiya-workshop-2.webp';
	import tyre1 from '$lib/assets/alarabiya-tyre-1.webp';
	import rims1 from '$lib/assets/alarabiya-rims-1.webp';
	import shock1 from '$lib/assets/alarabiya-shock-absorber-1.webp';
	import coil1 from '$lib/assets/alarabiya-coil-spring-1.webp';
	import rims2 from '$lib/assets/alarabiya-rims-2.webp';
	import rims3 from '$lib/assets/alarabiya-rims-3.webp';
	import tyre2 from '$lib/assets/alarabiya-tyre-2.webp';
	import spacer1 from '$lib/assets/alarabiya-rims-spacer-1.webp';
	import spacer2 from '$lib/assets/alarabiya-rims-spacer-2.webp';
	import michelin from '$lib/assets/michelin.png';
	import kumho from '$lib/assets/kumho.png';
	import bridgestone from '$lib/assets/bridgestone.png';
	import yokohama from '$lib/assets/yokohama.png';
	import nexen from '$lib/assets/nexen.png';
	import dunlop from '$lib/assets/dunlop.png';
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

<section
    class="hero"
    style={`background-image:
    linear-gradient(rgba(0,0,0,.55), rgba(0,0,0,.55)),
    url(${shopImage})`}
>
    <div class="hero-content">
        <h1>Alarabiya Tyre</h1>

        <p class="subtitle">
            Professional Tire, Wheel & Suspension Services in Muscat, Oman
        </p>

        <div class="actions">
            <a class="call-btn" href="tel:+96872006001">
                Call Now
            </a>

            <a
                class="whatsapp-btn"
                href="https://wa.me/96872006001"
                target="_blank"
                rel="noopener noreferrer"
            >
                WhatsApp
            </a>
        </div>
    </div>
</section>

<section class="workshop-services">

    <div class="service-row">
        <div class="service-image">
            <img src={workshop1} alt="Vehicle Lifting System" />
        </div>

        <div class="service-content">
            <span class="service-tag">Workshop Services</span>

            <h2>Professional Two-Post Hydraulic Lift</h2>

            <p>
                The XPROMISE two-post hydraulic lift safely raises vehicles to provide full undercarriage access. Ideal for general repairs, oil changes, suspension work, brake service, and exhaust system maintenance.
            </p>
        </div>
    </div>

    <div class="service-row reverse">
        <div class="service-image">
            <img src={workshop2} alt="Wheel Alignment Platform" />
        </div>

        <div class="service-content">
            <span class="service-tag">Precision Care</span>

            <h2>Professional Four-Post Alignment Lift</h2>

            <p>
                This four-post lift with runways is specifically designed for precise wheel alignment and suspension geometry adjustments. The vehicle drives onto the platforms and is raised evenly, allowing technicians to perform accurate alignment, steering, and underbody inspections.
            </p>
        </div>
    </div>

</section>

<section class="products">

    <div class="section-header">
        <span class="section-tag">Our Products</span>

        <h2>Quality Products for Every Vehicle</h2>

        <p>
            We offer a wide range of tyres, rims and suspension components
            from trusted manufacturers to meet your needs.
        </p>
    </div>

    <div class="product-grid">

        <div class="product-card">
            <img src={tyre1} alt="Tyres" />

            <div class="product-content">
                <h3>Premium Tyres</h3>

                <p>
                    Durable and reliable tyres for passenger vehicles and SUVs.
                </p>
            </div>
        </div>

        <div class="product-card">
            <img src={rims1} alt="Rims" />

            <div class="product-content">
                <h3>Stylish Rims</h3>

                <p>
                    Enhance the appearance and performance of your vehicle.
                </p>
            </div>
        </div>

        <div class="product-card">
            <img src={shock1} alt="Shock Absorbers" />

            <div class="product-content">
                <h3>Shock Absorbers</h3>

                <p>
                    Improve ride comfort and vehicle stability.
                </p>
            </div>
        </div>

        <div class="product-card">
            <img src={coil1} alt="Coil Springs" />

            <div class="product-content">
                <h3>Coil Springs</h3>

                <p>
                    Quality suspension components for dependable performance.
                </p>
            </div>
        </div>

    </div>

</section>

<!-- <section class="services">
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
</section> -->

<section class="brands">

    <div class="section-header">
        <span class="section-tag">Trusted Brands</span>

        <h2>We Carry Leading Tyre Brands</h2>

        <p>
            We proudly offer products from internationally trusted manufacturers.
        </p>
    </div>

    <div class="brand-logos">

        <img src={kumho} alt="Kumho" />
        <img src={bridgestone} alt="Bridgestone" />
        <img src={yokohama} alt="Yokohama" />
        <img src={nexen} alt="Nexen" />
        <img src={dunlop} alt="Dunlop" />
		<img src={michelin} alt="Michelin" />
    </div>

</section>

<section class="gallery">

    <div class="section-header">

        <span class="section-tag">
            Gallery
        </span>

        <h2>Inside Our Collection</h2>

        <p>
            Explore a selection of products and components available at
            Alarabiya Tyre.
        </p>

    </div>

    <div class="gallery-grid">

        <div class="gallery-item">
            <img src={rims2} alt="Rims Collection" />
        </div>

		<div class="gallery-item">
            <img src={rims3} alt="Rims Display" />
        </div>

        <div class="gallery-item">
            <img src={tyre2} alt="Tyres Collection" />
        </div>

        <div class="gallery-item">
            <img src={spacer1} alt="Rim Spacer" />
        </div>

    </div>

</section>

<!-- <section class="business-info">
	<h2>Business Information</h2>

	<p><strong>Phone:</strong> +968 7200 6001</p>

	<p><strong>Email:</strong> alarabiyatire@gmail.com</p>

	<p>
		<strong>Location:</strong>
		Al Maabilah Industrial Area 1, Muscat, Oman
	</p>
</section> -->

<style>
	.hero {
		min-height: 70vh;

		display: flex;
		align-items: center;
		justify-content: center;

		text-align: center;

		background-size: cover;
		background-position: center;

		border-radius: 24px;

		color: white;

		padding: 2rem;
	}

	.hero-content {
	    max-width: 700px;
	}

	.hero h1 {
		font-size: clamp(2.5rem, 6vw, 4.5rem);

		margin-bottom: 1rem;

		font-weight: 800;
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
		font-size: 1.2rem;

		line-height: 1.7;

		margin-bottom: 2rem;

		opacity: 0.95;
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
		flex-wrap: wrap;
	}

	.call-btn,

	.whatsapp-btn {
		padding: 1rem 1.8rem;

		border-radius: 12px;

		text-decoration: none;

		font-weight: 700;

		transition: 0.25s ease;
	}
	/* .contact-btn {
		padding: 0.9rem 1.5rem;
		border-radius: 10px;
		text-decoration: none;
		font-weight: 600;
	} */

	.call-btn {
		background: #dc2626;

		color: white;
	}

	.call-btn:hover {
		transform: translateY(-3px);
	}

	/* .contact-btn {
		border: 1px solid #ccc;
		color: inherit;
	} */
	 .whatsapp-btn {
		background: white;

		color: #111827;
	}

	.whatsapp-btn:hover {
		transform: translateY(-3px);
	}

	.workshop-services {
		margin-top: 5rem;
	}

	.service-row {
		display: grid;
		grid-template-columns: 1fr 1fr;

		gap: 3rem;

		align-items: center;

		margin-bottom: 5rem;
	}

	.reverse {
		direction: rtl;
	}

	.reverse .service-content {
		direction: ltr;
	}

	.service-image img {
		width: 100%;

		height: 380px;

		object-fit: cover;

		border-radius: 20px;

		box-shadow: 0 12px 30px rgba(0, 0, 0, 0.12);
	}

	.service-tag {
		display: inline-block;

		background: #fee2e2;

		color: #dc2626;

		padding: 0.4rem 0.8rem;

		border-radius: 999px;

		font-size: 0.85rem;

		font-weight: 700;

		margin-bottom: 1rem;
	}

	.service-content h2 {
		font-size: 2rem;

		margin-bottom: 1rem;

		color: #111827;
	}

	.service-content p {
		line-height: 1.8;

		color: #4b5563;

		font-size: 1.05rem;
	}

	.products {
		margin-top: 5rem;
	}

	.section-header {
		text-align: center;

		max-width: 700px;

		margin: 0 auto 3rem;
	}

	.section-header h2 {
		font-size: 2.2rem;

		margin: 1rem 0;
	}

	.section-header p {
		color: #6b7280;

		line-height: 1.8;
	}

	.section-tag {
		display: inline-block;

		background: #fee2e2;

		color: #dc2626;

		padding: 0.4rem 0.8rem;

		border-radius: 999px;

		font-size: 0.85rem;

		font-weight: 700;
	}

	.product-grid {
		display: grid;

		grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));

		gap: 2rem;
	}

	.product-card {
		background: white;

		border-radius: 20px;

		overflow: hidden;

		box-shadow: 0 12px 30px rgba(0, 0, 0, 0.08);

		transition: 0.3s ease;
	}

	.product-card:hover {
		transform: translateY(-8px);
	}

	.product-card img {
		width: 100%;

		height: 240px;

		object-fit: cover;
	}

	.product-content {
		padding: 1.5rem;
	}

	.product-content h3 {
		margin-bottom: 0.75rem;

		color: #111827;
	}

	.product-content p {
		color: #6b7280;

		line-height: 1.7;
	}

	.brands {
		margin-top: 5rem;
		text-align: center;
	}

	.brand-logos {
		margin-top: 3rem;

		display: flex;
		flex-wrap: wrap;

		justify-content: center;
		align-items: center;

		gap: 3rem;
	}

	.brand-logos img {
		height: 50px;

		max-width: 140px;

		object-fit: contain;

		opacity: 0.75;

		transition: 0.3s ease;
	}

	.brand-logos img:hover {
		opacity: 1;

		filter: grayscale(0);

		transform: translateY(-3px);
	}

	.gallery {
		margin-top: 5rem;
	}

	.gallery-grid {
		display: grid;

		grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));

		gap: 1rem;
	}

	.gallery-item {
		overflow: hidden;

		border-radius: 20px;

		box-shadow: 0 12px 30px rgba(0,0,0,.08);
	}

	.gallery-item img {
		width: 100%;

		aspect-ratio: 16 / 9;
		height: auto;

		object-fit: cover;

		display: block;

		transition: transform .4s ease;
	}

	.gallery-item:hover img {
		transform: scale(1.06);
	}
	@media (max-width: 768px) {
		.hero {
			min-height: 80vh;

			background-position: center 15%;
		}
		
		.service-row {
			grid-template-columns: 1fr;

			gap: 1.5rem;
		}

		.reverse {
			direction: ltr;
		}

		.service-image img {
			height: 480px;
		}

		.service-content h2 {
			font-size: 1.6rem;
		}
	}
</style>