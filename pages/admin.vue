<template>
	<v-container>
		<v-tabs>
			<v-tab to="/admin/videos">Videos</v-tab>
			<!-- <v-tab to="/admin/tags">Tags</v-tab> -->
			<v-tab to="/admin/users">Users</v-tab>
		</v-tabs>

		<NuxtChild />
	</v-container>
</template>

<script>
	export default {
		// middleware: ['auth-admin'],
	}
</script>
