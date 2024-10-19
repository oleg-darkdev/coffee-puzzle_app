<script lang="ts">


	import { SEO, otherBoardgames, navigation, navigation,  } from '$shared';
	import { Footer, Header, Hero, Cta, Faq, Features, Team, About, PreHeader, Contact, ScreenshotesSlider, AboutAuthor, Steps, BigImgsSlider, OtherBoardgamesSlider,  } from '$widgets';
  // import {  } from '$entities'

  export let data;

  // console.log(data.sessionid)
</script>


<SEO title="Home"/>






<Header {navigation}>
  <PreHeader />
</Header>


<main class="main-wrapper">
  <div class="section-header23 top-offset">
    <Hero />

    <!-- <ScreenshotesSlider /> -->
  </div>

  <Steps />

  <Features />

  <BigImgsSlider />

  <About />

  <Team />

  <AboutAuthor />

  <OtherBoardgamesSlider {otherBoardgames} />

  <Faq />

  <Cta />

  <Contact />


</main>

<Footer {otherBoardgames} {navigation}/>



<style lang="postcss">

</style>
