<script>
	import AppBar from '../components/AppBar.svelte';
</script>

<!-- Church Home Page Design -->
<main>
	<AppBar />
	<section
		class="flex min-h-screen flex-col items-center justify-center bg-gradient-to-br from-blue-100 to-white py-12"
	>
		<div class="w-full max-w-2xl px-6 text-center">
			<img src="/kko.png" alt="Church Logo" class="mx-auto mb-6 h-24 w-24 rounded-full shadow-lg" />
			<h1 class="mb-4 text-4xl font-extrabold text-blue-900">Rock of Kindness Church</h1>
			<p class="mb-8 text-lg text-gray-700">
				A place to worship, connect, and grow in faith. Join us for Sunday service, community
				events, and spiritual resources for all ages.
			</p>
			<div class="mb-8 flex flex-col justify-center gap-4 sm:flex-row">
				<a
					href="#services"
					class="rounded-lg bg-blue-700 px-6 py-3 font-semibold text-white shadow transition hover:bg-blue-800"
					>Sunday Services</a
				>
				<a
					href="#events"
					class="rounded-lg border border-blue-700 bg-white px-6 py-3 font-semibold text-blue-700 shadow transition hover:bg-blue-50"
					>Upcoming Events</a
				>
				<a
					href="#contact"
					class="rounded-lg bg-blue-100 px-6 py-3 font-semibold text-blue-900 shadow transition hover:bg-blue-200"
					>Contact Us</a
				>
			</div>
			<div class="mx-auto prose prose-lg rounded-xl bg-white/80 p-6 text-left shadow">
				<h2 class="mb-2 text-2xl font-bold text-blue-800">Our Mission</h2>
				<p>
					To share the love of Christ, serve our community, and help each person discover their
					purpose in God’s family.
				</p>
				<ul class="mt-4 list-disc pl-6">
					<li>Weekly worship and prayer gatherings</li>
					<li>Children, youth, and adult ministries</li>
					<li>Community outreach and support</li>
					<li>Spiritual growth resources</li>
				</ul>
			</div>
		</div>
	</section>
</main>
