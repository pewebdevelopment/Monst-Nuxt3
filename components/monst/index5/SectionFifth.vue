<template>
     <section class="py-20">
                <div class="container">
                    <div class="max-w-2xl mx-auto text-center">
                        <div class="max-w-md mb-8 mx-auto">
                            <span class="text-sm text-blueGray-400 wow animate__animated animate__fadeInUp" data-wow-delay=".1s">Contact Us</span>
                            <h2 class="mt-2 text-4xl font-bold font-heading wow animate__animated animate__fadeInUp" data-wow-delay=".3s">We will <span class="text-blue-500">be glad</span> to hear from you!</h2>
                        </div>
                        <div>
                            <form>
                                <div class="mb-4 text-sm wow animate__animated animate__fadeInUp" data-wow-delay=".5s">
                                    <span class="mr-4 font-semibold">Departament:</span>
                                    <label class="mr-4">
                                        <input class="mr-1" type="radio" name="department" value="1" checked=false />
                                        <span>Support</span>
                                    </label>
                                    <label>
                                        <input class="mr-1" type="radio" name="department" value="2" />
                                        <span>Sales</span>
                                    </label>
                                </div>
                                <div class="mb-4 wow animate__animated animate__fadeInUp" data-wow-delay=".3s">
                                    <input class="w-full p-4 text-xs font-semibold leading-none bg-blueGray-50 rounded outline-none" type="text" placeholder="Subject" />
                                </div>
                                <div class="mb-4 wow animate__animated animate__fadeInUp" data-wow-delay=".3s">
                                    <input class="w-full p-4 text-xs font-semibold leading-none bg-blueGray-50 rounded outline-none" type="text" placeholder="Name" />
                                </div>
                                <div class="mb-4 wow animate__animated animate__fadeInUp" data-wow-delay=".3s">
                                    <input class="w-full p-4 text-xs font-semibold leading-none bg-blueGray-50 rounded outline-none" type="email" placeholder="name@example.com" />
                                </div>
                                <div class="mb-4 wow animate__animated animate__fadeInUp" data-wow-delay=".3s">
                                    <textarea class="w-full h-24 p-4 text-xs font-semibold leading-none resize-none bg-blueGray-50 rounded outline-none" placeholder="Message..."></textarea>
                                </div>
                                <div class="mb-4 wow animate__animated animate__fadeInUp" data-wow-delay=".3s">
                                    <label class="flex px-2 bg-blueGray-50 rounded">
                                        <input class="hidden" type="file" name="Choose file" />
                                        <span class="my-1 ml-auto px-4 py-3 text-xs text-white font-semibold leading-none bg-blueGray-500 hover:bg-blueGray-600 rounded cursor-pointer"> Browse</span>
                                    </label>
                                </div>
                                <div class="flex justify-between items-center wow animate__animated animate__fadeInUp" data-wow-delay=".3s">
                                    <label>
                                        <input class="mr-1" type="checkbox" name="terms" value="1" />
                                        <span class="text-sm font-semibold">I agree to terms and conditions.</span>
                                    </label>
                                    <button class="py-4 px-8 text-sm text-white font-semibold leading-none bg-blue-500 hover:bg-blue-700 rounded" type="submit">Submit</button>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
            </section>
</template>