<nav>
	<div class="brand">
		Alarabiya Tyre
	</div>

	<div class="links">
		<a href="/">Home</a>
		<a href="/about">About Us</a>
		<a href="/contact">Contact</a>
		<a href="/privacy-policy">Privacy Policy</a>
	</div>
</nav>

<main>
	<slot />
</main>

<footer>
		<p>© 2026 Alarabiya Tyre. All Rights Reserved.</p>
</footer>

<style>
	nav {
		display: flex;
		justify-content: space-between;
		align-items: center;
		padding: 1rem 2rem;
		border-bottom: 1px solid #ddd;
	}

	.brand {
		font-weight: 700;
		font-size: 1.1rem;
	}

	.links {
		display: flex;
		gap: 1.5rem;
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
		margin-top: 4rem;
		padding: 2rem;
		text-align: center;
		border-top: 1px solid #ddd;
		font-size: 0.9rem;
	}
</style>