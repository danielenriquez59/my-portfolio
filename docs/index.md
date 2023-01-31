<script setup>
	import { ref } from 'vue';
	const items = ref([
		'List',
		'Something'
	]);
    import CustomComponent from './.vitepress/components/Posts.vue'
</script>

<h2>My Heading</h2>
<ul>
	<li v-for="item in items">{{ item }}</li>
</ul>
<p><CustomComponent /></p>
