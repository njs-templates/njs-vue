<script setup lang="ts">
import NavBar from "./components/NavBar.vue";
</script>

<template>
	<!-- <div id="nav">
		<RouterLink to="/">Home</RouterLink>
		<RouterLink to="/other">Other</RouterLink>
	</div> -->
	<NavBar />
	<RouterView />
</template>

<style scoped></style>
