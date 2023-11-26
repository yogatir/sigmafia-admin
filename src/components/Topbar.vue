<script setup>
    import { onMounted, ref } from 'vue';
    import { useRouter } from 'vue-router';

    onMounted(() => {
    });
</script>

<template>
    <header class="z-10 py-4 bg-white shadow-md">
        <div class="container flex items-center justify-between h-full px-6 mx-auto text-sigmafia-orange">
            <div class="flex justify-center flex-1 lg:mr-32">
                <div class="relative w-full max-w-xl mr-6 focus-within:text-sigmafia-orange">
                    <div class="absolute inset-y-0 flex items-center pl-2">
                        <svg class="w-5 h-5" aria-hidden="true" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" stroke="currentColor">
                            <path fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8zM2 8a6 6 0 1110.89 3.476l4.817 4.817a1 1 0 01-1.414 1.414l-4.816-4.816A6 6 0 012 8z" clip-rule="evenodd"></path>
                        </svg>
                    </div>
                    <input class="w-full pl-8 pr-2 text-sm text-gray-700 placeholder-gray-600 bg-gray-100 border-0 rounded-md focus:placeholder-gray-500 focus:bg-white focus:border-sigmafia-orange focus:outline-none focus:shadow-outline-sigmafia-orange form-input" type="text" placeholder="Search" aria-label="Search" />
                </div>
            </div>
            <ul class="flex items-center flex-shrink-0 space-x-6">
                <li class="relative">
                    <button class="align-middle rounded-full focus:shadow-outline-sigmafia-orange focus:outline-none">
                        <img class="object-cover w-8 h-8 rounded-full" src="https://images.unsplash.com/photo-1502378735452-bc7d86632805?ixlib=rb-0.3.5&q=80&fm=jpg&crop=entropy&cs=tinysrgb&w=200&fit=max&s=aa3a807e1bbdfd4364d1f449eaa96d82">
                    </button>
                </li>
            </ul>
        </div>
    </header>
</template>