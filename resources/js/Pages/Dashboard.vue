<script setup>
import AuthenticatedLayout from '@/Layouts/AuthenticatedLayout.vue';
import { Head } from '@inertiajs/vue3';
</script>

<template>
    <Head title="Dashboard" />

    <AuthenticatedLayout>
        <template #header>
            <h2 class="font-semibold text-xl text-gray-800 leading-tight">Dashboard</h2>
        </template>

        <div class="flex item-center space-x-4 bg-white shadow-xl rounded-lg m-4 p-2">
            <img class="w-40 h-40 rounded-full border-blue-800 border-2" src="src/kavindu-harshana-jpg.jpg"
                alt="Profile Photo">
            <div class="p-4">
                <div class="ml-4  flex item-center">
                    <h2 class="text-xl font-semibold pr-8">John Doe</h2>
                    <button class="bg-blue-500 hover:bg-blue-600 text-white font-bold p-1 rounded">
                        Follow
                    </button>
                </div>
                <div class="flex lg:pt-4 pt-3">
                    <div class="mr-4 p-3 text-center">
                        <span class="text-xl font-bold block uppercase tracking-wide text-blueGray-600">
                            22
                        </span>
                        <span class="text-sm text-blueGray-400">Posts</span>
                    </div>
                    <div class="mr-4 p-3 text-center">
                        <span class="text-xl font-bold block uppercase tracking-wide text-blueGray-600">
                            10
                        </span>
                        <span class="text-sm text-blueGray-400">Followers</span>
                    </div>
                    <div class="lg:mr-4 p-3 text-center">
                        <span class="text-xl font-bold block uppercase tracking-wide text-blueGray-600">
                            89
                        </span>
                        <span class="text-sm text-blueGray-400">Followings</span>
                    </div>
                </div>
                <p class="text-gray-600 p-3">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer gravida, ante
                    consequat consectetur, turpis nunc efficitur tellus.</p>
            </div>
        </div>
        <div class="flex items-center space-x-4 shadow-xl bg-sky-100 rounded-lg m-4 p-2">
            <div class="grid grid-cols-3 gap-4">
                <img class="w-full h-full object-cover" src="src/kavindu-harshana-jpg.jpg" alt="Image 1">
                <img class="w-full h-full object-cover" src="src/kavindu-harshana-jpg.jpg" alt="Image 2">
                <img class="w-full h-full object-cover" src="src/kavindu-harshana-jpg.jpg" alt="Image 3">
                <!-- Add more images here -->
            </div>
        </div>

    </AuthenticatedLayout>
</template>
