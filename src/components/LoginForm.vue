<template>
    <div class="p-6 w-88 border xs:border-[#363636] rounded-xs mb-3">
        <form>
            <div class="flex justify-center mt-2 mb-8">
                <img class="w-64 h-16 m-1 max-w-none object-contain" src="/assets/images/instagram_word.png" />
            </div>
            <div>
                <div class="justify-center mb-2">
                    <input 
                        v-model="username"
                        class="container h-9 p-2 bg-[#121212] text-xs text-white border border-[#555555] rounded-xs focus:outline-none focus:border-[#555555] " 
                        type="text"
                        placeholder="Phone number, username, or email" 
                        required>
                </div>
                <div class="justify-center mb-3 text-white">
                    <input 
                        v-model="password"
                        class="container h-9 mb-1 p-2 bg-[#121212] text-xs text-white border border-[#555555] rounded-xs focus:outline-none focus:border-[#555555]" 
                        type="password"
                        placeholder="Password" 
                        required>
                    </div>
                <div>
                    <button 
                        :disabled="!username || password.length < 6" 
                        class="w-full h-8 flex justify-center items-center rounded-lg text-white bg-[#0095F6] hover:bg-[#1877F2] 
                            disabled:bg-[#0069AD] disabled:text-[#AAAFB3]">
                        <span class="text-sm font-semibold">Log in</span>
                    </button>
                </div>
            </div>
        </form>
        <div class="">
            <div class="relative flex items-center mt-5 mb-6">
                <div class="flex-grow border-t border-[#262626]"></div>
                    <span class="flex-shrink mx-4 text-gray-400 text-[#A8A8A8] font-semibold text-xs">OR</span>
                <div class="flex-grow border-t border-[#262626]"></div>
            </div>
        </div>
        <div class="flex justify-center gap-2 items-center mt-4">
            <img class="h-5" src="/assets/images/facebook.png" alt="">
            <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><span
                    class="text-[#0095F6] hover:text-white text-sm font-semibold">Log in
                    with
                    Facebook</span></a>
        </div>
        <div class="flex justify-center mt-3">
            <a class="text-" href="https://www.instagram.com/accounts/password/reset/"><span
                    class="text-white font-normal text-sm">Forgot
                    password?</span></a>
        </div>
    </div>
</template>

<script setup>
    import { ref } from 'vue';
    const username = ref('');
    const password = ref('');
</script>
