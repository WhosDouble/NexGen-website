<header>
    <nav>
        <a href="#section1"><img class="cursor-pointer mr-20 pl-0 z-50" src="/src/assets/myLogo.png" alt="logo"></a>
        <div>
            <h3 class="">Platform</h3>
            <h3>Industries</h3>
            <h3>Developers</h3>
            <h3>Intergrations</h3>
            <a href="#">Resources</a>
        </div>
        <button class="bg-black rounded text-[#eee]">LOGIN</button>
        <button class="bg-black rounded text-[#eee]">BOOK</button>
    </nav>
</header>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Anton+SC&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
    h3, a{
        font-weight: 400;
        font-family: Poppins, sans-serif;
    }
    header{
        backdrop-filter: blur(10px);
        background-color: rgba(255, 255, 255, 0.8);
        position: fixed;
        width: 100%;
        padding-right: 40px;
        padding-left: 0;
        margin: 0;
        padding-top: 0;
    }
    nav{
        display: flex;
        align-items: center;
        width: 100%;
        gap: 10px;
        margin: 0;
        padding: 0;
    }
    img{
        width: 50px;
    }
    button{
        width: 120px;
        height: 30px;
        padding: 2px;
    }
    div{
        display: flex;
        width: 100%;
        justify-content: center;
        gap: 20px;
    }
</style>