<template>
	<div class="tasks">
		<h1>Things to do</h1>
		<TaskList v-bind:tasks="tasks"></TaskList>
	</div>
	
</template>

<script>
	import TaskList from '@/components/TaskList.vue'
	export default {
		name: "tasks",
		components: { TaskList },
		data() {
			return {
				tasks: ["First task", "Second task", "Third task"]
			}
		}
	}
</script>

<style>
	
</style>