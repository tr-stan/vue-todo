<template>
	<ul>
		<Task v-for="task in tasks" v-bind:description="task"></Task>
	</ul>
</template>

<script>
	import Task from '@/components/Task'
	export default {
		name: "TaskList",
		props: ["tasks"],
		components: { Task }
	}
</script>