<script>
    import Sqaurebox from "./components/sqaurebox.svelte";
</script>

<section class="flex flex-col text-center w-full" id="section1">
    <div class="main flex text-center justify-center w-full text-wrap pr-20 mt-20 mb-[30px] text-[50px]">
        <div class="max-w-[1000px]">
            <h1>BUILD ROBUST <span class="text-[#F05941]"> PRODUCT INTEGRATIONS</span> FOR YOUR USERS</h1>
        </div>
    </div>
    <Sqaurebox/>
    <div class="flex flex-col text-center justify-center">
        <div class="flex text-center justify-center">
            <div class="w-full max-w-[950px]">
                <p class="mt-[50px] text-[25px] mb-5">NexGen is an embedded integrations platform used by engineering and product teams <span class="take">to streamline and speed up all aspects of integration development—from user customization to polling infrastructure.</span>
                </p>
            </div>
        </div>
        <div class="flex justify-center gap-5">
        <a href="#section2" class="button1">CHOOSE YOUR EXPERIENCE</a>
            <button class="button2">BOOK A DEMO</button>
        </div>
    </div>
</section>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Anton+SC&family=JetBrains+Mono:ital,wght@0,100..800;1,100..800&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=Anton+SC&family=JetBrains+Mono:ital,wght@0,100..800;1,100..800&family=Kanit:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');

    h1{
        font-family: JetBrains Mono;
        font-weight: 700;
        line-height: 50px;
        letter-spacing: 1.5px;
    }
    .button1{
        border: 1px solid rgba(0, 0, 0, .3);
        padding: 10px;
        border-radius: 5px;
        font-family: Kanit, monospace;
    }
    .button2{
        padding: 10px;
        border-radius: 5px;
        background: #F05941; 
        font-family: Kanit, monospace;
        color: #eee;
    }
    p{
        color: rgba(0, 0, 0, .6);
        font-family: Kanit, monospace;
    }
    section{
        padding-bottom: 30px;
    }
    @media(max-width:576px){
        .take{
            display: none;
        }
    }
    @media(max-width:462px) {
        .main{
            font-size: 30px;
            text-align: center;
            padding: 0;
        }
        h1{
            line-height: 29px; 
        }
    }
</style>