<template>
	<div class="flex h-screen w-screen">
		<div class="w-1/4 bg-red-500">
			<TaskLeftListView></TaskLeftListView>
		</div>
		<div class="w-2/4 bg-pink-500">
			<TaskList></TaskList>
		</div>
		<div class="w-1/4 bg-blue-500">
			<TaskEditer></TaskEditer>
		</div>
	</div>
</template>

<script setup lang="ts">
import TaskList from '../components/task/TaskList.vue'
import TaskEditer from '../components/task/TaskEditer.vue'
import TaskLeftListView from '../components/task/TaskLeftListView.vue'

</script>

<style scoped>

</style>