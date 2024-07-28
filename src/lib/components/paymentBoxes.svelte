<script>
    let paymentBoxes = [
        {
            title: "EXPLORER",
            price: "$29",
            desc: "Save 300+ hours of reading 37k comments",
            words: [
                "10 reports", 
                "50 AI persona messages", 
                "slack intergration",
                "Sentiment analysis",
                "Trend analysis",
                "Sharable reports",
                "$1.9 per report"
            ],
            btnText: "Start for free",
            freePlanTxt: "*3 free searches per plan",
        },
        {
            title: "ENTHUSIAST",
            price: "$79",
            desc: "Save 300+ hours of reading 37k comments",
            words: [
                "25 reports", 
                "250 AI persona messages", 
                "slack intergration",
                "Sentiment analysis",
                "Trend analysis",
                "Sharable reports",
                "$1.9 per report"
            ],
            btnText: "Start for free",
            freePlanTxt: "*3 free searches per plan",
        },
        {
            title: "PROFESSIONAL",
            price: "$159",
            desc: "Save 300+ hours of reading 37k comments",
            words: [
                "10 reports", 
                "50 AI persona messages", 
                "slack intergration",
                "Sentiment analysis",
                "Trend analysis",
                "Sharable reports",
                "$1.9 per report"
            ],
            btnText: "Start for free",
            freePlanTxt: "*3 free searches per plan",
        },
    ]
</script>

<div class="flex justify-around gap-5 p-[70px]">
    {#each paymentBoxes as box}
        <div class="flex flex-col rounded-2xl p-10 bg-[#e3e3e3] w-full max-w-[500px]">
            <h3 class="text-[14px]">{box.title}</h3>
            <h2 class="text-[55px] font-bold">{box.price}</h2>
            <p class="pb-5">{box.desc}</p>
            <div class="flex w-full bg-[#cecece] pl-4 p-1 rounded-2xl mb-2">
                <h3>{box.words[0]}</h3>
            </div>
            <div class="flex w-full bg-[#cecece] pl-4 p-1 rounded-2xl mb-2">
                <h3>{box.words[1]}</h3>
            </div>
            <div class="flex w-full bg-[#cecece] pl-4 p-1 rounded-2xl mb-2">
                <h3>{box.words[2]}</h3>
            </div >
            <div class="flex w-full bg-[#cecece] pl-4 p-1 rounded-2xl mb-2">
                <h3>{box.words[3]}</h3>
            </div>
            <div class="flex w-full bg-[#cecece] pl-4 p-1 rounded-2xl mb-2">
                <h3>{box.words[4]}</h3>
            </div>
            <div class="flex w-full bg-[#cecece] pl-4 p-1 rounded-2xl mb-2">
                <h3>{box.words[5]}</h3>
            </div>
            <div class="flex w-full bg-[#cecece] pl-4 p-1 rounded-2xl mb-7">
                <h3>{box.words[6]}</h3>
            </div>
            <button class="pb-3 font-bold p-2 rounded-3xl bg-black text-white">{box.btnText}</button>
            <p class="pt-6">{box.freePlanTxt}</p>
        </div>    
    {/each}
</div>

<style>

</style>