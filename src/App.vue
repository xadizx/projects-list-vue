<template>
  <About />
  <Projects :projects="projects" />
</template>

<script>
import About from "./components/About.vue";
import Projects from "./components/Procjets.vue";

export default {
  name: "App",
  components: {
    About,
    Projects,
  },

  data() {
    return {
      projects: [],
    };
  },

  created() {
    this.projects = [
      {
        id: 1,
        name: "Katalog wizytówek NAP",
        description: `Jest to mój najbardziej "złożony" projektu, który od początku do końca realizowałem sam. Katalog wizytówek firmowych z możliwością logowania kontem google, dodawania wpisów jako podstrony, oceniania wpisów i dodawania komentarzy. Katalog posiada rozbudowany panel administratora, umożliwiający pełne zarządzanie katalogiem, a także system kodów umożliwiających dodawanie wpisów. Całość rozszerzona jest o Google Rich snippets dla lepszego pozcyjnowania w google.`,
        img: "gadul.png",
        url: "gadulek.pl",
        github: null,
        gallery: "https://strony.szczecin.pl/projekty/katalog-nap",
      },
      {
        id: 2,
        name: "Katalog SEO",
        description:
          "Jest to wcześniejsza wersja wcześniej wymienionego katalogu wizytówek, napisana w Laravelu, oprócz wcześniej wymienionych funkcjonalności na stronie znajdują się automatycznie generowane na podstawie mapki google, wyszukiwarka wpisów oraz sortowanie po kategoriach. Do dodanych wpisów po ich akceptacji można dodać treści takie jak FAQ/cennik/galeria zdjęć, które później wyświetlane będą na odpowiednich podstronach.",
        img: "bizn.png",
        url: "biznes.warszawa.pl",
        github: null,
        gallery: "https://strony.szczecin.pl/projekty/katalog-seo",
      },
      {
        id: 3,
        name: "TODO APP",
        description:
          "Zasady działania aplikacji TODO nie trzeba nikomu tłumaczyć. Stworzona w celach nauki podstaw ExpressJS, zapozania z TailwindCSS oraz darkmodem.",
        img: "x3.png",
        url: null,
        github: "https://github.com/xadizx/TodoApp",
        gallery: null,
      },
      {
        id: 4,
        name: "Moje portfolio",
        description:
          "Poprzednia strona przedstawiająca moje dotychczasowe projekty zrobiona w celu zapoznania z NextJS oraz tworzeniem API w expressie.",
        img: "portf.png",
        url: "strony.szczecin.pl",
        github: "https://github.com/xadizx/portfolio-backend",
        gallery: null,
      },

      {
        id: 5,
        name: "Woodforms.eu",
        description: "Prosta strona firmowa zrobiona w wordpressie",
        img: "woodf.png",
        url: "woodforms.eu",
        github: null,
        gallery: null,
      },
      {
        id: 6,
        name: "Akcent.szczecin.pl",
        description: "Strona firmowa robiona ręcznie w html/css",
        img: "akcent.png",
        url: "akcent.szczecin.pl",
        github: null,
        gallery: null,
      },

      {
        id: 7,
        name: "Śledzenie statystyk z serwerów",
        description:
          'Mini apka do śledzenia statystyk z serwerów mojego taty oraz dodatkowo z naszego "smart" ogródka na balkonie. Napisana w reacie.',
        img: "x1.png",
        url: null,
        github: null,
        gallery: null,
      },
      {
        id: 8,
        name: "Śledzenie statystyk z katalogów",
        description:
          "Apka zrobiona w celu zobaczenia jak działa React Native, pobierająca i wyświetlająca dane z wcześniej opisanych katalogów.",
        img: "x5.png",
        url: null,
        github: "https://github.com/xadizx/catalog-stats",
        gallery: null,
      },
    ];
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;700&display=swap");

body {
  background-color: #e7e7de;
  font-family: "Poppins", sans-serif !important;
}
</style>
