<script>
    let isModel = true
    const handleClick = () => {
        isModel = false
    }
</script>

{#if isModel}
    <div class="w-full max-w-[280px] z-[1000] m-8 p-5 rounded-xl bottom-0 right-0 bg-[#F05941] fixed">
        <h2 class="font-bold pb-2">DO YOU AGREE TO COOKIES?</h2>
        <p class="text-[13px] text-[rgba(0,0,0,0.8)] pb-3">By using our website you understand that we and our affiliates may use cookies. For more information, please visit our <a href="#" class="underline text-white">Privacy Policy</a></p>
        <button class="bg-white p-1 w-28 h-10 rounded" on:click|once={handleClick}>Decline</button>
        <button class="bg-black text-white p-1 w-28 h-10 rounded" on:click|once={handleClick}>Accept All</button>
    </div>
{/if}