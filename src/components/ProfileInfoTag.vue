<template>
	<div class="profile-info-tag-container">
		<div class="grid-container">
			<div class="grid-left-side">
				<a :href="link"> <slot></slot></a>
			</div>

			<div class="grid-right-side">
				<a :href="link"
					><div class="type">{{ type }}</div></a
				>
				<a :href="link"
					><div class="description">{{ description }}</div></a
				>
			</div>
		</div>
	</div>
</template>

<script>
export default {
	props: ["type", "description", "link"],
};
</script>
