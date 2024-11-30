<script lang="ts">
	import Header from '$lib/components/Header.svelte';
</script>

<Header />
<slot />

<style lang="scss">
	@import url('https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,100..900;1,100..900&display=swap');

	:global(*) {
		margin: 0;
		padding: 0;
		box-sizing: border-box;
	}

	:global(body) {
		font-family: 'Raleway', sans-serif;
		font-style: normal;
	}
</style>
