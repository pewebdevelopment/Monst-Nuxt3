<template>
    <header class="bg-transparent sticky-bar mt-4">
        <div class="container bg-transparent">
            <nav class="bg-transparent flex justify-between items-center py-3">
                <NuxtLink class="text-3xl font-semibold leading-none" to="/monst">
                    <img class="h-10" src="../assets/imgs/logos/monst-logo.svg" alt="" />
                </NuxtLink>
                <ul class="hidden lg:flex lg:items-center lg:w-auto lg:space-x-12">
                    <li class="group relative pt-4 pb-4 has-child">
                        <NuxtLink to="/monst" class="text-sm font-semibold text-blueGray-600 hover:text-blueGray-500">
                            Home</NuxtLink>
                        <ul class="drop-down-menu min-w-200">
                            <li>
                                <NuxtLink to="/monst"
                                    class="menu-sub-item text-sm text-blueGray-600 hover:text-blueGray-500">Landing page
                                    1</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/monst/index-2"
                                    class="menu-sub-item text-sm text-blueGray-600 hover:text-blueGray-500">Landing page
                                    2</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/monst/index-3"
                                    class="menu-sub-item text-sm text-blueGray-600 hover:text-blueGray-500">Landing page
                                    3</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/monst/index-4"
                                    class="menu-sub-item text-sm text-blueGray-600 hover:text-blueGray-500">Landing page
                                    4</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/monst/index-5"
                                    class="menu-sub-item text-sm text-blueGray-600 hover:text-blueGray-500">Landing page
                                    5</NuxtLink>
                            </li>
                        </ul>
                    </li>
                    <li class="pt-4 pb-4">
                        <NuxtLink class="text-sm font-semibold text-blueGray-600 hover:text-blueGray-500"
                            to="/monst/about">About Us</NuxtLink>
                    </li>
                    <li class="pt-4 pb-4">
                        <NuxtLink class="text-sm font-semibold text-blueGray-600 hover:text-blueGray-500"
                            to="/monst/services">Services</NuxtLink>
                    </li>
                    <li class="group relative pt-4 pb-4 has-child">
                        <NuxtLink class="text-sm font-semibold text-blueGray-600 hover:text-blueGray-500"
                            to="/monst/portfolio">
                            Company</NuxtLink>
                        <ul class="drop-down-menu min-w-200">
                            <li>
                                <NuxtLink to="/monst/portfolio"
                                    class="menu-sub-item text-sm text-blueGray-600 hover:text-blueGray-500">Portfolio
                                </NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/monst/team"
                                    class="menu-sub-item text-sm text-blueGray-600 hover:text-blueGray-500">Team
                                </NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/monst/testimonials"
                                    class="menu-sub-item text-sm text-blueGray-600 hover:text-blueGray-500">Testimonials
                                </NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/monst/pricing"
                                    class="menu-sub-item text-sm text-blueGray-600 hover:text-blueGray-500">Pricing
                                </NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/monst/faqs"
                                    class="menu-sub-item text-sm text-blueGray-600 hover:text-blueGray-500">Faqs
                                </NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/monst/404"
                                    class="menu-sub-item text-sm text-blueGray-600 hover:text-blueGray-500">404
                                </NuxtLink>
                            </li>
                        </ul>
                    </li>
                    <li class="group relative pt-4 pb-4 has-child">
                        <NuxtLink class="text-sm font-semibold text-blueGray-600 hover:text-blueGray-500"
                            to="/monst/blog">
                            Blog</NuxtLink>
                        <ul class="drop-down-menu min-w-200">
                            <li>
                                <NuxtLink to="/monst/blog"
                                    class="menu-sub-item text-sm text-blueGray-600 hover:text-blueGray-500">Category
                                    1</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/monst/blog-2"
                                    class="menu-sub-item text-sm text-blueGray-600 hover:text-blueGray-500">Category
                                    2</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/monst/blog-single"
                                    class="menu-sub-item text-sm text-blueGray-600 hover:text-blueGray-500">Single 1
                                </NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/monst/blog-single-2"
                                    class="menu-sub-item text-sm text-blueGray-600 hover:text-blueGray-500">Single 2
                                </NuxtLink>
                            </li>
                        </ul>
                    </li>
                    <li class="pt-4 pb-4">
                        <NuxtLink class="text-sm font-semibold text-blueGray-600 hover:text-blueGray-500"
                            to="/monst/contact">Contact</NuxtLink>
                    </li>
                </ul>
                <div class="hidden lg:block">
                    <NuxtLink class="btn-accent hover-up-2" to="/monst/login">Log In</NuxtLink>
                    <NuxtLink class="btn-primary hover-up-2" to="/monst/signup">Sign Up</NuxtLink>
                </div>
                <div class="lg:hidden">
                    <button
                        class="navbar-burger flex items-center py-2 px-3 text-blue-500 hover:text-blue-700 rounded border border-blue-200 hover:border-blue-300">
                        <svg class="fill-current h-4 w-4" viewbox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                            <title>Mobile menu</title>
                            <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"></path>
                        </svg>
                    </button>
                </div>
            </nav>
        </div>
    </header>
    <div v-if="main">
        <slot />
    </div>
    <div v-if="loader">

        <div id="preloader-active">
            <div class="preloader flex-1 content-center">
                <div class="logo absolute inset-y-2/4 jump">
                    <img src="../assets/imgs/logos/favicon.svg" alt="" />
                    <h1 class="text-lg font-semibold">Monst</h1>
                </div>
            </div>
        </div>
    </div>
    <section class="relative footer-2 border-t border-gray-100">
        <div class="hidden lg:block absolute inset-0 w-1/2 ml-auto bg-blueGray-50"></div>
        <div class="container">
            <div class="relative flex flex-wrap -mx-4">
                <div class="w-full lg:w-1/2 pt-20 px-4 max-w-lg lg:max-w-full mx-auto lg:mx-0 text-center lg:text-left">
                    <NuxtLink
                        class="inline-block mx-auto lg:ml-0 text-3xl font-semibold leading-none wow animate__animated animate__fadeInUp animated"
                        data-wow-delay=".1s" to="/monst/index">
                        <img class="h-10" src="../assets/imgs/logos/monst-logo.svg" alt="" />
                    </NuxtLink>
                    <div class="mt-12 mb-16">
                        <p class="mb-4 text-xs text-blueGray-400 text-center lg:text-left wow animate__animated animate__fadeInUp animated"
                            data-wow-delay=".1s">Subscribe and stay fully connected with product.</p>
                        <div class="flex flex-wrap lg:flex-nowrap items-center wow animate__animated animate__fadeInUp animated"
                            data-wow-delay=".3s">
                            <div class="flex w-full lg:w-2/3 mb-3 lg:mb-0 px-4 bg-blueGray-50 rounded">
                                <svg class="h-6 w-6 my-auto" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20"
                                    fill="currentColor">
                                    <path d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z">
                                    </path>
                                    <path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z"></path>
                                </svg>
                                <input class="w-full py-4 pl-3 text-xs text-blueGray-400 bg-blueGray-50 outline-none"
                                    type="text" placeholder="Type your e-mail" />
                            </div>
                            <button
                                class="hover-up-2 w-full lg:w-auto py-4 px-8 lg:ml-6 text-xs text-white font-semibold leading-none bg-blue-400 hover:bg-blue-500 rounded"
                                type="submit">Sign Up</button>
                        </div>
                    </div>
                    <div class="hidden lg:block wow animate__animated animate__fadeInUp animated" data-wow-delay=".5s">
                        <p class="text-xs text-blueGray-400">&copy; 2021. All rights reserved.</p>
                        <div class="-mx-2 mt-4">
                            <NuxtLink class="inline-block px-2" to="/monst/#">
                                <img src="../assets/imgs/icons/facebook-blue.svg" alt="" />
                            </NuxtLink>
                            <NuxtLink class="inline-block px-2" to="/monst/#">
                                <img src="../assets/imgs/icons/twitter-blue.svg" alt="" />
                            </NuxtLink>
                            <NuxtLink class="inline-block px-2" to="/monst/#">
                                <img src="../assets/imgs/icons/instagram-blue.svg" alt="" />
                            </NuxtLink>
                        </div>
                    </div>
                </div>
                <div class="relative w-full lg:w-1/2 px-4 pt-40 lg:pl-12">
                    <div class="flex flex-row flex-wrap justify-around mb-12">
                        <div class="w-1/2 lg:w-auto mb-12 wow animate__animated animate__fadeInUp animated"
                            data-wow-delay=".1s">
                            <h5 class="mb-6 text-lg font-bold font-heading">About</h5>
                            <ul class="space-y-3">
                                <li>
                                    <NuxtLink class="text-lg text-blueGray-400 hover:text-blueGray-500"
                                        to="/monst/about">About us</NuxtLink>
                                </li>
                                <li>
                                    <NuxtLink class="text-lg text-blueGray-400 hover:text-blueGray-500"
                                        to="/monst/portfolio">Portfolio</NuxtLink>
                                </li>
                                <li>
                                    <NuxtLink class="text-lg text-blueGray-400 hover:text-blueGray-500"
                                        to="/monst/services">Services</NuxtLink>
                                </li>
                                <li>
                                    <NuxtLink class="text-lg text-blueGray-400 hover:text-blueGray-500"
                                        to="/monst/contact">Contact</NuxtLink>
                                </li>
                            </ul>
                        </div>
                        <div class="w-1/2 lg:w-auto mb-12 wow animate__animated animate__fadeInUp animated"
                            data-wow-delay=".3s">
                            <h5 class="mb-6 text-lg font-bold font-heading">Quick links</h5>
                            <ul class="space-y-3">
                                <li>
                                    <NuxtLink class="text-lg text-blueGray-400 hover:text-blueGray-500"
                                        to="/monst/team">Team</NuxtLink>
                                </li>
                                <li>
                                    <NuxtLink class="text-lg text-blueGray-400 hover:text-blueGray-500"
                                        to="/monst/pricing">Pricing</NuxtLink>
                                </li>
                                <li>
                                    <NuxtLink class="text-lg text-blueGray-400 hover:text-blueGray-500"
                                        to="/monst/testimonials">Testimonials</NuxtLink>
                                </li>
                                <li>
                                    <NuxtLink class="text-lg text-blueGray-400 hover:text-blueGray-500"
                                        to="/monst/faqs">Faqs</NuxtLink>
                                </li>
                            </ul>
                        </div>
                        <div class="w-full lg:w-auto mb-4 wow animate__animated animate__fadeInUp animated"
                            data-wow-delay=".5s">
                            <h5 class="mb-6 text-lg font-bold font-heading">Blog</h5>
                            <ul class="space-y-3">
                                <li>
                                    <NuxtLink class="text-lg text-blueGray-400 hover:text-blueGray-500"
                                        to="/monst/blog">Bussiness</NuxtLink>
                                </li>
                                <li>
                                    <NuxtLink class="text-lg text-blueGray-400 hover:text-blueGray-500"
                                        to="/monst/blog-2">Marketing</NuxtLink>
                                </li>
                                <li>
                                    <NuxtLink class="text-lg text-blueGray-400 hover:text-blueGray-500"
                                        to="/monst/blog-single">Single</NuxtLink>
                                </li>
                            </ul>
                        </div>
                    </div>
                    <div class="lg:hidden text-center">
                        <p class="text-xs text-blueGray-400">&copy; 2021. All rights reserved.</p>
                        <div class="-mx-2 mt-4">
                            <NuxtLink class="inline-block px-2" to="/monst/#">
                                <img src="../assets/imgs/icons/facebook-blue.svg" alt="" />
                            </NuxtLink>
                            <NuxtLink class="inline-block px-2" to="/monst/#">
                                <img src="../assets/imgs/icons/twitter-blue.svg" alt="" />
                            </NuxtLink>
                            <NuxtLink class="inline-block px-2" to="/monst/#">
                                <img src="../assets/imgs/icons/instagram-blue.svg" alt="" />
                            </NuxtLink>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script setup>
let loader = ref(true)
let main = ref(false)
setTimeout(() => {
    loader.value = false
    main.value = true
}, 2000)
</script>