<template>
	<div class="max-w-screen-lg mx-auto md:px-20 xl:px-0">
		<slot />
	</div>
</template>

<script lang="ts">
import { Vue, Component } from 'nuxt-property-decorator';

@Component
export default class LandifyBlockTemplate extends Vue {}
</script>
