<template>

<section class="py-20 xl:bg-contain bg-top bg-no-repeat" style="background-image: url('assets/imgs/backgrounds/intersect.svg')">
                <div class="container">
                    <div class="text-center mb-8">
                        <h2 class="max-w-lg mx-auto mb-4 text-4xl font-bold font-heading wow animate__animated animate__fadeInUp animated">
                            <span>Choose Your </span>
                            <br />
                            <span class="text-blue-600">Best</span>
                            <span>Pricing Plan</span>
                        </h2>
                        <p class="max-w-sm mx-auto text-lg text-blueGray-400 wow animate__animated animate__fadeInUp animated" data-wow-delay=".3s">Great Things In Business Are Never Done By One Person</p>
                    </div>
                    <div class="flex flex-wrap sm:justify-center mb-10">
                        <label class="flex items-center mr-8 mb-2 wow animate__animated animate__fadeInUp animated" data-wow-delay=".3s">
                            <input type="radio" name="billing" value="1" />
                            <span class="mx-2 font-semibold">Monthly Billing</span>
                            <span class="inline-flex items-center justify-center w-12 h-10 bg-blue-500 text-white font-semibold rounded">$59</span>
                        </label>
                        <label class="flex items-center mb-2 wow animate__animated animate__fadeInUp animated" data-wow-delay=".5s">
                            <input type="radio" name="billing" value="2" />
                            <span class="mx-2 font-semibold">Annual Billing</span>
                            <span class="inline-flex items-center justify-center w-12 h-10 bg-blue-500 text-white font-semibold rounded">$99</span>
                        </label>
                    </div>
                    <div class="flex flex-wrap bg-white rounded shadow wow animate__animated animate__fadeInUp animated">
                        <div class="w-full md:w-1/2 lg:w-2/5 px-3">
                            <div class="p-8 text-center">
                                <span class="text-blueGray-400">Sign In</span>
                                <h4 class="mb-6 text-2xl">Setup your payment</h4>
                                <div class="flex mb-4 px-4 bg-blueGray-100 rounded">
                                    <input class="w-full py-4 text-xs placeholder-blueGray-400 font-semibold leading-none bg-blueGray-100 outline-none" type="email" placeholder="name@email.com" />
                                    <svg class="h-6 w-6 ml-4 my-auto text-blueGray-300" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 12a4 4 0 10-8 0 4 4 0 008 0zm0 0v1.5a2.5 2.5 0 005 0V12a9 9 0 10-9 9m4.5-1.206a8.959 8.959 0 01-4.5 1.207"></path>
                                    </svg>
                                </div>
                                <div class="flex mb-6 px-4 bg-blueGray-100 rounded">
                                    <input class="w-full py-4 text-xs placeholder-blueGray-400 font-semibold leading-none bg-blueGray-100 outline-none" type="password" placeholder="Enter your password" />
                                    <button class="ml-4">
                                        <svg class="h-6 w-6 my-auto text-blueGray-300" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"></path>
                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M2.458 12C3.732 7.943 7.523 5 12 5c4.478 0 8.268 2.943 9.542 7-1.274 4.057-5.064 7-9.542 7-4.477 0-8.268-2.943-9.542-7z"></path>
                                        </svg>
                                    </button>
                                </div>
                                <div class="text-left mb-5 text-sm text-blueGray-400">
                                    <label>
                                        <input type="checkbox" name="terms" value="1" />
                                        <span class="ml-1">I agree to terms and conditions.</span>
                                    </label>
                                </div>
                                <button class="block w-full p-4 text-center text-xs text-white font-semibold leading-none bg-blue-400 hover:bg-blue-500 rounded">Purchase now</button>
                            </div>
                        </div>
                        <div class="relative w-full md:w-1/2 lg:w-3/5 px-3 bg-blue-500 rounded-r overflow-hidden">
                            <div class="max-w-sm px-12 pt-12">
                                <span class="text-xs text-blue-200">Various Analysis Options</span>
                                <h3 class="mb-4 text-4xl font-bold font-heading text-white">Techno Provides Realtime Best Data Solutions.</h3>
                            </div>
                            <div class="absolute right-0 bottom-0">
                                <div class="flex items-center h-full">
                                    <img class="h-80" src="../../../assets/imgs/illustrations/online-shopping.png" alt="" />
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
</template>