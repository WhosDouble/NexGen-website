<script>
    import Cards from "./components/cards.svelte";
    import Carousel from "./components/carousel.svelte";
</script>

<div class="main pt-20 pl-16 pr-16">
    <div class="words-con w-full max-w-[900px]"><h1 class="words text-[55px] mb-10">SUPPORT YOUR DECISION- MAKING <span class="text-[#F05941]">WITH A SIMPLE SETUP</span></h1></div>
    <div class="showing">
        <Cards/>
    </div>
    <div class="hidden">
        <Carousel/>
    </div>
    <div class="flex items-center w-full max-w-[1600px] rounded-2xl h-28 bg-[#1b1b1b] mb-10">
        <div class="div1 w-full flex items-center justify-start p-5">
            <h2 class="text-[rgba(255,255,255,0.6)] text-[25px]">Unlock Your <span class="text-white">Intergration Superpowers</span></h2>
        </div>
        <div class="div2 w-[200px] flex items-center justify-end p-10">
            <button class="bg-[#fff] w-[200px] rounded-xl p-2">Book a Demo</button>
        </div>
    </div>
</div>

<style>
 @import url('https://fonts.googleapis.com/css2?family=Anton+SC&family=JetBrains+Mono:ital,wght@0,100..800;1,100..800&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');
 @import url('https://fonts.googleapis.com/css2?family=Anton+SC&family=JetBrains+Mono:ital,wght@0,100..800;1,100..800&family=Kanit:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');
 h1{
    font-family: JETBRAINS MONO;
    font-weight: 800;
 }

 button{
    font-family: Kanit, sans-serif;
    font-weight: 500;
 }

 @media(max-width:1160px) {
    .showing{
        display: none;
    }
    .hidden{
        display: block;
    }
}
@media(max-width:556px) {
    .showing{
        display: none;
    }
    .hidden{
        display: block;
    }
    .main{
        padding: 0;
    }
    .words-con{
        padding-left: 20px;
        padding-right: 20px;
        padding-top: 20px;
    }
    .words{
        font-size: 28px;
    }
}
@media(max-width:470px) {
    .showing{
        display: none;
    }
    .hidden{
        display: block;
    }
    .div1{
        padding: 0;
    }
    .div2{
        padding: 10px;
    }
}
</style>