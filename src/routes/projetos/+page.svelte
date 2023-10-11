<script>
	import Nav from '$lib/Components/Nav.svelte';

	let lines = ['Bem-vindo ao meu portfólio.', 'Por favor, aguarde.', 'Em construção...'];
</script>

<Nav />

<div class="min-h-screen text-yellow-500 p-4 font-mono">
	<pre>
		<div class="text-white mt-8">Acesso ao terminal</div>
		<div class="text-yellow-500">
			<div>
	<span class="text-yellow-500">$</span> <span class="animate-blink">_</span>
			</div>
			{#each lines as line (line)}
				<div>
	<span class="text-yellow-500">$</span> {line}
				</div>
			{/each}
		</div>
	</pre>
</div>

<style>
	.animate-blink {
		animation: blink 1s infinite;
	}

	@keyframes blink {
		0%,
		50% {
			opacity: 0;
		}
		51%,
		100% {
			opacity: 1;
		}

		body {
			background-color: black;
		}
	}
</style>
