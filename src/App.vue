<script setup lang="ts">
	import CardInfo from './shared/components/CardInfo/CardInfo.vue';
</script>

<template>
	<CardInfo
		title="sedans"
		url-image="icon-sedans.svg"
		text="Choose a sedan for its affordability and excellent fuel economy. Ideal for cruising in the city or on your next road trip."
		background-color="bg-orange"
	/>
	<CardInfo
		title="suvs"
		url-image="icon-suvs.svg"
		text="Take an SUV for its spacious interior, power, and versatility. Perfect for your next family vacation and off-road adventures."
		background-color="bg-cyan"
	/>
	<CardInfo
		title="luxury"
		url-image="icon-luxury.svg"
		text="Cruise in the best car brands without the bloated prices. Enjoy the enhanced comfort of a luxury rental and arrive in style."
		background-color="bg-dark-cyan"
	/>
</template>
