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
              <a href="/" class="ml-6 no-underline text-grey-darker hover:text-black">Home</a>
              <a href="https://medium.com/the-school-of-ai-official" target="_blank" class="ml-6 no-underline text-grey-darker hover:text-black">Blog</a>
              <a href="https://www.theschool.ai/courses/" target="_blank" class="ml-6 no-underline text-grey-darker hover:text-black">Courses</a>
            </nav>
          </div>
        </div>
      </header>
      <div class="py-16">
        <div
          class="container mx-auto px-4 py-4 md:px-0 bg-no-repeat bg-right custom-bg"
        >
          <h1 class="font-semibold leading-normal mb-4">School Of AI
            <br>Giridih
          </h1>
          <h4 class="font-semibold mb-4">Artificial intelligence education group</h4>
          <p
            class="max-w-sm leading-normal mb-8"
          >We are a non-profit organization born in Silicon Valley that now has more than 800 Deans in more than 400 cities around the world.</p>
          <div class="flex max-w-sm">
            <input
              type="text"
              placeholder="Enter your email"
              class="focus:outline-none border border-transparent border-r-0 focus:border-grey flex-1 p-4 rounded-l"
            >
            <button class="bg-indigo rounded-r text-white px-6">Subscribe</button>
          </div>
        </div>
      </div>
    </div>
    <div class="py-12">
      <div class="container mx-auto">
        <h1 class="text-2xl text-center mb-6">Our Mission</h1>
        <div class="flex flex-col lg:flex-row -m-x-12 items-center py-8">
          <div class="lg:w-2/5 px-12 mb-8 lg:mb-0">
            <img src="./assets/education.svg">
          </div>
          <div class="lg:w-3/5 text-md px-6 lg:px-12">
            <h2 class="mb-4 text-3xl">
              We want to spread the artificial intelligence and its applications, globally and free of charge.
            </h2>
            <div class="leading-normal">
              <p>Our doors are open to all those who wish to learn. We are a learning community that covers almost all countries.</p>
              <p>We are dedicated to teaching our students how to make a positive impact in the world using AI technology, either through employment or entrepreneurship.</p>
              <p>We propose to organize, free of charge, classes and lectures on artificial intelligence and its practical applications.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="bg-grey-lighter py-8">
      <div class="container mx-auto">
        <h1 class="text-2xl text-center mb-8">Find our events</h1>
        <div class="flex justify-center">
          <a href="https://www.facebook.com/groups/giridihschoolofai/" target="_blank" class="flex items-center bg-white p-4 rounded shadow mr-2 min-w-sm">
            <img class="block w-8" src="./assets/facebook.svg" alt="">
          </a>
        </div>
      </div>
    </div>
    <div class="py-16">
      <div class="container mx-auto">
        <div class="flex flex-col-reverse lg:flex-row mb-20">
          <div class="lg:w-3/5 px-4 py-2 leading-normal">
            <h2 class="mb-2">Talks</h2>
            <p>Each month we organize a talk where we explain a theoretical concept and a practical application.</p>
            <p>We want all of us to be participants. Would you like to talk about a particular topic or your experience with Artificial Intelligence?</p>
            <p><a href="#" class="no-underline text-indigo hover:underline">Want to be a speaker?</a></p>
          </div>
          <div class="lg:w-2/5 text-center mb-6 lg:mb-0">
            <img class="w-48" src="./assets/talks.svg" alt="">
          </div>
        </div>
        <div class="flex flex-col-reverse lg:flex-row-reverse mb-20">
          <div class="lg:w-3/5 px-4 py-2 leading-normal">
            <h2 class="mb-2">Hackatons</h2>
            <p>We believe that artificial intelligence can help improve the way of living and facilitate our daily tasks. That's why we offer fellowships collaborating with big companies to participate in interesting projects where to use artificial intelligence.</p>
          </div>
          <div class="lg:w-2/5 text-center mb-6 lg:mb-0">
            <img class="w-48" src="./assets/hackathon.svg" alt="">
          </div>
        </div>
        <div class="flex flex-col-reverse lg:flex-row">
          <div class="lg:w-3/5 px-4 py-2 leading-normal">
            <h2 class="mb-2">Courses</h2>
            <p>We already have three courses (link to the courses), the three free ones, one is like a challenge, where every day a new app is programmed, while the second is about how to develop decentralized applications and the terzero is about data science, basic level.</p>
            <p><a href="#" class="no-underline text-indigo hover:underline">Do you have any ideas to develop our own course in person? Let us know!</a></p>
          </div>
          <div class="lg:w-2/5 text-center mb-6 lg:mb-0">
            <img class="w-48" src="./assets/courses.svg" alt="">
          </div>
        </div>
      </div>
    </div>
    <div class="bg-grey-lighter text-center py-4">
      Giridih School Of AI
    </div>
  </div>
</template>

<script>
import "./assets/style.css";

export default {
  name: "app"
};
</script>

<style>
.custom-bg {
  background-image: url('./assets/bg.svg'); 
  background-size: 435px;
}

@media screen and (max-width: 800px){
  .custom-bg {
    background-image: url('./assets/bg.svg'); 
    background-size: 0;
  }
}
</style>
