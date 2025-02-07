<template>
    <div class="w-88 mb-2">
        <div class="rounded-xs border border-[#363636] pt-2 pl-10 pr-10 pb-5 mb-2 ">
            <form>
                <div class="flex justify-center mt-7 mb-6">
                    <img class="h-16" src="/assets/images/Instagram_word.png" />
                </div>
                <div class="justify-center border border-[#555555] rounded-xs mb-2">
                    <input class="container h-9 p-2 bg-[#121212] text-xs text-white" type="text"
                        placeholder="Phone number, username, or email" required>
                </div>
                <div class="justify-center border border-[#555555] rounded-xs mb-3 text-white">
                    <input class="container h-9 p-2 bg-[#121212] text-xs" type="password" placeholder="Password" required>
                </div>
                <div class="">
                    <button class="w-full h-8 flex justify-center items-center rounded text-white">
                        <span class="text-sm">Log in</span>
                    </button>
                </div>
            </form>
            <div class="relative flex items-center mt-5 mb-6">
                <div class="flex-grow border-t border-[#262626]"></div>
                <span class="flex-shrink mx-4 text-gray-400 text-[#A8A8A8] font-semibold text-sm">OR</span>
                <div class="flex-grow border-t border-[#262626]"></div>
            </div>
            <div class="flex justify-center gap-2 items-center mt-4">
                <img class="h-5" src="/assets/images/facebook.png" alt="">
                <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><span
                        class="text-[#0095F6] hover:text-white text-sm">Login in
                        with
                        Facebook</span></a>
            </div>
            <div class="flex justify-center mt-4">
                <a class="text-" href="https://www.instagram.com/accounts/password/reset/"><span
                        class="text-white font-normal text-sm">Forgot
                        password?</span></a>
            </div>
        </div>


        <div class="flex justify-center border border-[#363636] p-5">
            <span class="text-sm text-white">Don't have an account? <a
                    href="https://www.instagram.com/accounts/emailsignup/"><span class="text-[#0095F6] text-sm">Sign
                        Up</span></a></span>

        </div>
        <div>
            <div class="m-3 flex justify-center">
                <span class="text-sm text-white">Get the app.</span>
            </div>

            <div class="flex justify-center gap-2">
                <div>
                    <a href="https://play.google.com/store/apps/details?id=com.instagram.android"><img class="h-10"
                            src="/assets/images/google_play.png" alt=""></a>
                </div>
                <div>
                    <a href="ms-windows-store://pdp/?productid=9nblggh5l9xt&referrer=appbadge&source=www.instagram.com&mode=mini&pos=2560%2C0%2C1920%2C1032"
                        alt=""><img class="h-10" src="/assets/images/microsoft.png"></a>

                </div>
            </div>
        </div>
    </div>
</template>