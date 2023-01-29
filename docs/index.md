<script setup>
	import { ref } from 'vue';
	const items = ref([
		'List',
		'Something'
	]);
</script>

<h2>My Heading</h2>
<ul>
	<li v-for="item in items">{{ item }}</li>
</ul>
