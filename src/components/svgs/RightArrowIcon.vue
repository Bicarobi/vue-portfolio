<template>
	<div>
		<svg viewBox="0 0 320 512">
			<path d="M310.6 233.4c12.5 12.5 12.5 32.8 0 45.3l-192 192c-12.5 12.5-32.8 12.5-45.3 0s-12.5-32.8 0-45.3L242.7 256 73.4 86.6c-12.5-12.5-12.5-32.8 0-45.3s32.8-12.5 45.3 0l192 192z" />
		</svg>
	</div>
</template>

<script>
export default {
	name: "RightArrowIcon",
};
</script>

<style scoped>
div {
	line-height: 0;

	position: fixed;
	top: 50%;
	right: 5%;
}

svg {
	height: var(--icon-size2);
	cursor: pointer;
}

path {
	fill: var(--color2);
}
</style>
