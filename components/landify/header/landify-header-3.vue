<template>
	<div class="flex h-20 bg-transparent justify-between">
		<landify-icon />
		<div class="font-bold justify-self-center self-center space-x-8">
			<n-link tag="a" :to="'/'">
				About
			</n-link>
			<n-link tag="a" :to="'/'">
				Services
			</n-link>
			<n-link tag="a" :to="'/'">
				Blog
			</n-link>
			<n-link tag="a" :to="'/'">
				Jobs
			</n-link>
			<n-link tag="a" :to="'/'">
				Contact
			</n-link>
		</div>
	</div>
</template>

<script lang="ts">
import { Vue, Component } from 'nuxt-property-decorator';

@Component
export default class LandifyHeader3 extends Vue {}
</script>
