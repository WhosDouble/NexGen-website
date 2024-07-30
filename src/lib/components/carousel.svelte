<script>
    import Carousel from "svelte-carousel";
    let cards = [
        {
            number: "01",
            header: "Configure Your Builder",
            para: "Set up your integration environment with our intuitive configuration tools."
        },
        {
            number: "02",
            header: "Connect Critical Apps",
            para: "Quickly link your customers' most essential applications using our rapid-integration."
        },
        {
            number: "03",
            header: "Develop Programmatically",
            para: "Use our Connectivity APIs to create custom integrations programmatically."
        },
        {
            number: "04",
            header: "Deploy and Optimize Performance",
            para: " Deploy your integrations effortlessly and continuously optimized for performance."
        },
    ]
    let carousel; // for calling methods of the carousel instance
    const handleNextClick = () => {
      carousel.goToNext();
    };
  </script>
  
  <Carousel
      bind:this={carousel}
      autoplay
      autoplayDuration={7000}
      autoplayProgressVisible>
      {#each cards as card}
        <div class="second w-full max-w-[384px] bg-[#1b1b1b] rounded-2xl p-10 mb-7 group">
            <p class="text-[rgb(255,255,255,0.6)] group-hover:text-[#fff]">{card.number}</p>
            <h2 class="text-white text-[25px] pt-5 group-hover:text-[#F05941]">{card.header}</h2>
            <p id="last-p" class="text-[rgb(255,255,255,0.4)] pt-56">{card.para}</p>
        </div>
      {/each}
  </Carousel>

  <style>

  </style>