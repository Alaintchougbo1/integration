<script setup>

</script>

<template>
<div class="bg-grey-lighter min-h-screen flex flex-col h-full">
            <div class="container max-w-sm mx-auto flex-1 flex flex-col items-center justify-center">
                <div class="bg-purple-400 py-10 shadow-md text-black w-full rounded-lg px-20 h-96">
                    <h1 class="mb-8 text-3xl text-center">Sign in</h1>

                    <input 
                        type="text"
                        class="block border border-grey-light w-full p-3 rounded mb-4"
                        name="email"
                        placeholder="Email" />

                    <input 
                        type="password"
                        class="block border border-grey-light w-full p-3 rounded mb-4"
                        name="password"
                        placeholder="Password" />


               
                    <button
                        type="submit"
                        class="w-full text-center py-3 bg-blue-700 text-white hover:bg-green-dark focus:outline-none my-1 rounded-lg"
                    >Sign In</button>
                    <p class="justify">Don’t have account, sign up</p>
                </div>

            </div>
        </div>
</template>

<style scoped>
</style>
