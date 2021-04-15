<script>
	// import { createEventDispatcher } from 'svelte';

	// const dispatch = createEventDispatcher();

	// function sayTyKurwoJebana() {
	// 	dispatch('message', {
	// 		text: 'siema kurwo jebana'
	// 	});
	// }
</script>

<button class="baton">
	<slot>Jan papiesz drugi</slot>
</button>

<style lang="scss">
	.baton {
		@include grid-center-padding(15rem);
	}
</style>
