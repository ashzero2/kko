<!-- Responsive Church Navbar -->
<script>
	let menuOpen = true;
</script>

<nav class="w-full bg-primary-50 text-white shadow-lg">
	<div class="max-w-6xl mx-auto px-4 flex items-center justify-between h-16">
		<div class="flex items-center gap-3">
			<img src="/kko.png" alt="Church Logo" class="w-8 h-8 rounded-full" />
			<span class="font-bold text-xl text-surface-700 tracking-wide">Rock of Kindness</span>
		</div>
		<div class="hidden md:flex gap-8">
			<a href="/" class="hover:text-blue-200 text-surface-700 font-medium">Home</a>
			<a href="#services" class="hover:text-blue-200 text-surface-700 font-medium">Services</a>
			<a href="#events" class="hover:text-blue-200 text-surface-700 font-medium">Events</a>
			<a href="#about" class="hover:text-blue-200 text-surface-700 font-medium">About</a>
			<a href="tel:+1234567890" class="hover:text-blue-200 text-surface-700 font-medium">Call</a>
			<a href="mailto:info@rockofkindness.org" class="hover:text-blue-200 text-surface-700 font-medium">Contact</a>
		</div>
		<!-- Mobile menu button -->
		<button class="md:hidden focus:outline-none" on:click={() => menuOpen = !menuOpen} aria-label="Toggle menu">
			<svg class="w-7 h-7 text-surface-700" fill="none" stroke="currentColor" viewBox="0 0 24 24">
				<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
			</svg>
		</button>
	</div>
	<!-- Mobile menu -->
	{#if menuOpen}
		<div class="md:hidden bg-primary-100 px-4 pb-4 pt-2 flex flex-col gap-4">
			<a href="/" class="hover:text-blue-200 font-medium text-surface-700">Home</a>
			<a href="#services" class="hover:text-blue-200 font-medium text-surface-700">Services</a>
			<a href="#events" class="hover:text-blue-200 font-medium text-surface-700">Events</a>
			<a href="#about" class="hover:text-blue-200 font-medium text-surface-700">About</a>
			<a href="tel:+1234567890" class="hover:text-blue-200 font-medium text-surface-700">Call</a>
			<a href="mailto:info@rockofkindness.org" class="hover:text-blue-200 font-medium text-surface-700">Contact</a>
		</div>
	{/if}
</nav>
