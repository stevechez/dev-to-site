<template>
<Navbar />
  <div class="w-full flex flex-col sm:flex-row flex-wrap sm:flex-nowrap py-4 flex-grow">
    <div class="w-fixed w-full flex-shrink flex-grow-0 px-4 ">
        <div class="sticky top-0 p-4 bg-gray-100 rounded-xl w-full h-full">
            <Sidebar />
        </div>
    </div>
    <Content />
    <Rightside />
</div>
<footer class="bg-black mt-auto">
    <div class="p-5 text-white mx-auto">
        <h1 class="text-2xl">Footer</h1>
        <div class="flex">
            <div class="flex-grow flex flex-col">
                <a href="/#home">Boom</a>
                <a href="#">Boom</a>
                <a href="#">Boom</a>
                <a href="#">Boom</a>
            </div>
            <div class="flex-grow flex flex-col">
                <a href="#">Boom</a>
                <a href="#">Boom</a>
                <a href="#">Boom</a>
                <a href="#">Boom</a>
            </div>
            <div class="flex-grow flex flex-col">
                <a href="#">Boom</a>
                <a href="#">Boom</a>
                <a href="#">Boom</a>
            </div>
            <div class="flex-grow flex flex-col">
                <a href="#">Boom</a>
                <a href="#">Boom</a>
                <a href="#">Boom</a>
                <a href="#">Boom</a>
            </div>
        </div>
        <div class="text-right text-xs py-4">
            <a href="">&copy;2021 Someco Inc.</a>
        </div>
    </div>
</footer>
</template>

<script setup>
import Navbar from './Navbar.vue'
import Sidebar from './Sidebar.vue'
import Content from './Content.vue'
import Rightside from './Rightside.vue'
</script>

<style lang="scss" scoped>
@media (min-width: 640px) {
    .w-fixed {
        flex: 0 1 230px;
        min-width: 230px;
    }
}
</style>
