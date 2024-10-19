<script lang="ts">


	import { SEO, otherBoardgames, navigation, navigation, FlatLightBtn,  } from '$shared';
	import { Footer, Header, Hero, Cta, Faq, AboutFasilitatorCards, Features, Team, About, PreHeader, Contact, ScreenshotesSlider, AboutAuthor, Steps, BigImgsSlider, OtherBoardgamesSlider,  } from '$widgets';
  // import {  } from '$entities'

  export let data;

  // console.log(data.sessionid)
</script>


<SEO title="Home"/>

<Header {navigation}>
  <!-- <PreHeader /> -->
</Header>


<main class="main-wrapper">
  <div class="section-header23 top-offset">
    <Hero />

    <!-- <ScreenshotesSlider /> -->
  </div>

  <Steps />

  <Features />

  <BigImgsSlider />

  <AboutFasilitatorCards anchor='facilitator-cards' img='fasilitator-cards.webp' bgColor='bg-color-orange'>
    <div class="" slot='content'>
      <div class="margin-bottom margin-xsmall">
        <h2 class="heading-medium">Facilitator
          <span class="text-style-underline">cards</span>
        </h2>
      </div>

      <div class="margin-bottom margin-xsmall">
        <p class="text-size-medium margin-bottom margin-xsmall">
          Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
        </p>
        <p class="text-size-medium margin-bottom margin-xsmall">
          Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
        </p>
        <p class="text-size-medium margin-bottom margin-xsmall">
          Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
        </p>
        <p class="text-size-medium margin-bottom margin-xsmall">
          Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
        </p>

      </div>

      <div class="margin-bottom margin-xsmall">
        <p class="text-color-dark-orange text-size-xsmall">*Lorem Ipsum has been the industry's standard dummy</p>
      </div>


    </div>

    <div slot="card-content" class="">
      <div class="grid grid-cols-2 gap-6">
        <h3 class="text-4xl ">34 <br /> Lorem</h3>
        <h3 class="text-4xl">34 <br /> Lorem</h3>
      </div>

      <div>"Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book."</div>
      <!--
      <div class="margin-top margin-xxsmall">
        <h2 class="text-weight-bold text-size-regular">Oleg_darkDev</h2>
      </div> -->

    </div>
  </AboutFasilitatorCards>

  <About />

  <AboutFasilitatorCards anchor='communication-cards' img='fasilitator-cards.webp' bgColor='bg-color-dark-orange'>
    <div class="" slot='content'>
      <div class="margin-bottom margin-xsmall">
        <h2 class="heading-medium">Communication
          <span class="text-style-underline">cards</span>
        </h2>
      </div>

      <div class="margin-bottom margin-xsmall">
        <p class="text-size-medium margin-bottom margin-xsmall">
          Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
        </p>
        <p class="text-size-medium margin-bottom margin-xsmall">
          Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
        </p>
        <p class="text-size-medium margin-bottom margin-xsmall">
          Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
        </p>
        <p class="text-size-medium margin-bottom margin-xsmall">
          Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
        </p>

      </div>

      <div class="margin-bottom margin-xsmall">
        <p class="text-color-dark-orange text-size-xsmall">*Lorem Ipsum has been the industry's standard dummy</p>
      </div>

      <div  class="margin-bottom max-w-[230px] margin-xsmall">
          <FlatLightBtn link='https://core-cards.vercel.app/' title='Lorem Ipsum has been'/>
      </div>
    </div>

    <div slot="card-content" class="">
      <div class="grid grid-cols-2 gap-6">
        <h3 class="text-4xl ">34 <br /> Lorem</h3>
        <h3 class="text-4xl">34 <br /> Lorem</h3>
      </div>

      <div>"Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book."</div>
      <!--
      <div class="margin-top margin-xxsmall">
        <h2 class="text-weight-bold text-size-regular">Oleg_darkDev</h2>
      </div> -->

    </div>
  </AboutFasilitatorCards>

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
