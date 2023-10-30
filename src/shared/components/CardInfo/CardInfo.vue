<script setup lang="ts">
	import './CardInfo.css';
	import ButtonLearnMore from '../ButtonLearnMore/ButtonLearnMore.vue';

	interface Props {
		urlImage: string;
		title: string;
		text: string;
		backgroundColor: string;
	}

	const props = withDefaults(defineProps<Props>(), {
		urlImage: 'icon-luxury.svg',
		title: 'Sedans',
		text: 'Choose a sedan for its affordability and excellent fuel economy. Ideal for cruising in the city or on your next road trip.',
		backgroundColor: 'bg-orange',
	});
</script>
<template>
	<div class="card" :class="[props.backgroundColor]">
		<img :src="`/images/${props.urlImage}`" :alt="`logo of ${props.title}`" />
		<h2>{{ props.title }}</h2>
		<p>{{ props.text }}</p>
		<ButtonLearnMore />
	</div>
</template>
