<template>
  <div class="flex flex-col mt-5 mb-5">
    <div
      id="about"
      class="
        grid
        place-items-center
        w-4/5
        mx-auto
        md:p-10
        my-20
        sm:my-auto
        rounded-xl
        space-y-5
        text-center
      "
    >
      <h1 class="text-4xl md:text-8xl font-semibold uppercase">
        Adam Zabraniak
      </h1>
      <h2 class="text-2xl md:text-justify">
        Jestem absolwentem technikum informatycznego, a z programowaniem wiążę
        swoją przyszłość zawodową. W wolnych chwilach poszerzam swoją wiedzę
        samodzielnie oraz przez różnego rodzaju poradniki i kursy. Poniżej
        znajduje się lista z wykonanymi przeze mnie projektami/mini apkami wraz
        z krótkim opisem.
      </h2>
      <div
        class="
          flex flex-wrap
          mt-10
          justify-center
          lg:space-x-2
          md:flex-col
          lg:flex-row
          items-center
        "
      >
        <a
          href="https://strony.szczecin.pl/"
          class="
            tracking-wide
            font-bold
            rounded
            py-2
            px-6
            inline-flex
            items-center
            transition
            duration-300
            md:mb-3
          "
        >
          <span class="mx-auto"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-6 w-6"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"
              />
            </svg>
            Portfolio</span
          >
        </a>

        <a
          href="https://github.com/xadizx/"
          class="
            tracking-wide
            font-bold
            rounded
            py-2
            px-6
            inline-flex
            items-center
            transition
            duration-300
            md:mb-3
          "
        >
          <span class="mx-auto"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-6 w-6"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"
              />
            </svg>
            Github</span
          >
        </a>
        <a
          href="mailto:adamzabraniak@gmail.com"
          class="
            tracking-wide
            font-bold
            rounded
            py-2
            px-6
            inline-flex
            items-center
            transition
            duration-300
            md:mb-3
          "
        >
          <span class="mx-auto"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-6 w-6"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
              />
            </svg>
            adamzabraniak@gmail.com</span
          >
        </a>

        <a
          href="tel:577717118"
          class="
            tracking-wide
            font-bold
            rounded
            py-2
            px-6
            inline-flex
            items-center
            transition
            duration-300
            md:mb-3
          "
        >
          <span class="mx-auto"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-6 w-6"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"
              />
            </svg>
            577 717 118</span
          >
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "About",
};
</script>

<style scoped>
body {
  color: #191919 !important;
}

h1 {
  color: #3772ff;
}
svg {
  display: inline;
}

a {
  color: #3772ff;
}
</style>
