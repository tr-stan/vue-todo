<template>
	<li> {{description}} </li>
</template>

<script>
	export default {
		name: "task",
		props: ["description"]
	}
</script>