<template>
	<view>
		<view>{{username}}</view>
		<view v-for="tel in tels">{{tel}}</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				username: "pearz",
				tels:['18254777274', '19963145067']
			}
		},
		methods: {

		}
	}
</script>

<style>

</style>
