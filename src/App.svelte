<script>
  import Header from "./lib/header.svelte";
  import './app.css'
  import Model from "./lib/components/model.svelte";
  import Section1 from "./lib/section1.svelte";
  import Section2 from "./lib/section2.svelte";
  import Section3 from "./lib/section3.svelte";
  import Section4 from "./lib/section4.svelte";
  import Footer from "./lib/footer.svelte";
</script>

<body>
      <Header/>
      <Model/>
      <Section1/>
      <Section2/>
      <Section3/>
      <Section4/>
      <Footer/>
</body>

<style>
  body{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    overflow-y: hidden;
  }
</style>
