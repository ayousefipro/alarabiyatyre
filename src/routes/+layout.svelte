<script>
    import logo from '$lib/assets/logo.png';
</script>

<nav>
	<div class="brand">
		<img src={logo} alt="Alarabiya Tyre Logo" />
		<span>Alarabiya Tyre</span>
	</div>

	<div class="links">
		<a href="/">Home</a>
		<a href="/about">About Us</a>
		<a href="/contact">Contact</a>
		<!-- <a class="nav-call" href="tel:+96872006001">
            Call Now
        </a> -->
	</div>
</nav>

<main>
	<slot />
</main>


<footer>

    <div class="footer-grid">

        <div>
            <h3>Alarabiya Tyre</h3>

            <p>
                Professional tyre, wheel and suspension services in Muscat.
            </p>
        </div>

        <div>
            <h4>Contact</h4>

            <p>+968 7200 6001</p>

            <p>alarabiyatire@gmail.com</p>
        </div>

        <div>
            <h4>Location</h4>

            <p>
                Al Maabilah Industrial Area 1
                <br>
                Muscat, Oman
            </p>
        </div>

        <div>
            <h4>Working Hours</h4>

            <p>Sat – Thu: 8:00 AM – 11:00 PM</p>

            <p>Fri: 2:00 PM – 11:00 PM</p>
        </div>

    </div>

    <div class="footer-bottom">

        <div>
            © 2026 Alarabiya Tyre
        </div>

        <div class="footer-links">

            <a href="/">Home</a>

            <a href="/about">About</a>

            <a href="/contact">Contact</a>

            <a href="/privacy-policy">Privacy Policy</a>

        </div>

    </div>

</footer>

<style>
	:global(body) {
		background-color: #fafafa;
		margin: 0;
	}
	nav {
		display: flex;
		justify-content: space-between;
		align-items: center;

		padding: 1rem 2rem;

		background: white;

		border-bottom: 1px solid #e4e4e7;
		box-shadow: 0 1px 3px rgba(0,0,0,.05);
	}

	.navbar {
		position: sticky;
		top: 0;
		z-index: 1000;

		display: flex;
		justify-content: space-between;
		align-items: center;

		padding: 1rem 2rem;

		background: rgba(255,255,255,.92);

		backdrop-filter: blur(12px);

		border-bottom: 1px solid #eee;
	}

	.brand {
		display: flex;
		align-items: center;
		gap: 0.75rem;

		font-weight: 700;
		font-size: 1.1rem;
	}

	.brand img {
		width: 80px;
		height: 80px;

		object-fit: contain;
	}

	.links {
		display: flex;
		gap: 2rem;
	}

	.links a {
		text-decoration: none;
		color: #3f3f46;
		font-weight: 500;
		transition: color .2s ease;
	}

	.links a:hover {
		color: #b91c1c;
	}

	.nav-call {
		background: #dc2626;

		color: white !important;

		padding: .75rem 1.2rem;

		border-radius: 10px;
	}

	.nav-call:hover {
		transform: translateY(-2px);
	}

	a {
		text-decoration: none;
		color: inherit;
	}

	main {
		max-width: 1200px;
		margin: 0 auto;
		padding: 1rem;
	}

	footer {
		margin-top: 5rem;

		background: #18181b;

		color: white;

		padding: 3rem 2rem 2rem;
	}

	.footer-grid {
		display: grid;

		grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));

		gap: 2rem;

		margin-bottom: 2rem;
	}

	.footer-grid h3,
	.footer-grid h4 {
		margin-bottom: 1rem;
	}

	.footer-grid p {
		color: #d1d5db;

		line-height: 1.8;
	}

	.footer-bottom {
		border-top: 1px solid rgba(255,255,255,.15);

		padding-top: 1.5rem;

		display: flex;

		justify-content: space-between;

		align-items: center;

		flex-wrap: wrap;

		gap: 1rem;
	}

	.footer-links {
		display: flex;

		flex-wrap: wrap;

		gap: 1.5rem;
	}

	.footer-links a {
		color: #d1d5db;

		text-decoration: none;
	}

	.footer-links a:hover {
		color: white;
	}

	@media (max-width:768px) {

	.navbar {
		padding: 1rem;
	}

	.links a:not(.nav-call) {
		display: none;
	}

	.footer-bottom {
        flex-direction: column;

        text-align: center;
    }

    .footer-links {
        justify-content: center;
    }
	}
</style>