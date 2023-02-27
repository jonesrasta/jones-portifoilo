<script>
export default {
  setup() {
    let Links = [
      { name: "Services", link: "#" },
      { name: "Projects", link: "#" },
      { name: "Contacts", link: "#" },
    ];
    return { Links, open };
  },
};
</script>

<template>
  <div
    class="flex justify-between items-center text-gray-100 py-6 hover:text-gray-100 focus:text-gray-700 shadow-lg"
  >

    <button
      class="navbar-toggler md:hidden absolute py-2 pl-6"
      type="button"
      data-bs-toggle="collapse"
      data-bs-target="#navbarSupportedContent"
      aria-controls="navbarSupportedContent"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <svg
        aria-hidden="true"
        focusable="false"
        data-prefix="fas"
        data-icon="bars"
        class="w-6"
        role="img"
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 448 512"
      >
        <path
          fill="currentColor"
          d="M16 132h416c8.837 0 16-7.163 16-16V76c0-8.837-7.163-16-16-16H16C7.163 60 0 67.163 0 76v40c0 8.837 7.163 16 16 16zm0 160h416c8.837 0 16-7.163 16-16v-40c0-8.837-7.163-16-16-16H16c-8.837 0-16 7.163-16 16v40c0 8.837 7.163 16 16 16zm0 160h416c8.837 0 16-7.163 16-16v-40c0-8.837-7.163-16-16-16H16c-8.837 0-16 7.163-16 16v40c0 8.837 7.163 16 16 16z"
        ></path>
      </svg>
    </button>
    <div class="mb-4 mx-28 ">
        <img
        src="/src/assets/logo.svg"
        alt="Avatar"
      >
      </div>
    <div class="flex justify-end px-4">

      <a
        href="https://www.linkedin.com/in/joneslima"
        target="blank"
        type="button"
        class="text-white leading-normal uppercase hover:[color:#6FF1A6] focus:outline-none focus:ring-0 transition duration-150 ease-in-out w-7 h-9 m-1"
      >
        <svg
          aria-hidden="true"
          focusable="false"
          data-prefix="fab"
          data-icon="linkedin-in"
          class="w-6 h-full mx-auto"
          role="img"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 448 512"
        >
          <path
            fill="currentColor"
            d="M100.28 448H7.4V148.9h92.88zM53.79 108.1C24.09 108.1 0 83.5 0 53.8a53.79 53.79 0 0 1 107.58 0c0 29.7-24.1 54.3-53.79 54.3zM447.9 448h-92.68V302.4c0-34.7-.7-79.2-48.29-79.2-48.29 0-55.69 37.7-55.69 76.7V448h-92.78V148.9h89.08v40.8h1.3c12.4-23.5 42.69-48.3 87.88-48.3 94 0 111.28 61.9 111.28 142.3V448z"
          ></path>
        </svg>
      </a>
      <a
        href="https://github.com/jonesrasta"
        target="blank"
        type="button"
        class="text-white leading-normal uppercase hover:[color:#6FF1A6] focus:outline-none focus:ring-0 transition duration-150 ease-in-out w-7 h-9 m-1"
      >
        <svg
          aria-hidden="true"
          focusable="false"
          data-prefix="fab"
          data-icon="github"
          class="w-6 h-full mx-auto"
          role="img"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 576 512"
        >
          <path
            fill="currentColor"
            d="M165.9 397.4c0 2-2.3 3.6-5.2 3.6-3.3.3-5.6-1.3-5.6-3.6 0-2 2.3-3.6 5.2-3.6 3-.3 5.6 1.3 5.6 3.6zm-31.1-4.5c-.7 2 1.3 4.3 4.3 4.9 2.6 1 5.6 0 6.2-2s-1.3-4.3-4.3-5.2c-2.6-.7-5.5.3-6.2 2.3zm44.2-1.7c-2.9.7-4.9 2.6-4.6 4.9.3 2 2.9 3.3 5.9 2.6 2.9-.7 4.9-2.6 4.6-4.6-.3-1.9-3-3.2-5.9-2.9zM244.8 8C106.1 8 0 113.3 0 252c0 110.9 69.8 205.8 169.5 239.2 12.8 2.3 17.3-5.6 17.3-12.1 0-6.2-.3-40.4-.3-61.4 0 0-70 15-84.7-29.8 0 0-11.4-29.1-27.8-36.6 0 0-22.9-15.7 1.6-15.4 0 0 24.9 2 38.6 25.8 21.9 38.6 58.6 27.5 72.9 20.9 2.3-16 8.8-27.1 16-33.7-55.9-6.2-112.3-14.3-112.3-110.5 0-27.5 7.6-41.3 23.6-58.9-2.6-6.5-11.1-33.3 2.6-67.9 20.9-6.5 69 27 69 27 20-5.6 41.5-8.5 62.8-8.5s42.8 2.9 62.8 8.5c0 0 48.1-33.6 69-27 13.7 34.7 5.2 61.4 2.6 67.9 16 17.7 25.8 31.5 25.8 58.9 0 96.5-58.9 104.2-114.8 110.5 9.2 7.9 17 22.9 17 46.4 0 33.7-.3 75.4-.3 83.6 0 6.5 4.6 14.4 17.3 12.1C428.2 457.8 496 362.9 496 252 496 113.3 383.5 8 244.8 8zM97.2 352.9c-1.3 1-1 3.3.7 5.2 1.6 1.6 3.9 2.3 5.2 1 1.3-1 1-3.3-.7-5.2-1.6-1.6-3.9-2.3-5.2-1zm-10.8-8.1c-.7 1.3.3 2.9 2.3 3.9 1.6 1 3.6.7 4.3-.7.7-1.3-.3-2.9-2.3-3.9-2-.6-3.6-.3-4.3.7zm32.4 35.6c-1.6 1.3-1 4.3 1.3 6.2 2.3 2.3 5.2 2.6 6.5 1 1.3-1.3.7-4.3-1.3-6.2-2.2-2.3-5.2-2.6-6.5-1zm-11.4-14.7c-1.6 1-1.6 3.6 0 5.9 1.6 2.3 4.3 3.3 5.6 2.3 1.6-1.3 1.6-3.9 0-6.2-1.4-2.3-4-3.3-5.6-2z"
          ></path>
        </svg>
      </a>
      <a
        href="https://mail.google.com/"
        target="blank"
        type="button"
        class="text-white leading-normal uppercase hover:[color:#6FF1A6] focus:outline-none focus:ring-0 transition duration-150 ease-in-out w-7 h-9 m-1"
      >
        <svg
          aria-hidden="true"
          focusable="false"
          data-prefix="fab"
          data-icon="github"
          class="w-6 h-full mx-auto"
          role="img"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 96 73"
        >
          <path
            fill="currentColor"
            d="M73.8522 7.3341L79.8844 2.79582C86.2775 -2.0126 95.3958 2.5635 95.3958 10.5757V19.2201V65.6834C95.3958 69.2654 92.5035 72.1667 88.9327 72.1667H73.8522V35.4282L48 54.878L22.1478 35.4282V72.1667H7.06731C3.49647 72.1667 0.604248 69.2654 0.604248 65.6834V19.2201V10.5757C0.604248 2.5635 9.72255 -2.0126 16.1156 2.79582L22.1478 7.3341V7.33412L48 26.7839L73.8522 7.3341Z"
          />
        </svg>
      </a>
    </div>
  </div>
  <div
    class="nav-mobile hidden absolute py-8 justify-between items-center text-gray-100 hover:text-gray-100 focus:text-gray-700 shadow-lg"
  >
    <div class="text-center">
      <img
        src="/src/assets/img/avatar.png"
        class="absolute md:hidden w-14 mb-4 mx-6"
        alt="Avatar"
      />
      <h5 class="text-xl font-medium leading-tight">Jones Lima</h5>
      <p class="text-[color:#6FF1A6] text-sm ml-6">Software Developer</p>

      <div class="border-b border-gray-300 mt-6 w-64 ml-4"></div>
      <div class="flex items-center">
        <span class="text-[color:#6FF1A6] mr-1">
          <img class="visibility: hidden" src="/src/assets/logo.svg" >
        </span>
      </div>
      <div class="nav-list">
        <ul
          class="md:flex md:items-center md:px-26 px-4 md:pb-0 pb-8 absolute md:w-auto w-full duration-700 ease-in"
          :class="[open ? 'rigth-0' : 'rigth-[-100%]']"
        >
          <li class="md:mx-4 md:my-0 my-4 mt-4" v-for="link in Links" v-bind:key="link.link">
            <a :href="link.link" class="text-lg hover:[color:#6FF1A6]">{{
              link.name
            }}</a>
          </li>
        </ul>
      </div>
    </div>
    <div Class="absolute container w-full py-2.5 items-center mt-32">

 
<button
  class="Button bg-[color:#6FF1A6] rounded text-zinc-900"
>
<a class="justify-center" href="./src/assets/cv.pdf" download>Downloand CV</a>
</button>
 </div>
   </div>
  
</template>

<style scoped>
.nav-mobile {
  width: 288px;
  height: 320px;
  background: rgba(56, 56, 56, 0.75);
  backdrop-filter: blur(5px);
  border-radius: 7px;
  z-index: 0;
  top: -1px;
}
ul {
  top: 6.5rem;
  font-weight: 400;
  font-style: ubuntu;
  left: -80px;
}
li {
  top: 10px;
}

.container {
display: flex;
justify-content: center;
align-items: center
}
.Button {
font-family: ubuntu mono;
font-weight: 600;
font-size: 16px;
width: 140px;
height: 38px;
margin: 1.5rem;
justify-content: center;
align-items: center;
}
</style>
