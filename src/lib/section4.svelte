<script>
    import PaymentBoxes from "./components/paymentBoxes.svelte";
</script>

<div>
    <div class="w-full flex justify-around p-14">
        <h2 class="text-[rgba(5,5,5,0.8)] text-[55px]">Start for free <span class="text-black">Upgrade to scale<span class="flash">_</span></span></h2>
        <h3 class="text-[20px]">No credit card required Cancel anytime</h3>
    </div>
    <PaymentBoxes/>
</div>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Anton+SC&family=JetBrains+Mono:ital,wght@0,100..800;1,100..800&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=Anton+SC&family=JetBrains+Mono:ital,wght@0,100..800;1,100..800&family=Kanit:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');
    h2{
        font-family: JETBRAINS MONO, monospace;
        font-weight: 600;
    }
    .flash{
        animation: flash 1.4s linear infinite;
    }
    @keyframes flash {
        0%{
            opacity: 0;
        }
        50%{
            opacity: 1;
        }
        100%{
            opacity: 0;
        }
    }
</style>