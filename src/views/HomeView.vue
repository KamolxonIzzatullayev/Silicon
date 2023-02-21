<template>
    <div class="home">
        <HelloWorld msg="Welcome to Your Vue.js App" />
    </div>
    <div class="text-2xl font-bold text-blue-800">
        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Magni,
        accusamus.
    </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
    name: "HomeView",
    components: {
        HelloWorld,
    },
};
</script>
