<script>
    let infos = [
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
</script>

<div class="main flex gap-5 justify-start">
    {#each infos as info}
        <div class="second w-full max-w-[384px] bg-[#1b1b1b] rounded-2xl p-10 mb-7 group">
            <p class="text-[rgb(255,255,255,0.6)] group-hover:text-[#fff]">{info.number}</p>
            <h2 class="text-white text-[25px] pt-5 group-hover:text-[#F05941]">{info.header}</h2>
            <p id="last-p" class="text-[rgb(255,255,255,0.4)] pt-56">{info.para}</p>
        </div>
    {/each}
</div>


<style>
   @import url('https://fonts.googleapis.com/css2?family=Anton+SC&family=JetBrains+Mono:ital,wght@0,100..800;1,100..800&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');
   @import url('https://fonts.googleapis.com/css2?family=Anton+SC&family=JetBrains+Mono:ital,wght@0,100..800;1,100..800&family=Kanit:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');

   h2{
    font-family: JETBRAINS MONO, monospace;
   }
   #last-p{
    font-family: Kanit, monospace;
   }
</style>