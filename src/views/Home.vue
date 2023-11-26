<script setup>
    import Sidebar from '@/components/Sidebar.vue';
    import Topbar from '@/components/Topbar.vue';
</script>

<template>
    <div class="flex h-screen bg-gray-500">
        <Sidebar />
        <div class="flex flex-col flex-1 w-full">
            <Topbar />
            <main class="h-full pb-16 bg-gray-100 overflow-y-auto">
                <div class="container grid px-6 mx-auto">
                    <h2 class="my-6 text-2xl font-semibold text-gray-700">Dashboard</h2>
                    <div class="w-full mb-8 overflow-hidden rounded-lg shadow-xs">
                        <div class="w-full overflow-x-auto">
                            <table class="w-full whitespace-no-wrap">
                                <thead>
                                    <tr class="text-xs font-semibold tracking-wide text-left text-gray-500 uppercase border-b bg-gray-50">
                                        <th class="px-4 py-3">Client</th>
                                        <th class="px-4 py-3">Amount</th>
                                        <th class="px-4 py-3">Status</th>
                                        <th class="px-4 py-3">Date</th>
                                    </tr>
                                </thead>
                                <tbody class="bg-white divide-y">
                                    <tr class="text-gray-700">
                                        <td class="px-4 py-3">
                                            <div class="flex items-center text-sm">
                                                <div class="relative hidden w-8 h-8 mr-3 rounded-full md:block">
                                                    <img class="object-cover w-full h-full rounded-full" src="https://images.unsplash.com/flagged/photo-1570612861542-284f4c12e75f?ixlib=rb-1.2.1&q=80&fm=jpg&crop=entropy&cs=tinysrgb&w=200&fit=max&ixid=eyJhcHBfaWQiOjE3Nzg0fQ">
                                                    <div class="absolute inset-0 rounded-full shadow-inner">
                                                    </div>
                                                </div>
                                                <div>
                                                    <p class="font-semibold">Hans Burger</p>
                                                    <p class="text-xs text-gray-600">10x Developer</p>
                                                </div>
                                            </div>
                                        </td>
                                        <td class="px-4 py-3 text-sm">
                                            $ 863.45
                                        </td>
                                        <td class="px-4 py-3 text-sm">
                                            <span class="px-2 py-1 font-semibold leading-tight text-green-700 bg-green-100 rounded-full">
                                                Approved
                                            </span>
                                        </td>
                                        <td class="px-4 py-3 text-sm">
                                            6/10/2020
                                        </td>
                                    </tr>
                                </tbody>
                            </table>
                        </div>
                        <div class="grid px-4 py-3 text-xs font-semibold tracking-wide text-gray-500 uppercase border-t bg-gray-50 sm:grid-cols-9">
                            <span class="flex items-center col-span-3">
                                Showing 21-30 of 100
                            </span>
                            <span class="col-span-2"></span>
                            <span class="flex col-span-4 mt-2 sm:mt-auto sm:justify-end">
                                <nav aria-label="Table navigation">
                                    <ul class="inline-flex items-center">
                                        <li>
                                            <button class="px-3 py-1 rounded-md rounded-l-lg focus:outline-none focus:shadow-outline-sigmafia-orange">
                                                <svg class="w-4 h-4 fill-current">
                                                    <path d="M12.707 5.293a1 1 0 010 1.414L9.414 10l3.293 3.293a1 1 0 01-1.414 1.414l-4-4a1 1 0 010-1.414l4-4a1 1 0 011.414 0z" clip-rule="evenodd" fill-rule="evenodd"></path>
                                                </svg>
                                            </button>
                                        </li>
                                        <li>
                                            <button class="px-3 py-1 rounded-md focus:outline-none focus:shadow-outline-sigmafia-orange">
                                            </button>
                                        </li>
                                        <li>
                                            <button class="px-3 py-1 rounded-md rounded-l-lg focus:outline-none focus:shadow-outline-sigmafia-orange">
                                                <svg class="w-4 h-4 fill-current">
                                                    <path d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z" clip-rule="evenodd" fill-rule="evenodd"></path>
                                                </svg>
                                            </button>
                                        </li>
                                    </ul>
                                </nav>
                            </span>
                        </div>
                    </div>
                </div>
            </main>
        </div>
    </div>
</template>