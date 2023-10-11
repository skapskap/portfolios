<script>
	import Fa from 'svelte-fa/src/fa.svelte';
	import {
		faMagnifyingGlass,
		faKeyboard,
		faPalette,
		faComputer,
		faNetworkWired
	} from '@fortawesome/free-solid-svg-icons';
</script>

<div class="mx-auto mt-6 mb-8 px-5">
	<h2 class="my-5 text-2xl flex items-center text-yellow-500" data-svelte-h="svelte-ux5qrk">
		<Fa icon={faMagnifyingGlass} class="text-yellow-500 fa-2x mr-2" />
		Skills
	</h2>

	<div class="grid gap-4 sm:grid-cols-2 xl:grid-cols-4">
		<div
			class="rounded p-5 bg-white/50 dark:bg-zinc-800 shadow dark:shadow-zinc-700 hover:shadow-lg hover:dark:shadow-yellow-500 text-white"
		>
			<h3 class="text-xl flex items-center">
				<Fa icon={faKeyboard} class="text-white fa-2x mr-2" />&nbsp;Linguagens
			</h3>
			<hr />
			<br />
			<div>
				<span>JavaScript, TypeScript</span>
				<div class="h-2 rounded bg-zinc-200 dark:bg-zinc-700">
					<div class="h-2 rounded bg-yellow-600" style="width: 90%" />
				</div>
				<br />
			</div>
			<div>
				<span>Go</span>
				<div class="h-2 rounded bg-zinc-200 dark:bg-zinc-700">
					<div class="h-2 rounded bg-yellow-600" style="width: 85%" />
				</div>
				<br />
			</div>
			<div>
				<span>Python</span>
				<div class="h-2 rounded bg-zinc-200 dark:bg-zinc-700">
					<div class="h-2 rounded bg-yellow-600" style="width: 78%" />
				</div>
				<br />
			</div>
		</div>
		<div
			class="rounded p-5 bg-white/50 dark:bg-zinc-800 shadow dark:shadow-zinc-700 hover:shadow-lg hover:dark:shadow-yellow-500 text-white"
		>
			<h3 class="text-xl flex items-center">
				<Fa icon={faPalette} class="text-white fa-2x mr-2" />&nbsp;Estilização
			</h3>
			<hr />
			<br />
			<div>
				<span>CSS</span>
				<div class="h-2 rounded bg-zinc-200 dark:bg-zinc-700">
					<div class="h-2 rounded bg-yellow-600" style="width: 80%" />
				</div>
				<br />
			</div>
			<div>
				<span>PostCSS, Tailwind</span>
				<div class="h-2 rounded bg-zinc-200 dark:bg-zinc-700">
					<div class="h-2 rounded bg-yellow-600" style="width: 70%" />
				</div>
				<br />
			</div>
		</div>
		<div
			class="rounded p-5 bg-white/50 dark:bg-zinc-800 shadow dark:shadow-zinc-700 hover:shadow-lg hover:dark:shadow-yellow-500 text-white"
		>
			<h3 class="text-xl flex items-center">
				<Fa icon={faComputer} class="text-white fa-2x mr-2" />&nbsp;Front
			</h3>
			<hr />
			<br />
			<div>
				<span>Svelte, SvelteKit</span>
				<div class="h-2 rounded bg-zinc-200 dark:bg-zinc-700">
					<div class="h-2 rounded bg-yellow-600" style="width: 80%" />
				</div>
				<br />
			</div>
			<div>
				<span>Angular, RxJS</span>
				<div class="h-2 rounded bg-zinc-200 dark:bg-zinc-700">
					<div class="h-2 rounded bg-yellow-600" style="width: 65%" />
				</div>
				<br />
			</div>
			<div>
				<span>React, NextJS</span>
				<div class="h-2 rounded bg-zinc-200 dark:bg-zinc-700">
					<div class="h-2 rounded bg-yellow-600" style="width: 50%" />
				</div>
				<br />
			</div>
		</div>
		<div
			class="rounded p-5 bg-white/50 dark:bg-zinc-800 shadow dark:shadow-zinc-700 hover:shadow-lg hover:dark:shadow-yellow-500 text-white"
		>
			<h3 class="text-xl flex items-center">
				<Fa icon={faNetworkWired} class="text-white fa-2x mr-2" />&nbsp;Back
			</h3>
			<hr />
			<br />
			<div>
				<span>Go (stdlib + Chi)</span>
				<div class="h-2 rounded bg-zinc-200 dark:bg-zinc-700">
					<div class="h-2 rounded bg-yellow-600" style="width: 95%" />
				</div>
				<br />
			</div>
			<div>
				<span>PostgreSQL</span>
				<div class="h-2 rounded bg-zinc-200 dark:bg-zinc-700">
					<div class="h-2 rounded bg-yellow-600" style="width: 85%" />
				</div>
				<br />
			</div>
			<div>
				<span>Flask, Django</span>
				<div class="h-2 rounded bg-zinc-200 dark:bg-zinc-700">
					<div class="h-2 rounded bg-yellow-600" style="width: 70%" />
				</div>
				<br />
			</div>
			<div>
				<span>Node, Express</span>
				<div class="h-2 rounded bg-zinc-200 dark:bg-zinc-700">
					<div class="h-2 rounded bg-yellow-600" style="width: 60%" />
				</div>
				<br />
			</div>
			<div>
				<span>Docker, CI/CD</span>
				<div class="h-2 rounded bg-zinc-200 dark:bg-zinc-700">
					<div class="h-2 rounded bg-yellow-600" style="width: 65%" />
				</div>
				<br />
			</div>
		</div>
	</div>
</div>
