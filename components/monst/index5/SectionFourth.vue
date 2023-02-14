<template>
    <section>
        <div class="container">
            <div class="flex w-full lg:h-full">
                <div class="flex-1 lg:pr-32 py-20 lg:py-16 wow animate__animated animate__fadeInUp"
                    data-wow-delay=".3s">
                    <div class="max-w-2xl px-4 mx-auto lg:ml-0">
                        <h3 class="mb-8 text-4xl font-bold font-heading wow animate__animated animate__fadeInUp">Faqs
                        </h3>

                        <div class="leading-loose text-lg mt-6 wow animate__animated animate__fadeInUp">
                            <template v-for="faq in faqs">
                                <div>
                                    <button
                                        class="w-full font-bold border-b border-gray-200 py-3 flex justify-between items-center mt-4"
                                        x-bind:class="isOpen ? 'text-blue-500' : ''">
                                        <div x-text="faq.question">{{ faq.question }}</div>
                                        <svg v-if="!faq.isOpen" class="fill-current" viewBox="0 0 24 24" width="24"
                                            height="24">
                                            <path class="heroicon-ui"
                                                d="M12 22a10 10 0 110-20 10 10 0 010 20zm0-2a8 8 0 100-16 8 8 0 000 16zm1-9h2a1 1 0 010 2h-2v2a1 1 0 01-2 0v-2H9a1 1 0 010-2h2V9a1 1 0 012 0v2z" />
                                        </svg>
                                        <svg v-if="faq.isOpen" class="fill-current" viewBox="0 0 24 24" width="24"
                                            height="24">
                                            <path class="heroicon-ui"
                                                d="M12 22a10 10 0 110-20 10 10 0 010 20zm0-2a8 8 0 100-16 8 8 0 000 16zm4-8a1 1 0 01-1 1H9a1 1 0 010-2h6a1 1 0 011 1z" />
                                        </svg>
                                    </button>
                                    <div class="text-gray-700 text-sm mt-2" x-text="faq.answer" v-if="faq.isOpen">
                                        {{ faq.answer }}
                                    </div>
                                </div>
                            </template>
                        </div>

                    </div>
                </div>
                <div class="hidden lg:block lg:relative lg:w-1/3 bg-blue-500 wow animate__animated animate__fadeInUp"
                    data-wow-delay=".3s">
                    <div class="absolute left-0 md:-mr-32 mt-24 flex items-center">
                        <img class="jump lg:max-w-lg" src="../../../assets/imgs/illustrations/faqs.svg" alt="" />
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script setup>
const faqs = [
    {
        question: 'Internet Things',
        answer: 'Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature',
        isOpen: true,
    },
    {
        question: 'Artificial Intelligence',
        answer: 'Since 2007 we have been a visionary and a reliable software design engineering partner for world-class brands. We are a boutique digital transformation consultancy.',
        isOpen: false,
    },
    {
        question: 'Cloud Computing',
        answer: 'Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature',
        isOpen: false,
    },
]
</script>