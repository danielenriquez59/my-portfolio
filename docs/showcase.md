<!-- // page1_v2 -->

<script setup>
    import { ref } from 'vue'
    import PostCards from './.vitepress/components/Posts.vue'
    const image1 = ref("./public/images/talyn-lift.png")
    const image2 = ref("./public/images/talyn-lift.png")
    const image3 = ref("./public/images/talyn-lift.png")
    const string1 = ref("This is a test1")
    const string2 = ref("This is a test2")
    const string3 = ref("This is a test3")

</script>


# Showcase
Here are is a showcase of previous projects I have worked on.  
- - - -

<PostCards 
:image1="image1" :image2="image2" :image3="image3" 
:string1="string1" :string2="string2" :string3="string3"
/>