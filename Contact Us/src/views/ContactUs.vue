<template>
  <body class="font-poppins">
    <nav class="flex items-center justify-between bg-mainColor h-24">
      <div class="logo ml-40">
        <img src="/public/Logo.png" alt="logo" />
      </div>

      <div class="navigations flex items-center mr-40 gap-10">
        <a href="#" class="home text-white no-underline text-base">Home</a>
        <a
          href="#"
          class="text-gray-400 no-underline text-base hover:text-gray-100"
          >About Us</a
        >
        <a
          href="#"
          class="text-gray-400 no-underline text-base hover:text-gray-100"
          >Pricing</a
        >
        <a
          href="#"
          class="text-gray-400 no-underline text-base hover:text-gray-100"
          >Work</a
        >
        <a
          href="#"
          class="text-gray-400 no-underline text-base hover:text-gray-100"
          >Blog</a
        >
        <button
          class="w-[185px] h-[60px] border border-solid border-white/[0.2] text-white bg-mainColor rounded-full transition duration-300 hover:bg-opacity-80"
        >
          Contact Us
        </button>
      </div>
    </nav>

    <section
      class="flex flex-col items-center text-center mt-[130px] font-poppins"
    >
      <h2 class="text-5xl text-fontColor">Contact Us</h2>
      <p class="text-fontColor mt-[16px]">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
        <br />eiusmod tempor incididunt ut labore.
      </p>
    </section>

    <section class="flex justify-center items-center mt-[64px]">
      <div class="grid grid-cols-2 gap-4">
        <div class="flex flex-col">
          <label for="name" class="font-black">Name</label>
          <input
            type="text"
            placeholder="Enter your name "
            class="font-black w-[438px] h-[64px]"
          />
        </div>

        <div class="flex flex-col">
          <label for="subject" class="font-black">Subject</label>
          <input
            type="text"
            placeholder="Provide context"
            class="font-black w-[438px] h-[64px]"
          />
        </div>

        <div class="flex flex-col">
          <label for="email" class="font-black">Email</label>
          <input
            type="text"
            placeholder="Enter your email"
            class="font-black w-[438px] h-[64px]"
          />
        </div>

        <div class="flex flex-col">
          <label for="subject" class="font-black">Subject</label>
          <input
            type="text"
            placeholder="Select subject "
            class="font-black w-[438px] h-[64px]"
          />
        </div>

        <div class="flex flex-col col-span-2">
          <label for="message" class="font-black">Message</label>
          <input
            type="text"
            placeholder="Write your question here"
            class="font-black w-[908px] h-[176px]"
          />
        </div>

        <div class="flex flex-col col-span-2 mb-[128px]">
          <button class="w-[264px] h-[64px]  bg-fontColor text-white rounded-full">Send Messege</button>
        </div>
      </div>
    </section>

    <footer class="bg-mainColor text-white">
      <div class="flex justify-start gap-[140px] ml-[159px] pt-[103px]">
        <div class="mt-10">
          <img src="/public/Logo.png" alt="logo" />
          <p class="text-base mt-4">
            We are always open to discuss your project and <br />
            improve your online presence.
          </p>

          <div
            class="flex justify-start gap-[29px] bg-[#fcd980] text-[#282938] w-[517px] mt-[86px] mb-[92px]"
          >
            <div class="ml-[37px] pt-[17px]">
              <label class="font-medium text-[18px]">Email me at</label>
              <p class="font-normal text-[16px]">contact@website.com</p>
            </div>

            <div class="pt-[17px] mb-[17px]">
              <label class="font-medium text-[18px]">Call us</label>
              <p class="font-normal text-[16px]">0927 6277 28525</p>
            </div>
          </div>
        </div>

        <div class="font-poppins">
          <h2 class="text-4xl font-poppins font-semibold">Let's Talk!</h2>
          <p class="text-base font-light mt-4">
            We are always open to discuss your project, <br />
            improve your online presence and help with your <br />
            UX/UI design challenges.
          </p>

          <div class="flex gap-[26px] mt-4">
            <a href="#"><i class="bx bxl-facebook-circle text-white"></i></a>
            <a href="#"><i class="bx bxl-twitter text-white"></i></a>
            <a href="#"><i class="bx bxl-instagram text-white"></i></a>
            <a href="#"><i class="bx bxl-linkedin-square text-white"></i></a>
          </div>
        </div>
      </div>
    </footer>
  </body>
</template>

<style></style> 
