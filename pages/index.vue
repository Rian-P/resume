<template>
  <div>
    <index-navbar />
    <section class="animate__animated animate__bounceInLeft animate__delay-2s header relative pt-16 items-center flex h-screen max-h-860-px">
      <div class="container mx-auto items-center flex flex-wrap">
        <div class="w-full md:w-8/12 lg:w-6/12 xl:w-6/12 px-4">
          <div class="pt-32 sm:pt-0">
            <h2 class="font-semibold text-4xl text-blueGray-600">
            Rian pratama
            </h2>
            
            <p class="mt-1 text-lg leading-relaxed text-blueGray-500">
              FrontEnd  Developer 
            </p>
            <p class="mt-4 text-lg leading-relaxed text-blueGray-500">
             Perkenalkan saya seorang lulusan D4 teknik informatika dengan lulus pada tahun 2023.
            </p>
            <div class="mt-12">
              <a href="#lanjutkanSection" target="_blank"
              @click.prevent="scrollToSection('#lanjutkanSection')"  
              class="get-started text-white font-bold px-6 py-4 rounded outline-none focus:outline-none mr-1 mb-1 bg-emerald-500 active:bg-emerald-600 uppercase text-sm shadow hover:shadow-lg ease-linear transition-all duration-150">
                Selanjutnya
              </a>
             
            </div>
          </div>
        </div>
      </div>

      <img class="animate__animated animate__bounceInRight animate__delay-2s absolute top-0 b-auto right-0 pt-16 sm:w-6/12 -mt-48 sm:mt-0 w-10/12 max-h-860-px" :src="patternVue"
        alt="..." />
    </section>

    <section id="lanjutkanSection" class="mt-48 md:mt-40 pb-40 relative bg-blueGray-100">
      <div class="-mt-20 top-0 bottom-auto left-0 right-0 w-full absolute h-20" style="transform: translateZ(0);">
        <svg class="absolute bottom-0 overflow-hidden" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none"
          version="1.1" viewBox="0 0 2560 100" x="0" y="0">
          <polygon class="text-blueGray-100 fill-current" points="2560 0 2560 100 0 100"></polygon>
        </svg>
      </div>
      <div class="container mx-auto">
        <div class="flex flex-wrap items-center">
          <div class="w-10/12 md:w-6/12 lg:w-4/12 px-12 md:px-4 mr-auto ml-auto -mt-32">
            <div
              class="relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-lg rounded-lg bg-emerald-500">
              <img alt="..."
                src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=700&q=80"
                class="w-full align-middle rounded-t-lg" />
              <blockquote class="relative p-8 mb-4">
                <svg preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 583 95"
                  class="absolute left-0 w-full block h-95-px -top-94-px">
                  <polygon points="-30,95 583,95 583,65" class="text-emerald-500 fill-current"></polygon>
                </svg>
                <h4 class="text-xl font-bold text-black">
                  Experience Project
                </h4>
                <p class="text-md font-light mt-7 text-black">
                  pengenalan project yang saya buat. selama perkuliah dengan beberapa yang saya tampilkan.
                </p>
              </blockquote>
            </div>
          </div>

          <div class="w-full md:w-6/12 px-4">
            <div class="flex flex-wrap">
              <div class="w-full md:w-6/12 px-4">
                <div class="relative flex flex-col mt-4">
                  <div class="px-4 py-5 flex-auto">
                    <div
                      class="text-blueGray-500 p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-white">
                      <i class="fas fa-sitemap"></i>
                    </div>
                    <h6 class="text-xl mb-1 font-semibold">
                      Maggang diPT.Sekar Tehno Kreatif
                    </h6>
                    <p class="mb-4 text-blueGray-500">
                      Saya menjalankan maggang selama 4 bulan di PT.Sekar Tehno Kreatif dengan bergerak pada pembuatan website.Dengan posisi Front end mengerjakan rumahpekerja.id.
                    </p>
                  </div>
                </div>
                <div class="relative flex flex-col min-w-0">
                  <div class="px-4 py-5 flex-auto">
                    <div
                      class="text-blueGray-500 p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-white">
                      <i class="fas fa-drafting-compass"></i>
                    </div>
                    <h6 class="text-xl mb-1 font-semibold">
                      Pengabdian Masyarakat
                    </h6>
                    <p class="mb-4 text-blueGray-500">
                      Saya menjalankan pengabdian masyrakat selama 2 bulan dengan melakukan pengajaran pada sekolahan SMP 1 kedungbanteng menjelaskan cara pembuatan vidio dengan pengambilan teknik kamera untuk menghasilkan vidiografer yang sempurna kepada siswa.
                    </p>
                  </div>
                </div>
              </div>
              <div class="w-full md:w-6/12 px-4">
                <div class="relative flex flex-col min-w-0 mt-4">
                  <div class="px-4 py-5 flex-auto">
                    <div
                      class="text-blueGray-500 p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-white">
                      <i class="fas fa-newspaper"></i>
                    </div>
                    <h6 class="text-xl mb-1 font-semibold">Sistem Penyewaan rental mobil berbasis website</h6>
                    <p class="mb-4 text-blueGray-500">
                      saya melakukan pembuatan produk berupa website untuk memenuhi kebutuhan Tugas Akhir dengan penyelesaian permasalahan pada PT Prapatan trans jaya yang tersebut masih menggunakan metode transaksi manual nah dari permasalahan itu saya peralih dengan untuk memudahkan transaksi dan bisa diakses realtime.
                    </p>
                  </div>
                </div>
                <div class="relative flex flex-col min-w-0">
                  <div class="px-4 py-5 flex-auto">
                    <div
                      class="text-blueGray-500 p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-white">
                      <i class="fas fa-file-alt"></i>
                    </div>
                    <h6 class="text-xl mb-1 font-semibold">
                      Pengenalan Plat nomor kendaraan
                    </h6>
                    <p class="mb-4 text-blueGray-500">
                      saya melakukan bersama tim membuat pengenalan Plat nomor kendaraan dengan AI berbasis mobile yang digunakan menggunakan kamera external untuk membaca nomor dan hasilnya akan ditampilkan di mobile berserta keluar masuknya.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="container mx-auto overflow-hidden pb-20">
        <div class="flex flex-wrap items-center">
          <div class="w-full md:w-4/12 px-12 md:px-4 ml-auto mr-auto mt-48">
            <div
              class="text-blueGray-500 p-3 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg rounded-full bg-white">
              <i class="fas fa-sitemap text-xl"></i>
            </div>
            <h3 class="text-3xl mb-2 font-semibold leading-normal">
              SoftKill 
            </h3>
            <p class="text-lg font-light leading-relaxed mt-4 mb-4 text-blueGray-600">
              berikut Softkill penguasaan bahasa program.
            </p>
            <div class="block pb-6">
              <span
                class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-blueGray-500 bg-white uppercase last:mr-0 mr-2 mt-2">
                Laravel
              </span>
              <span
                class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-blueGray-500 bg-white uppercase last:mr-0 mr-2 mt-2">
                Word 
              </span>
              <span
                class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-blueGray-500 bg-white uppercase last:mr-0 mr-2 mt-2">
                Excel
              </span>
              <span
                class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-blueGray-500 bg-white uppercase last:mr-0 mr-2 mt-2">
                Power Point
              </span>
              <span
                class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-blueGray-500 bg-white uppercase last:mr-0 mr-2 mt-2">
                Css-tailwinds
              </span>
              <span
                class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-blueGray-500 bg-white uppercase last:mr-0 mr-2 mt-2">
                Vue.js
              </span>
              <span
                class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-blueGray-500 bg-white uppercase last:mr-0 mr-2 mt-2">
                Css
              </span>
              <span
                class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-blueGray-500 bg-white uppercase last:mr-0 mr-2 mt-2">
                html
              </span>
              <span
                class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-blueGray-500 bg-white uppercase last:mr-0 mr-2 mt-2">
                Pagination
              </span>
              <span
                class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-blueGray-500 bg-white uppercase last:mr-0 mr-2 mt-2">
                Progressbars
              </span>
              <span
                class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-blueGray-500 bg-white uppercase last:mr-0 mr-2 mt-2">
                laravel orchid
              </span>
              <span
                class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-blueGray-500 bg-white uppercase last:mr-0 mr-2 mt-2">
                JavaScript
              </span>
            </div>
            
          </div>

          <div class="w-full md:w-5/12 px-4 mr-auto ml-auto mt-32">
            <div class="relative flex flex-col min-w-0 w-full mb-6 mt-48 md:mt-0">
              <img alt="..." :src="componentBtn"
                class="w-full align-middle rounded absolute shadow-lg max-w-100-px left-145-px -top-29-px z-3" />
              <img alt="..." :src="componentProfileCard"
                class="w-full align-middle rounded-lg absolute shadow-lg max-w-210-px left-260-px -top-160-px" />
              <img alt="..." :src="componentInfoCard"
                class="w-full align-middle rounded-lg absolute shadow-lg max-w-180-px left-40-px -top-225-px z-2" />
              <img alt="..." :src="componentInfo2"
                class="w-full align-middle rounded-lg absolute shadow-2xl max-w-200-px -left-50-px top-25-px" />
              <img alt="..." :src="componentMenu"
                class="w-full align-middle rounded absolute shadow-lg max-w-580-px -left-20-px top-210-px" />
              <img alt="..." :src="componentBtnPink"
                class="w-full align-middle rounded absolute shadow-xl max-w-120-px left-195-px top-95-px" />
            </div>
          </div>
        </div>

        <div class="flex flex-wrap items-center pt-32">
          <div class="w-full md:w-6/12 px-4 mr-auto ml-auto mt-32">
            <div class="justify-center flex flex-wrap relative">
              <div class="my-4 w-full lg:w-6/12 px-4">
                <a href="https://laravel.com/"
                  target="_blank">
                  <div class="bg-red-600 shadow-lg rounded-lg text-center p-8">
                    <img alt="..." class="shadow-md rounded-full max-w-full w-16 mx-auto p-2 bg-white"
                      src="https://laravel.com/img/logomark.min.svg" />
                    <p class="text-lg text-white mt-4 font-semibold">
                      Laravel
                    </p>
                  </div>
                </a>
                <a href="https://tailwindcss.com/"
                  target="_blank">
                  <div class="bg-lightBlue-500 shadow-lg rounded-lg text-center p-8 mt-8">
                    <img alt="..." class="shadow-md rounded-full max-w-full w-16 mx-auto p-2 bg-white"
                      src="data:image/png;base64,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" />
                    <p class="text-lg text-white mt-4 font-semibold">
                      Tailwinds
                    </p>
                  </div>
                </a>
                <a href=""
                  target="_blank">
                  <div class="bg-blueGray-700 shadow-lg rounded-lg text-center p-8 mt-8">
                    <img alt="..." class="shadow-md rounded-full max-w-full w-16 mx-auto p-2 bg-white"
                      src="data:image/png;base64,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" />
                    <p class="text-lg text-white mt-4 font-semibold">
                      Excel
                    </p>
                  </div>
                </a>
              </div>
              <div class="my-4 w-full lg:w-6/12 px-4 lg:mt-16">
                <a href="https://www.creative-tim.com/learning-lab/tailwind/js/alerts/notus?ref=vn-index" target="_blank">
                  <div class="bg-yellow-500 shadow-lg rounded-lg text-center p-8">
                    <img alt="..." class="shadow-md rounded-full max-w-full w-16 mx-auto p-2 bg-white"
                      src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/js.png" />
                    <p class="text-lg text-white mt-4 font-semibold">
                      JavaScript
                    </p>
                  </div>
                </a>
                <a href="https://getbootstrap.com/"
                  target="_blank">
                  <div class="bg-red-700 shadow-lg rounded-lg text-center p-8 mt-8">
                    <img alt="..." class="shadow-md rounded-full max-w-full w-16 mx-auto p-2 bg-white"
                      src="data:image/jpeg;base64,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" />
                    <p class="text-lg text-white mt-4 font-semibold">
                      Bootstrap
                    </p>
                  </div>
                </a>
                <a href="https://www.creative-tim.com/learning-lab/tailwind/vue/alerts/notus?ref=vn-index"
                  target="_blank">
                  <div class="bg-emerald-500 shadow-lg rounded-lg text-center p-8 mt-8">
                    <img alt="..." class="shadow-md rounded-full max-w-full w-16 mx-auto p-2 bg-white"
                      src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/vue.jpg" />
                    <p class="text-lg text-white mt-4 font-semibold">
                      Vue.js
                    </p>
                  </div>
                </a>
              </div>
            </div>
          </div>

          <div class="w-full md:w-4/12 px-12 md:px-4 ml-auto mr-auto mt-48">
            <div
              class="text-blueGray-500 p-3 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg rounded-full bg-white">
              <i class="fas fa-drafting-compass text-xl"></i>
            </div>
            <h3 class="text-3xl mb-2 font-semibold leading-normal">
              Javascript Components
            </h3>
           
            
            <div class="block pb-6">
              <span
                class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-blueGray-500 bg-white uppercase last:mr-0 mr-2 mt-2">
                Alerts
              </span>
              <span
                class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-blueGray-500 bg-white uppercase last:mr-0 mr-2 mt-2">
                Dropdowns
              </span>
              <span
                class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-blueGray-500 bg-white uppercase last:mr-0 mr-2 mt-2">
                Menus
              </span>
              <span
                class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-blueGray-500 bg-white uppercase last:mr-0 mr-2 mt-2">
                Modals
              </span>
              <span
                class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-blueGray-500 bg-white uppercase last:mr-0 mr-2 mt-2">
                Navbars
              </span>
              <span
                class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-blueGray-500 bg-white uppercase last:mr-0 mr-2 mt-2">
                Popovers
              </span>
              <span
                class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-blueGray-500 bg-white uppercase last:mr-0 mr-2 mt-2">
                Tabs
              </span>
              
            </div>
            
          </div>
        </div>
      </div>

      <div class="justify-center text-center flex flex-wrap mt-24">
        <div class="w-full md:w-6/12 px-12 md:px-4">
          <h2 class="font-semibold text-4xl">hasil pengerjaan saya</h2>
          <p class="text-lg leading-relaxed mt-4 mb-4 text-blueGray-500">
            Belajar membuat website sederhana dengan bersama team serta salah satu project maggang.
          </p>
        </div>
      </div>
    </section>

    <section class="block relative z-1 bg-blueGray-600">
      <div class="container mx-auto">
        <div class="justify-center flex flex-wrap">
          <div class="w-full lg:w-12/12 px-4 -mt-24">
            <div class="flex flex-wrap">
              <div class="w-full lg:w-4/12 px-4">
                <h5 class="text-xl font-semibold pb-4 text-center">
                  Login Page
                </h5>
                <a>
                  <div
                    class="hover:-mt-4 relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-lg rounded-lg ease-linear transition-all duration-150">
                    <img alt="..." class="align-middle border-none max-w-full h-auto rounded-lg" :src="login" />
                  </div>
                </a>
              </div>

              <div class="w-full lg:w-4/12 px-4">
                <h5 class="text-xl font-semibold pb-4 text-center">
                  Profile Page
                </h5>
                <router-link to="/profile">
                  <div
                    class="hover:-mt-4 relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-lg rounded-lg ease-linear transition-all duration-150">
                    <img alt="..." class="align-middle border-none max-w-full h-auto rounded-lg" :src="profile" />
                  </div>
                </router-link>
              </div>

              <div class="w-full lg:w-4/12 px-4">
                <h5 class="text-xl font-semibold pb-4 text-center">
                  Landing Page Penyewaan kendaraan
                </h5>
                <router-link to="/landing">
                  <div
                    class="hover:-mt-4 relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-lg rounded-lg ease-linear transition-all duration-150">
                    <img alt="..." class="align-middle border-none max-w-full h-auto rounded-lg" :src="landing" />
                  </div>
                </router-link>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="py-20 bg-blueGray-600 overflow-hidden">
      <div class="container mx-auto pb-64">
        <div class="flex flex-wrap justify-center">
          <div class="w-full md:w-5/12 px-12 md:px-4 ml-auto mr-auto md:mt-64">
            <div
              class="text-blueGray-500 p-3 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg rounded-full bg-white">
              <i class="fas fa-code-branch text-xl"></i>
            </div>
            <h3 class="text-3xl mb-2 font-semibold leading-normal text-white">
              Open Source
            </h3>
            <p class="text-lg font-light leading-relaxed mt-4 mb-4 text-blueGray-400">
              Since
              <a href="https://tailwindcss.com/?ref=creativetim" class="text-blueGray-300" target="_blank">
                Tailwind CSS
              </a>
              is an open source project we wanted to continue this movement too.
              You can give this version a try to feel the design and also test
              the quality of the code!
            </p>
            <p class="text-lg font-light leading-relaxed mt-0 mb-4 text-blueGray-400">
              Get it free on Github and please help us spread the news with a
              Star!
            </p>
            <a href="https://github.com/creativetimofficial/vue-notus?ref=vn-index" target="_blank"
              class="github-star mt-4 inline-block text-white font-bold px-6 py-4 rounded outline-none focus:outline-none mr-1 mb-1 bg-blueGray-700 active:bg-blueGray-600 uppercase text-sm shadow hover:shadow-lg ease-linear transition-all duration-150">
              Github Star
            </a>
          </div>

          <div class="w-full md:w-4/12 px-4 mr-auto ml-auto mt-32 relative">
            <i class="fab fa-github text-blueGray-700 text-55 absolute -top-150-px -right-100 left-auto opacity-80"></i>
          </div>
        </div>
      </div>
    </section>

    <section class="pb-16 bg-blueGray-200 relative pt-32">
      <div class="-mt-20 top-0 bottom-auto left-0 right-0 w-full absolute h-20" style="transform: translateZ(0);">
        <svg class="absolute bottom-0 overflow-hidden" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none"
          version="1.1" viewBox="0 0 2560 100" x="0" y="0">
          <polygon class="text-blueGray-200 fill-current" points="2560 0 2560 100 0 100"></polygon>
        </svg>
      </div>

      <div class="container mx-auto">
        <div class="flex flex-wrap justify-center bg-white shadow-xl rounded-lg -mt-64 py-16 px-12 relative z-10">
          <div class="w-full text-center lg:w-8/12">
            <p class="text-4xl text-center">
              <span role="img" aria-label="love">
                😍
              </span>
            </p>
            <h3 class="font-semibold text-3xl">
              Do you love this Starter Kit?
            </h3>
            <p class="text-blueGray-500 text-lg leading-relaxed mt-4 mb-4">
              Cause if you do, it can be yours now. Hit the buttons below to
              navigate to get the Free version for your next project. Build a
              new web app or give an old project a new look!
            </p>
            <div class="sm:block flex flex-col mt-10">
              <a href="https://www.creative-tim.com/learning-lab/tailwind/vue/overview/notus?ref=vn-index" target="_blank"
                class="get-started text-white font-bold px-6 py-4 rounded outline-none focus:outline-none mr-1 mb-2 bg-emerald-500 active:bg-emerald-600 uppercase text-sm shadow hover:shadow-lg ease-linear transition-all duration-150">
                Get started
              </a>
              <a href="https://github.com/creativetimofficial/vue-notus?ref=vn-index" target="_blank"
                class="github-star sm:ml-1 text-white font-bold px-6 py-4 rounded outline-none focus:outline-none mr-1 mb-1 bg-blueGray-700 active:bg-blueGray-600 uppercase text-sm shadow hover:shadow-lg ease-linear transition-all duration-150">
                <i class="fab fa-github text-lg mr-1"></i>
                <span>Help With a Star</span>
              </a>
            </div>
            <div class="text-center mt-16"></div>
          </div>
        </div>
      </div>
    </section>
    <footer-component />
  </div>
</template>
<script>
import 'animate.css';
import IndexNavbar from "@/components/Navbars/IndexNavbar.vue";
import FooterComponent from "@/components/Footers/Footer.vue";

import patternVue from "@/assets/img/pattern_vue.png";
import componentBtn from "@/assets/img/component-btn.png";
import componentProfileCard from "@/assets/img/component-profile-card.png";
import componentInfoCard from "@/assets/img/component-info-card.png";
import componentInfo2 from "@/assets/img/component-info-2.png";
import componentMenu from "@/assets/img/component-menu.png";
import componentBtnPink from "@/assets/img/component-btn-pink.png";
import documentation from "@/assets/img/documentation.png";
import landing from "@/assets/img/landing.png";
export default {
  name: 'IndexPage',
  data() {
    return {
      patternVue,
      componentBtn,
      componentProfileCard,
      componentInfoCard,
      componentInfo2,
      componentMenu,
      componentBtnPink,
      documentation,
     
      landing,
    };
  },
  components: {
    IndexNavbar,
    FooterComponent,
  },
  methods: {
    scrollToSection(selector) {
      // Scroll to the specified section
      const targetElement = document.querySelector(selector);
      if (targetElement) {
        targetElement.scrollIntoView({ behavior: 'smooth' });
      }
    },
  },
}
</script>
