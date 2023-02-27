<script setup>
import styles from "./logo.module.scss";
</script>

<template>
  <div class="md:columns-2 mx-auto overflow-hidden max-w-4xl mt-24">
    <div
      class="flex flex-col-reverse justify-center box-decoration-slice bg-[color:#6FF1A6] ml-4 rounded w-48 h-11"
    >
      <h1 class="text-center text-lg font-ubuntu font-bold">
        Software Developer
      </h1>
    </div>
    <div>
      <h2 :class="styles.title">
        Talk is cheap. <br />
        Show me the code.
      </h2>
      <p :class="styles.subtitle">
        Desenvolvedor de Software apaixonado por soluçãode problemas e pela
        criação de soluções eficientes para sua empresa.
      </p>
      <div class="py-8">
        <a
          href="https://wa.me/+5511955509876"
          target="blank"
          class="font-medium underline underline-offset-4 text-[color:#6FF1A6] hover:text-emerald-300 pl-5"
          >WHATSAPP!</a
        >
      </div>
      <div
        :class="styles.experiences"
        class="flex justify-center md:pr-32 md:mt-0"
      >
        <p :class="styles.years">02</p>
        <p :class="styles.experience" class="pt-4 pl-4">
          ANOS <br />EXPERIÊNCIA
        </p>
        <p :class="styles.years" class="pr-4">15</p>
        <p :class="styles.experience" class="pt-4 pr-4">
          PROJETOS <br />
          COMPLETOS
        </p>
      </div>
      <div class="md:flex mt-16">
        <img
          class="w-full md:h-full md:py-0"
          src="/src/assets/img/jones.png"
          alt="Img Jones"
        />
      </div>
    </div>
  </div>
</template>

<style scoped></style>
