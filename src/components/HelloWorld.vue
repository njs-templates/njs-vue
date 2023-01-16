<script setup lang="ts">
import { ref } from "vue";

defineProps<{ msg: string }>();

const count = ref(0);
</script>

<template>
	<div class="grid grid-cols-1 justify-items-center space-y-5">
		<h1>{{ msg }}</h1>
		<button
			class="btn btn-primary font-bold"
			type="button"
			@click="count++"
		>
			count is {{ count }}
		</button>
		<p>
			Edit
			<code>components/HelloWorld.vue</code> to test HMR
		</p>

		<p>
			Check out
			<a
				class="link"
				href="https://vuejs.org/guide/quick-start.html#local"
				target="_blank"
				>create-vue</a
			>, the official Vue + Vite starter
		</p>
		<p>
			Install
			<a
				class="link"
				href="https://github.com/johnsoncodehk/volar"
				target="_blank"
				>Volar</a
			>
			in your IDE for a better DX
		</p>
		<p class="read-the-docs">Click on the logos to learn more</p>
	</div>
</template>

<style scoped>
.read-the-docs {
	@apply text-accent;
}
</style>
