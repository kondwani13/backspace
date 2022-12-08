<template>
  
  <Header />
<div class="relative lg:px-28 px-4  container mx-auto grid sm:grid-cols-1 md:grid-cols-2 lg:grid-cols-2 xl:grid-cols-2 pt-16 lg:pt-36 gap-8">
            <div class="text-color -mt-6">
                <h1 class="lg:text-7xl text-6x1 lg:w-1/2 xl:w-full xl:text-8xl font-black f-f-l">Optimal. Durable. Efficient.</h1>
                <div class="f-f-r -mt-4 text-xl lg:text-3xl pb-20 sm:pb-0 pt-10 xl:pt-20">
                    <h2>Are you tired of using a slow PC?</h2>
                    <h2>We would like to give you a PC hardware upgrade.</h2>
                    <h2>Or better yet offer you a deal for a high end machine.</h2>
                </div>
                
            </div>
            <div class="">
                <img class="w-full -mt-8 lg:-ml-16 xl:-ml-44" src="https://i.ibb.co/tsB09wS/de3.png" alt="" />
                <button class="hover:opacity-90 text-xl w-full rounded-lg xl:text-3xl xl:w-10/12 mt-4 xl:mt-11 f-f-r py-6 bg-indigo-700 text-white text-bold">Our services</button>
            </div>
        </div>

        <Services />
        <div class="-mt-8 lg:px-28 px-8">
    
   <p class="">     We are skilled in working with all operating systems and makes of computers. Whether you own a desktop, laptop, iMac, MacBook, all-in-one or touchscreen we can repair your machines software & hardware. <br> Is your computer suffering from :</p>
  </div>
        <div class="flex justify-center py-8">
        <div class="inline-grid grid-cols-1 gap-4 ">
        
  <div class="flex">
   <img class="w-4" src="https://i.ibb.co/N7KygVJ/go.png"  alt="go" >
   <p class="">Slow Running Computer</p>
  </div>
  <div class="flex">
    <img class="w-4" src="https://i.ibb.co/N7KygVJ/go.png"  alt="go" >
   <p class="">Computer wont turn on</p>
  </div>
  <div class="flex text-center">
    <img class="w-4" src="https://i.ibb.co/N7KygVJ/go.png"  alt="go" >
   <p class="">Computer randomly freezes</p>
  </div>
  <div class="flex text-center">
    <img class="w-4" src="https://i.ibb.co/N7KygVJ/go.png"  alt="go" >
   <p class="">Can not connect to internet</p>
  </div>
  <div class="flex text-center">
    <img class="w-4" src="https://i.ibb.co/N7KygVJ/go.png"  alt="go" >
   <p class="">Reinstall operating system</p>
  </div>
  <div class="flex text-center">
    <img class="w-4" src="https://i.ibb.co/N7KygVJ/go.png"  alt="go" >
   <p class="">Virus removal</p>
  </div>
  <div class="flex text-center">
    <img class="w-4" src="https://i.ibb.co/N7KygVJ/go.png"  alt="go" >
   <p class="">Spyware removal</p>
  </div>
  <div class="flex text-center">
    <img class="w-4" src="https://i.ibb.co/N7KygVJ/go.png"  alt="go" >
   <p class="">Malware removal</p>
  </div>
  <div class="flex text-center">
    <img class="w-4" src="https://i.ibb.co/N7KygVJ/go.png"  alt="go" >
   <p class="">Screen repair</p>
  </div>
  <div class="flex text-center">
    <img class="w-4" src="https://i.ibb.co/N7KygVJ/go.png"  alt="go" >
   <p class="">Software problems</p>
  </div>
  <div class="flex text-center">
    <img class="w-4" src="https://i.ibb.co/N7KygVJ/go.png"  alt="go" >
   <p class="">Mouse/keyboard/accesory problems</p>
  </div>


  </div>

  
  
</div>
<div class="flex flex-col justify-center items-center pt-6">
<img class="w-64 " src="https://i.ibb.co/vqzXRV9/de4.png" alt="de4" >
</div>
  <Footer />
</template>

<script>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
import Services from './components/Services.vue'

export default {
  name: 'App',
  components: {
    Header,
    Footer,
    Services
  }
}
</script>


