<template>
	<NcAppContent>
		<div id="gradestracker">
			<h1>Grades Tracker</h1>
		</div>
	</NcAppContent>
</template>

<script>
import NcAppContent from '@nextcloud/vue/dist/Components/NcAppContent.js'

export default {
	name: 'App',
	components: {
		NcAppContent,
	},
}
</script>

<style scoped lang="scss">
#gradestracker {
	display: flex;
	justify-content: center;
	margin: 16px;
}
</style>
