<script>
  import { Carousel, CarouselTransition } from 'flowbite-svelte'
  // ./imageData/+server.js has the following
  const images = [
  {
    id: 0,
    name: "Cosmic timetraveler",
    imgurl: "https://flowbite-svelte.com//images/carousel/cosmic-timetraveler-pYyOZ8q7AII-unsplash.webp",
    attribution: "cosmic-timetraveler-pYyOZ8q7AII-unsplash.com",
  },
  {
    id: 1,
    name: "Cristina Gottardi",
    imgurl: "https://flowbite-svelte.com/images/carousel/cristina-gottardi-CSpjU6hYo_0-unsplash.webp",
    attribution: "cristina-gottardi-CSpjU6hYo_0-unsplash.com",
  },
  {
    id: 2,
    name: "Johannes Plenio",
    imgurl: "https://flowbite-svelte.com//images/carousel/johannes-plenio-RwHv7LgeC7s-unsplash.webp",
    attribution: "johannes-plenio-RwHv7LgeC7s-unsplash.com",
  },
  {
    id: 3,
    name: "Jonatan Pie",
    imgurl: "https://flowbite-svelte.com//images/carousel/jonatan-pie-3l3RwQdHRHg-unsplash.webp",
    attribution: "jonatan-pie-3l3RwQdHRHg-unsplash.com",
  },
  {
    id: 4,
    name: "Mark Harpur",
    imgurl: "https://flowbite-svelte.com//images/carousel/mark-harpur-K2s_YE031CA-unsplash.webp",
    attribution: "mark-harpur-K2s_YE031CA-unsplash",
  },
  {
    id: 5,
    name: "Pietro De Grandi",
    imgurl: "https://flowbite-svelte.com//images/carousel/pietro-de-grandi-T7K4aEPoGGk-unsplash.webp",
    attribution: "pietro-de-grandi-T7K4aEPoGGk-unsplash",
  },
  {
    id: 6,
    name: "Sergey Pesterev",
    imgurl: "https://flowbite-svelte.com//images/carousel/sergey-pesterev-tMvuB9se2uQ-unsplash.webp",
    attribution: "sergey-pesterev-tMvuB9se2uQ-unsplash",
  },
  {
    id: 7,
    name: "Solo travel goals",
    imgurl: "https://flowbite-svelte.com//images/carousel/solotravelgoals-7kLufxYoqWk-unsplash.webp",
    attribution: "solotravelgoals-7kLufxYoqWk-unsplash",
  },
];
</script>


<div class="max-w-4xl">
  <Carousel {images} />
</div>