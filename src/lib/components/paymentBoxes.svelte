<script>
    import { Check } from 'lucide-svelte'
    let paymentBoxes = [
        {
            title: "EXPLORER",
            price: "$29",
            desc: "Save 300+ hours of reading 37k comments",
            words: [
                "Essential integration tools", 
                "Up to 10 integrations", 
                "Email Support",
                "Basic Analytics",
                "Single User Access",
                "Regular Updates",
                "$1.9 per report"
            ],
            btnText: "Start for free",
            freePlanTxt: "*3 free searches per plan",
        },
        {
            title: "ENTHUSIAST",
            price: "$79",
            desc: "Save 600+ hours of reading 57k comments",
            words: [
                "Advanced integration tools", 
                "Up to 40 integrations", 
                "Email Support",
                "Advanced Analytics",
                "2-3 User Access",
                "Regular Updates",
                "$1.3 per report"
            ],
            btnText: "Start for free",
            freePlanTxt: "*3 free searches per plan",
        },
        {
            title: "PROFESSIONAL",
            price: "$159",
            desc: "Save 1200+ hours of reading 127k comments",
            words: [
                "Expert integration tools", 
                "Unlimited integrations", 
                "Email Support",
                "Expert Analytics",
                "Unlimited User Access",
                "Priority Updates",
                "$0.8 per report"
            ],
            btnText: "Start for free",
            freePlanTxt: "*3 free searches per plan",
        },
    ]
</script>

<div class="flex justify-around gap-6 p-[70px]">
    {#each paymentBoxes as box}
        <div class="flex flex-col rounded-2xl p-10 bg-[#e3e3e3] w-full max-w-[500px]">
            <h3 class="text-[14px]">{box.title}</h3>
            <h2 class="text-[55px] font-bold">{box.price}</h2>
            <h3 class="pb-5">{box.desc}</h3>
            <div class="flex w-full gap-2  rounded-2xl mb-2">
                <Check/>
                <p>{box.words[0]}</p>
            </div>
            <div class="flex w-full gap-2 rounded-2xl mb-2">
                <Check/>
                <p>{box.words[1]}</p>
            </div>
            <div class="flex w-full gap-2 rounded-2xl mb-2">
                <Check/>
                <p>{box.words[2]}</p>
            </div >
            <div class="flex w-full gap-2 rounded-2xl mb-2">
                <Check/>
                <p>{box.words[3]}</p>
            </div>
            <div class="flex w-full gap-2 rounded-2xl mb-2">
                <Check/>
                <p>{box.words[4]}</p>
            </div>
            <div class="flex w-full gap-2 rounded-2xl mb-2">
                <Check/>
                <p>{box.words[5]}</p>
            </div>
            <div class="flex w-full gap-2 rounded-2xl mb-7">
                <Check/>
                <p>{box.words[6]}</p>
            </div>
            <button class="pb-3 font-bold p-2 rounded-3xl bg-black text-white">{box.btnText}</button>
            <p id="sub-text" class="pt-6">{box.freePlanTxt}</p>
        </div>    
    {/each}
</div>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Anton+SC&family=JetBrains+Mono:ital,wght@0,100..800;1,100..800&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=Anton+SC&family=JetBrains+Mono:ital,wght@0,100..800;1,100..800&family=Kanit:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');

    h3{
        font-family: JETBRAINS MONO, monospace;
    }
    p{
        font-family: Kanit, monospace;
        font-size: 20px;
    }
    #sub-text{
        font-size: 16px;
        color: rgba(0,0,0,0.8);
    }
    button{
        font-family: JETBRAINS Mono;
        font-weight: 700;
    }
</style>