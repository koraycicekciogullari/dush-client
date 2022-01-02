<template>
  <div class="container mx-auto">
    <div class="grid gap-4">
      <div>
        <div class="w-full py-4">
          <div class="w-full py-4 px-8 text-white bg-gradient-to-r from-purple-900 via-purple-700 to-purple-900 relative rounded">
            <h3 class="font-semibold">Login Page</h3>
            <icons-trend-icon class="absolute w-14 h-14 top-0 right-2 fill-current z-0 opacity-10" />
          </div>
        </div>
        <article>
          <div>
            <div class="flex items-center justify-center">
              <div class="md:hidden sm:mb-8 mb-6">
                <img src="https://tuk-cdn.s3.amazonaws.com/can-uploader/sign_in_2-svg1.svg" alt="logo">
              </div>
              <div class="bg-white shadow-lg rounded xl:w-1/3 lg:w-5/12 md:w-1/2 w-full lg:px-10 sm:px-6 sm:py-10 px-2 py-6">
                <p tabindex="0" class="focus:outline-none text-2xl font-extrabold leading-6 text-gray-800">Login to your account</p>
                <p tabindex="0" class="focus:outline-none text-sm mt-4 font-medium leading-none text-gray-500">Dont have account? <a href="javascript:void(0)" class="hover:text-gray-500 focus:text-gray-500 focus:outline-none focus:underline hover:underline text-sm font-medium leading-none text-gray-800 cursor-pointer"> Sign up here</a></p>
                <button aria-label="Continue with google" role="button" class="focus:outline-none focus:ring-2 focus:ring-offset-1 focus:ring-gray-700 p-3 border rounded-lg border-gray-700 flex items-center w-full mt-10 hover:bg-gray-100">
                  <img src="https://tuk-cdn.s3.amazonaws.com/can-uploader/sign_in_2-svg2.svg" alt="google">
                  <p class="text-base font-medium ml-4 text-gray-700">Continue with Google</p>
                </button>
                <button aria-label="Continue with github" role="button" class="focus:outline-none focus:ring-2 focus:ring-offset-1 focus:ring-gray-700 p-3 border rounded-lg border-gray-700 flex items-center w-full mt-4 hover:bg-gray-100">
                  <img src="https://tuk-cdn.s3.amazonaws.com/can-uploader/sign_in_2-svg3.svg" alt="github">
                  <p class="text-base font-medium ml-4 text-gray-700">Continue with Github</p>
                </button>
                <button aria-label="Continue with twitter" role="button" class="focus:outline-none focus:ring-2 focus:ring-offset-1 focus:ring-gray-700 p-3 border rounded-lg border-gray-700 flex items-center w-full mt-4 hover:bg-gray-100">
                  <img src="https://tuk-cdn.s3.amazonaws.com/can-uploader/sign_in_2-svg4.svg" alt="twitter">
                  <p class="text-base font-medium ml-4 text-gray-700">Continue with Twitter</p>
                </button>
                <div class="w-full flex items-center justify-between py-5">
                  <hr class="w-full bg-gray-400" />
                  <p class="text-base font-medium leading-4 px-2.5 text-gray-500">OR</p>
                  <hr class="w-full bg-gray-400" />
                </div>
                <div>
                  <label for="email" class="text-sm font-medium leading-none text-gray-800"> Email </label>
                  <input id="email" aria-labelledby="email" type="email" class="bg-gray-200 border rounded text-xs font-medium leading-none placeholder-gray-800 text-gray-800 py-3 w-full pl-3 mt-2" placeholder="e.g: john@gmail.com " />
                </div>
                <div class="mt-6 w-full">
                  <label for="myInput" class="text-sm font-medium leading-none text-gray-800"> Password </label>
                  <div class="relative flex items-center justify-center">
                    <input id="myInput" type="password" class="bg-gray-200 border rounded text-xs font-medium leading-none text-gray-800 py-3 w-full pl-3 mt-2" />
                    <div class="absolute right-0 mt-2 mr-3 cursor-pointer" onclick="showPassword()">
                      <div id="show">
                        <img src="https://tuk-cdn.s3.amazonaws.com/can-uploader/sign_in_2-svg5.svg" alt="eye">
                      </div>
                      <div id="hide" class="hidden">
                        <img src="https://tuk-cdn.s3.amazonaws.com/can-uploader/sign_in_2-svg6.svg" alt="eye">
                      </div>
                    </div>
                  </div>
                </div>
                <div class="mt-8">
                  <button role="button" class="focus:ring-2 focus:ring-offset-2 focus:ring-indigo-700 text-sm font-semibold leading-none text-white focus:outline-none bg-indigo-700 border rounded hover:bg-indigo-600 py-4 w-full">Create my account</button>
                </div>
              </div>
              <div class="xl:w-1/3 md:w-1/2 lg:ml-16 ml-8 md:mt-0 mt-6">
                <div class="pl-8 md:block hidden">
                  <img src="https://tuk-cdn.s3.amazonaws.com/can-uploader/sign_in_2-svg1.svg" alt="logo">
                </div>
                <div class="flex items-start mt-8">
                  <div>
                    <img class="w-24" src="https://tuk-cdn.s3.amazonaws.com/can-uploader/sign_in_2-svg7.svg" alt="quote">
                  </div>
                  <p class="sm:text-2xl text-xl leading-7 text-gray-600 pl-2.5">Generating random paragraphs can be an excellent way for writers to get their creative flow going at the beginning of the day. The writer has no idea what topic the random paragraph will be about when it appears</p>
                </div>
                <div class="flex items-center pl-8 mt-10">
                  <div class="w-8 h-8">
                    <img src="https://i.ibb.co/xLtZCRT/Mask-Group.png" alt="profile picture" class="w-full h-full" />
                  </div>
                  <div class="ml-2">
                    <p class="text-sm font-medium leading-none text-gray-800">Anita Jane</p>
                    <p class="text-sm font-medium leading-none text-gray-600 mt-1 cursor-pointer hover:underline">See profile</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </article>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ContactComponent"
}
</script>
