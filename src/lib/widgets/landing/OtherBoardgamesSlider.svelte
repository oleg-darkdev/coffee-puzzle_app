

<script lang="ts">
    // import {  } from '$shared';
    // import {  } from '$widgets';
    import { OtherBoardgameSliderCard } from '$entities';

  export let otherBoardgames;
</script>

<section class="section_testimonial15">
    <div class="padding-global">
      <div>
        <div class="padding-section-medium">
          <div class="max-width-small align-center">
            <div class="text-align-center ">
              <div class="margin-bottom margin-small">
                <h2 class="heading-medium">Pozostałe  <span class="text-style-underline-v5">gry planszowe</span>
                </h2>
              </div>
              <div class="margin-bottom margin-large">
                <div class="text-size-medium">
                  Lorem Ipsum is simply dummy text of the printing and typesetting industry.
                </div>
              </div>
            </div>
          </div>
          <div class="max-width-medium align-center">
            <div  class="splide splide-testimonial-single">
              <div class="splide__track w-dyn-list">
                <div role="list" class="splide__list w-dyn-items">
                  {#each otherBoardgames as boardgame}
                    <OtherBoardgameSliderCard {boardgame}/>
                  {/each}
                </div>
              </div>
              <div class="splide__arrows">
                <div class="splide__arrows-wrapper">
                  <button aria-label="slider previous"  class="splide__arrow splide__arrow--prev w-inline-block">
                    <img src="images/arrow-prev-orange.svg" loading="lazy" alt="Previous">
                  </button>
                  <button aria-label="next control" class="splide__arrow splide__arrow--next w-inline-block">
                    <img src="images/arrow-right-orange.svg" loading="lazy" alt="Next">
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>



  <!--



<script lang="ts">
    // import {  } from '$shared';
    // import {  } from '$widgets';
    import { OtherBoardgameSliderCard } from '$entities';

  export let otherBoardgames;
</script>

<section class="section_testimonial15">
    <div class="padding-global">
      <div>
        <div class="padding-section-medium">
          <div class="max-width-small align-center">
            <div class="text-align-center ">
              <div class="margin-bottom margin-small">
                <h2 class="heading-medium">Pozostałe  <span class="text-style-underline-v5">gry planszowe</span>
                </h2>
              </div>
              <div class="margin-bottom margin-large">
                <div class="text-size-medium">
                  Lorem Ipsum is simply dummy text of the printing and typesetting industry.
                </div>
              </div>
            </div>
          </div>
          <div class="max-w-6xl mx-auto">
            <div  class="splide splide-testimonial-single">
              <div class="splide__track w-dyn-list">
                <div role="list" class="flex flex-wrap flex-row justify-between">
                  {#each otherBoardgames as boardgame}
                    <OtherBoardgameSliderCard {boardgame}/>
                  {/each}
                </div>
              </div>
              <div class="splide__arrows">
                <div class="splide__arrows-wrapper">
                  <button aria-label="slider previous"  class="splide__arrow splide__arrow--prev w-inline-block">
                    <img src="images/arrow-prev-orange.svg" loading="lazy" alt="Previous">
                  </button>
                  <button aria-label="next control" class="splide__arrow splide__arrow--next w-inline-block">
                    <img src="images/arrow-right-orange.svg" loading="lazy" alt="Next">
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

<style lang="postcss">

</style>

   -->

<style lang="postcss">

</style>
