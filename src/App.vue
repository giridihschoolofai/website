<template>
  <div class="font-sans text-black">
    <div class="bg-grey-lighter">
      <header class="border-b">
        <div class="container mx-auto">
          <div class="flex items-center justify-between py-4 px-4 md:px-0">
            <div>
              <a href="#">
                <img
                  class="w-10"
                  src="https://theschool.ai/wp-content/uploads/2018/09/Black_Brain_Icon.png"
                  alt="Logo"
                >
              </a>
            </div>
            <nav>
              <a href="#" class="ml-6 no-underline text-grey-darker hover:text-black">Home</a>
              <a href="#" class="ml-6 no-underline text-grey-darker hover:text-black">Blog</a>
              <a href="#" class="ml-6 no-underline text-grey-darker hover:text-black">Courses</a>
            </nav>
          </div>
        </div>
      </header>
      <div class="py-16">
        <div class="container mx-auto px-4 py-4 md:px-0 bg-no-repeat bg-right" style="background-image: url('./assets/bg.svg'); background-size: 435px;">
          <h1 class="font-semibold leading-normal mb-4">School Of AI
            <br>Valencia
          </h1>
          <h4 class="font-semibold mb-4">Artificial intelligence education group</h4>
          <p class="max-w-sm leading-normal mb-8">We are a non-profit organization born in Silicon Valley that now has more than 800 Deans in more than 400 cities around the world.</p>
          <div class="flex max-w-sm">
            <input type="text" placeholder="Enter your email" class="focus:outline-none border border-transparent border-r-0 focus:border-grey flex-1 p-4 rounded-l">
            <button class="bg-indigo rounded-r text-white px-6">Subscribe</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import "./assets/style.css";

export default {
  name: "app"
};
</script>