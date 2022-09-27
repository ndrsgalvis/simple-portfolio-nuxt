<template>
    <header 
    class=" flex bg-gray-50/10 w-full py-5 px-5 top-0 z-10 fixed items-center justify-between backdrop-blur-sm dark:bg-gray-900"
    >
        <nuxt-link to="/">
            <svg 
                class="h-8 w-8 dark:text-light-50" 
                fill="currentColor"
                viewBox="0 0 24 24" 
                xmlns="http://www.w3.org/2000/svg">
                    <path 
                        fill-rule="evenodd"
                        d="m12 0a12 12 0 1 0 12 12 12.013 12.013 0 0 0 -12-12zm0 22a10 10 0 1 1 10-10 10.011 10.011 0 0 1 -10 10zm5-10a1 1 0 0 1 -1 1h-3v3a1 1 0 0 1 -2 0v-3h-3a1 1 0 0 1 0-2h3v-3a1 1 0 0 1 2 0v3h3a1 1 0 0 1 1 1z"
                        clip-rule="evenodd"
                    />
            </svg>
        </nuxt-link>

        <nav class="flex gap-10 items-center">
            <nuxt-link 
            class="font-medium text-lg text-dark-900/50 dark:text-gray-50/80 hover:text-dark-900"
            to="/"
            > Home 
            </nuxt-link>
            <nuxt-link 
            class="font-medium text-lg text-dark-900/50 dark:text-gray-50/80 hover:text-dark-900"
            to="about" 
            >  About
            </nuxt-link>
            <switch-mode/>
        </nav>
    </header>
</template>

