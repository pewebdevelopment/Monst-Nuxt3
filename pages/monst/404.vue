<template>
    <section class="pt-20 pb-32">
        <div class="container text-center">
            <img class="mb-4 mx-auto md:max-w-md mb-12 wow animate__animated animate__fadeIn"
                src="../../assets/imgs/illustrations/error2.png" alt="" />
            <span class="text-4xl text-blue-500 font-bold font-heading wow animate__animated animate__fadeIn"
                data-wow-delay=".2s">Error 404</span>
            <h2 class="mb-2 text-4xl font-bold font-heading wow animate__animated animate__fadeIn" data-wow-delay=".3s">
                Something went wrong!</h2>
            <p class="mb-6 text-blueGray-400 wow animate__animated animate__fadeInUp" data-wow-delay=".4s">Sorry, but we
                are unable to open this page.</p>
            <div>
                <NuxtLink class="block sm:inline-block py-4 px-8 mb-4 sm:mb-0 sm:mr-3 text-xs text-white text-center font-semibold leading-none bg-blue-400 hover:bg-blue-500 rounded wow animate__animated animate__fadeInUp"
                    data-wow-delay=".5s" to="/monst">Go back to Homepage</NuxtLink>
                <NuxtLink class="block sm:inline-block py-4 px-8 text-xs text-blueGray-500 hover:text-blueGray-800 text-center font-semibold leading-none bg-blueGray-50 hover:bg-blueGray-100 rounded wow animate__animated animate__fadeInUp"
                    data-wow-delay=".6s" to="/monst/contact">Contact Us</NuxtLink>
            </div>
        </div>
    </section>
</template>


<script setup>
definePageMeta({
    layout: 'monst'
})
</script>