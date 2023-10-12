<script lang="ts">
	import Nav from '$lib/Components/Nav.svelte';
	import Skills from '$lib/Components/Skills.svelte';
</script>

<Nav />

<div
	class="min-h-screen px-[200px] max-lg:px-0 flex flex-col items-center pt-8 bg-gradient-to-b from-zinc-950 via-zinc-900 to-zinc-800"
>
	<div class="grid grid-cols-1 md:grid-cols-3 border-yellow-400 rounded-xl bg-slate-950">
		<div class="flex flex-col p-3">
			<img src="https://i.imgur.com/4zQAjD1.jpg" alt="Avatar" class="border rounded-md" />
			<div
				class="border border-slate-900 bg-slate-950 mt-2 rounded-xl flex flex-col items-center justify-center p-3"
			>
				<h1 class="text-2xl 2xl:text-4xl text-white">Gabriel de Lima Caldas</h1>
			</div>
		</div>
		<div class="flex flex-col col-span-2 p-3">
			<div class="border border-slate-900 flex flex-col gap-3 rounded-xl p-3">
				<div class="flex justify-between items-center">
					<h2 class="text-white">Sobre Mim</h2>
				</div>
				<main class="text-slate-300">
					<p class="text-base 2xl:text-2xl">
						Tenho 23 anos, sou de Itaboraí, interior do estado do Rio de Janeiro. Tenho contato com
						tecnologia desde os 3 anos de idade por conta do meu pai, que era técnico de
						informática, com quem também trabalhei com montagem e manutenção de computadores. <br />
						Meu primeiro contato com programação foi com 9 anos, criando blogs de Pokémon e anime no
						geral e meu segundo foi aos 14, quando aprendi um pouco de Lua para fazer karaokês no Aegisub.
						Nessa idade, também ingressei num curso de informática, aprendendo sintaxe de HTML, CSS e
						Javascript. Algum tempo depois, também estagiei na empresa durante quase um ano.
						<br />Estou cursando Análise e Desenvolvimento de Sistemas na
						<a
							target="_blank"
							class="underline hover:text-yellow-600"
							href="https://www.unicesumar.edu.br/home/"
							rel="noreferrer">UniCesumar</a
						>
						e no momento atuo como Desenvolvedor na empresa júnior
						<a
							target="_blank"
							class="underline hover:text-yellow-600"
							href="https://www.linkedin.com/company/mentor-code/about/"
							rel="noreferrer">CodeMentor</a
						>
						atuando na criação de APIs Restful na Squad de
						<a
							target="_blank"
							class="underline hover:text-yellow-600"
							href="https://www.djangoproject.com/"
							rel="noreferrer">Django</a
						>.
					</p>
				</main>
			</div>
		</div>
	</div>
	<section class="container items-center">
		<Skills />
	</section>
</div>
