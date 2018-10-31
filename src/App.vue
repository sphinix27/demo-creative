<template>
  <div id="app">
    <nav class="fixed z-50 px-2 py-4 bg-transparent border-transparent w-full" v-scroll="handleScroll">
      <div class="flex items-center justify-between flex-wrap w-3/5 mx-auto">
        <div class="flex items-center justify-between">
          <a class="inline-block py-1 mr-4 text-xl text-grey font-sans font-bold uppercase whitespace-no-wrap no-underline" href="#">Start Bootstrap</a>
        </div>
        <div class="flex items-center justify-between">
          <a class="block items-center uppercase no-underline text-sm font-bold text-grey font-sans py-4 px-2" href="#about">About</a>
          <a class="block items-center uppercase no-underline text-sm font-bold text-grey font-sans py-4 px-2" href="#services">Services</a>
          <a class="block items-center uppercase no-underline text-sm font-bold text-grey font-sans py-4 px-2" href="#portfolio">Portfolio</a>
          <a class="block items-center uppercase no-underline text-sm font-bold text-grey font-sans py-4 px-2" href="#contact">Contact</a>
        </div>
      </div>
    </nav>
    <header class="flex py-0 text-white h-screen min-h-full bg-gray bg-center bg-cover bg-cover-image">
      <div class="container mx-auto my-auto">
        <div class="flex flex-wrap -mx-1">
          <div class="mx-auto w-4/5">
            <h1 class="flex items-center justify-between uppercase font-bold text-5xl text-center">Your Favorite Source of Free Bootstrap Themes</h1>
            <hr class="border-red-light my-6 w-32 border-2 overflow-visible">
          </div>
          <div class="flex flex-col justify-center items-center mx-auto w-3/5">
            <p class="mb-12 text-grey-light text-center text-xl">Start Bootstrap can help you build better websites using the Bootstrap CSS framework! Just download your template and start going, no strings attached!</p>
            <button class="text-center text-base text-white font-bold leading-normal rounded-full bg-red-light px-8 py-4 uppercase no-underline" href="#">Find Out More</button>
          </div>
        </div>
      </div>
    </header>
    <section class="block py-32 bg-red-light" id="about">
      <div class="container px-4 mx-auto">
        <div class="flex flex-wrap -mx-4">
          <div class="flex flex-col items-center justify-center w-2/3 mx-auto text-center">
            <h2 class="mt-0 text-white text-4xl mb-2 font-medium leading-tight">We've got what you need!</h2>
            <hr class="border-white my-6 w-32 border-2 overflow-visible">
            <p class="mb-4 text-grey-light mb-6 mt-0 block text-xl">Start Bootstrap has everything you need to get your new website up and running in no time! All of the templates and themes on Start Bootstrap are open source, free to download, and easy to use. No strings attached!</p>
            <a class="py-4 px-8 border-none font-bold uppercase rounded-full bg-white text-black no-underline inline-block whitespace-no-wrap text-center align-middle" href="#services">Get Started!</a>
          </div>
        </div>
      </div>
    </section>

    <section class="py-20" id="services">
      <div class="container px-4 mx-auto">
        <div class="flex flex-wrap -mx-1">
          <div class="flex flex-col w-full text-center items-center justify-center">
            <h2 class="mt-0 text-3xl mb-2 font-medium leading-tight items-center">At Your Service</h2>
            <hr class="border-red-light my-6 w-32 border-2 overflow-visible">
          </div>
        </div>
      </div>
      <div class="container px-4 mx-auto">
        <div class="flex flex-wrap -mx-1 justify-between items-center">
          <div class="text-center flex max-w-xs flex-no-grow flex-no-shrink relative w-1/4 px-4">
            <div class="max-w-md mx-auto mt-12">
              <svg class="fill-current text-red-light h-12 w-12" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20">
                <path d="M15.3 14.89l2.77 2.77a1 1 0 0 1 0 1.41 1 1 0 0 1-1.41 0l-2.59-2.58A5.99 5.99 0 0 1 11 18V9.04a1 1 0 0 0-2 0V18a5.98 5.98 0 0 1-3.07-1.51l-2.59 2.58a1 1 0 0 1-1.41 0 1 1 0 0 1 0-1.41l2.77-2.77A5.95 5.95 0 0 1 4.07 13H1a1 1 0 1 1 0-2h3V8.41L.93 5.34a1 1 0 0 1 0-1.41 1 1 0 0 1 1.41 0l2.1 2.1h11.12l2.1-2.1a1 1 0 0 1 1.41 0 1 1 0 0 1 0 1.41L16 8.41V11h3a1 1 0 1 1 0 2h-3.07c-.1.67-.32 1.31-.63 1.89zM15 5H5a5 5 0 1 1 10 0z"/>
              </svg>
              <h3 class="mb-4 text-3xl font-light">Sturdy Templates</h3>
              <p class="text-muted mb-0 text-grey-dark my-0">Our templates are updated regularly so they don't break.</p>
            </div>
          </div>
          <div class="text-center flex max-w-xs flex-no-grow flex-no-shrink relative w-1/4 px-4">
            <div class="max-w-md mx-auto mt-12">
              <svg class="fill-current text-red-light h-12 w-12" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20">
                <path d="M16.88 9.1A4 4 0 0 1 16 17H5a5 5 0 0 1-1-9.9V7a3 3 0 0 1 4.52-2.59A4.98 4.98 0 0 1 17 8c0 .38-.04.74-.12 1.1z"/>
              </svg>
              <h3 class="mb-4 text-3xl font-light">Ready to Ship</h3>
              <p class="text-muted mb-0 text-grey-dark my-0">You can use this theme as is, or you can make changes!</p>
            </div>
          </div>
          <div class="text-center flex max-w-xs flex-no-grow flex-no-shrink relative w-1/4 px-4">
            <div class="max-w-md mx-auto mt-12">
              <svg class="fill-current text-red-light h-12 w-12" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20">
                <path d="M4 11H2a2 2 0 0 1-2-2V5c0-1.1.9-2 2-2h2V1h14v10a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4zm0-2V5H2v4h2zm-2 8v-1h18v1l-4 2H6l-4-2z"/>
              </svg>
              <h3 class="mb-4 text-3xl font-light">Up to Date</h3>
              <p class="text-muted mb-0 text-grey-dark my-0">We update dependencies to keep things fresh.</p>
            </div>
          </div>
          <div class="text-center flex max-w-xs flex-no-grow flex-no-shrink relative w-1/4 px-4">
            <div class="max-w-md mx-auto mt-12">
              <svg class="fill-current text-red-light h-12 w-12" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20">
                <path d="M10 20a10 10 0 1 1 0-20 10 10 0 0 1 0 20zm1-5h1a3 3 0 0 0 0-6H7.99a1 1 0 0 1 0-2H14V5h-3V3H9v2H8a3 3 0 1 0 0 6h4a1 1 0 1 1 0 2H6v2h3v2h2v-2z"/>
              </svg>
              <h3 class="mb-4 text-3xl font-light">Made with Love</h3>
              <p class="text-muted mb-0 text-grey-dark my-0">You have to make your websites with love these days!</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="p-0" id="portfolio">
      <div class="p-0 w-full mx-auto block">
        <div class="mx-0 flex flex-wrap">
          <div class="px-0 w-1/3 flex flex-no-grow flex-no-shrink relative">
            <a class="relative block mx-auto my-0 bg-transparent no-underline box" href="./assets/1.jpg">
              <img class="w-full h-auto align-middle border-none image" src="./assets/1.jpg" alt="">
              <div class="image-text w-full h-full text-center bg-red-light flex items-center justify-center">
                <div class="w-full text-center text-white flex flex-col">
                  <div class="text-lg font-semibold uppercase block">
                    Category
                  </div>
                  <div class="py-0 px-4 block text-xl">
                    Project Name
                  </div>
                </div>
              </div>
            </a>
          </div>
          <div class="px-0 w-1/3 flex flex-no-grow flex-no-shrink relative">
            <a class="relative block mx-auto my-0 bg-transparent no-underline box" href="./assets/2.jpg">
              <img class="w-full h-auto align-middle border-none image" src="./assets/2.jpg" alt="">
              <div class="image-text w-full h-full text-center bg-red-light flex items-center justify-center">
                <div class="w-full text-center text-white flex flex-col">
                  <div class="text-lg font-semibold uppercase block">
                    Category
                  </div>
                  <div class="py-0 px-4 block text-xl">
                    Project Name
                  </div>
                </div>
              </div>
            </a>
          </div>
          <div class="px-0 w-1/3 flex flex-no-grow flex-no-shrink relative">
            <a class="relative block mx-auto my-0 bg-transparent no-underline box" href="./assets/3.jpg">
              <img class="w-full h-auto align-middle border-none image" src="./assets/3.jpg" alt="">
              <div class="image-text w-full h-full text-center bg-red-light flex items-center justify-center">
                <div class="w-full text-center text-white flex flex-col">
                  <div class="text-lg font-semibold uppercase block">
                    Category
                  </div>
                  <div class="py-0 px-4 block text-xl">
                    Project Name
                  </div>
                </div>
              </div>
            </a>
          </div>
          <div class="px-0 w-1/3 flex flex-no-grow flex-no-shrink relative">
            <a class="relative block mx-auto my-0 bg-transparent no-underline box" href="./assets/4.jpg">
              <img class="w-full h-auto align-middle border-none image" src="./assets/4.jpg" alt="">
              <div class="image-text w-full h-full text-center bg-red-light flex items-center justify-center">
                <div class="w-full text-center text-white flex flex-col">
                  <div class="text-lg font-semibold uppercase block">
                    Category
                  </div>
                  <div class="py-0 px-4 block text-xl">
                    Project Name
                  </div>
                </div>
              </div>
            </a>
          </div>
          <div class="px-0 w-1/3 flex flex-no-grow flex-no-shrink relative">
            <a class="relative block mx-auto my-0 bg-transparent no-underline box" href="./assets/5.jpg">
              <img class="w-full h-auto align-middle border-none image" src="./assets/5.jpg" alt="">
              <div class="image-text w-full h-full text-center bg-red-light flex items-center justify-center">
                <div class="w-full text-center text-white flex flex-col">
                  <div class="text-lg font-semibold uppercase block">
                    Category
                  </div>
                  <div class="py-0 px-4 block text-xl">
                    Project Name
                  </div>
                </div>
              </div>
            </a>
          </div>
          <div class="px-0 w-1/3 flex flex-no-grow flex-no-shrink relative">
            <a class="relative block mx-auto my-0 bg-transparent no-underline box" href="./assets/6.jpg">
              <img class="w-full h-auto align-middle border-none image" src="./assets/6.jpg" alt="">
              <div class="image-text w-full h-full text-center bg-red-light flex items-center justify-center">
                <div class="w-full text-center text-white flex flex-col">
                  <div class="text-lg font-semibold uppercase block">
                    Category
                  </div>
                  <div class="py-0 px-4 block text-xl">
                    Project Name
                  </div>
                </div>
              </div>
            </a>
          </div>
        </div>
      </div>
    </section>

    <section class="py-20" id="contact">
      <div class="container flex flex-col items-center justify-center w-full mx-auto">
        <div class="flex flex-wrap -mx-4 w-full">
          <div class="mx-auto text-center">
            <h2 class="text-4xl font-light">Let's Get In Touch!</h2>
            <hr class="border-red-light my-6 w-32 border-2 overflow-visible">
            <p class="text-xl text-grey-darker">Ready to start your next project with us? That's great! Give us a call or send us an email and we will get back to you as soon as possible!</p>
          </div>
        </div>
        <div class="flex flex-wrap -mx-4 w-full items-center justify-around">
          <div class="text-center">
            <svg class="h-12 w-12" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20">
              <path d="M20 18.35V19a1 1 0 0 1-1 1h-2A17 17 0 0 1 0 3V1a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v4c0 .56-.31 1.31-.7 1.7L3.16 8.84c1.52 3.6 4.4 6.48 8 8l2.12-2.12c.4-.4 1.15-.71 1.7-.71H19a1 1 0 0 1 .99 1v3.35z"/>
            </svg>
            <p>123-456-6789</p>
          </div>
          <div class="text-center">
            <svg class="h-12 w-12" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20">
              <path d="M18 2a2 2 0 0 1 2 2v12a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V4c0-1.1.9-2 2-2h16zm-4.37 9.1L20 16v-2l-5.12-3.9L20 6V4l-10 8L0 4v2l5.12 4.1L0 14v2l6.37-4.9L10 14l3.63-2.9z"/>
            </svg>
            <p>
              <a class="no-underline text-red-light" href="mailto:your-email@your-domain.com">feedback@startbootstrap.com</a>
            </p>
          </div>
        </div>
      </div>
    </section>
  </div>  
</template>

<script>

export default {
  name: 'app',
  el: '#app',
  directives: {
    scroll: {
      inserted: function(el, binding) {
        let f = function(evt) {
          if (binding.value(evt, el)) {
            window.removeEventListener('scroll', f);
          }
        };
        window.addEventListener('scroll', f);
      }
    }
  },
  methods: {
    handleScroll: function (evt, el) {
      if (window.scrollY > 50) {
        el.setAttribute(
          'style',
          'background-color: white;'
        )
      }
      return window.scrollY > 100
    }
  }
}
</script>

<style>
@tailwind preflight;
@tailwind components;
@tailwind utilities;
.bg-cover-image {
  background-image: url('./assets/header.jpg');
}

.box {
  display: block;
}

.box:hover .image {
  opacity: 0.25;
}

.box:hover .image-text {
  opacity: 0.75;
}

.image-text {
  transition: .5s ease;
  opacity: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  text-align: center;
}
</style>
