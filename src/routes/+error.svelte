<script lang="ts">
	import { page } from "$app/state";
</script>

<main class="page">
	<h1>Issue {page.status}</h1>
	<p>{page.error?.message ?? "An unexpected error occurred while processing your financial workflow."}</p>
	<a href="/">Return to Billow Dashboard</a>
</main>
