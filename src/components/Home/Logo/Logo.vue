<script setup>
import styles from "./logo.module.scss";
</script>

<template>
  <div class="container bg-[color:#2D2E32]">
    <div class="box bg-[color:#6FF1A6] m-12">
      <h1 class="text-center text-lg font-ubuntu font-bold">
        Front-End Developer
      </h1>
    </div>
    <div>
      <h2 :class="styles.title">
        Talk is cheap. <br />
        Show me the code.
      </h2>
      <p :class="styles.subtitle">
        Desenvolvedor de Software apaixonado por solução de problemas e pela
        criação de soluções eficientes para sua empresa.
      </p>
      <ul class="list-none pt-6">
        <li>
          <a
            href="https://wa.me/+5511955509876"
            target="blank"
            class="font-medium underline underline-offset-4 text-[color:#6FF1A6] hover:text-emerald-300 pl-5"
            >WHATSAPP!</a
          >
        </li>
      </ul>
      <div :class="styles.experiences" class="flex justify-center mb-2">
        <p :class="styles.years">02</p>
        <p :class="styles.experience" class="pt-4 pl-2">
          ANOS <br />EXPERIÊNCIA
        </p>
        <p :class="styles.years" class="pr-4">15</p>
        <p :class="styles.experience" class="pt-4 pr-4">
          PROJETOS <br />
          COMPLETOS
        </p>
      </div>
      <div class="flex flex-col justify-center">
        <img
          src="/src/assets/img/jones.png"
          class="mt-10 w-full h-full"
          alt=""
          width="286"
          height="328"
        />
      </div>
    </div>
    <div class="grid justify-center pt-6 bg-[color:#25262A] w-full">
      <button
        class="box-button shadow-md hover:transition hover:duration-300 hover:ease-in-out"
      >
        <p class="text-box font-bold text-[color:#6FF1A6] h-8 flex pl-4">
          Front-End
        </p>
        <p class="flex font-normal pl-4 text-white">
          I design and code beatifully simple
        </p>
      </button>
      <button class="box-button mt-2 shadow-md">
        <p class="text-box font-bold text-[color:#6FF1A6] h-8 flex pl-4">
          UX | UI Motion
        </p>
        <p class="flex font-normal pl-4 text-white">
          I design and code beatifully simple
        </p>
      </button>
      <button class="box-button justify-center mt-2 shadow-md">
        <p class="text-box font-bold text-[color:#6FF1A6] h-8 flex pl-4">
          Back-End
        </p>
        <p class="flex font-normal pl-4 text-white">
          I design and code beatifully simple
        </p>
      </button>
    </div>
  </div>
</template>

<style scoped>
.box {
  margin-left: 17px;
  margin-top: 100px;
  display: flex;
  border-radius: 3px;
  max-width: 191px;
  height: 44px;
  flex-direction: column-reverse;
  justify-content: center;
}

.box-button {
  width: 340px;
  height: 117px;
  background: #2c2d31;
  box-shadow: -10px 31px 46px rgba(0, 0, 0, 0.2);
  border-radius: 1px;
  justify-content: center;
  align-items: center
}
</style>
