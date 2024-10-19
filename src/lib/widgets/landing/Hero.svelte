

<script lang="ts">
    // import {  } from '$shared';
    // import {  } from '$widgets';
    // import {  } from '$entities'

  const boxInclude = [
    {
      title: 'Karty dla komunikacji',
      anchor: '#communication-cards',
      icon: 'features-corecards.svg',
      textColor: 'text-color-dark-orange'
    },
    {
      title: 'Podstawy facylitacji',
      anchor: '#facilitator-cards',
      icon: 'features-fasilitator.svg',
      textColor: 'text-color-orange'
    },
    {
      title: 'Narzędzie Lean Coffee',
      anchor: '#lean-coffee',
      icon: 'features-lean-coffee.svg',
      textColor: 'text-color-turquoise'
    },
  ]
</script>




<section class="top-offset">
  <div class="page-padding">
    <div class="container-medium">
    <div class="padding-top padding-xlarge">
      <div class="text-align-center">
        <div class="max-w-4xl align-center">
          <div class="margin-bottom margin-xsmall">
            <h1 class="heading-preheader ">Lorem Ipsum is simply dummy</h1>
          </div>
          <div class="margin-bottom margin-small">
            <h2 class="heading-hero slide_from-bottom-400">Lorem Ipsum is simply dummy  <span class="text-style-underline">printing and typesetting industry.</span>
            </h2>
          </div>
          <div class="margin-bottom margin-small">
            <p class="text-size-medium slide_from-bottom-500">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
          </div>
          <div class="margin-bottom margin-small">
            <div class="checklist-horizontal-wrap ">

              {#each boxInclude as {title, anchor, icon, textColor}}

                <a href='{anchor}' class="checklist-item">
                  <div>
                    <div class="checklist-icon">
                      <img src="/images/{icon}" class='w-full h-full' alt="">
                    </div>
                  </div>
                  <div>
                    <div class='text-2xl {textColor}'>{title}</div>
                  </div>
                </a>
              {/each}

            </div>
          </div>
          <div class="margin-top margin-medium">
            <div class="button-row is-button-row-center">
              <a href="/" class="button with-icon w-inline-block">
                <div class="button-text">Lorem Ipsum is simply dummy</div>
                <div class="icon-xxsmall w-embed">
                  <svg width="100%" height="100%" viewBox="0 0 18 15" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                    <path d="M1 7.5H17M17 7.5L11 1.5M17 7.5L11 13.5" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path>
                  </svg>
                </div>
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  </div>

  <div class="section-strip-lines">
    <div class="container-xlarge">
      <div class="padding-top padding-large">
        <div class="gallery-wrap">
          <div class="gallery-item item-1">
            <div class="gallery-img-white-layer grow-300">
              <img
                src="/images/hero_promo_1.png"
                loading="lazy"
                alt=""
                class="gallery-img"
              />
            </div>
          </div>
          <div class="gallery-item item-2">
            <div class="gallery-img-white-layer grow-500">
              <img
                src="/images/hero_promo_2.png"
                loading="lazy"
                alt=""
                class="gallery-img"
              />
            </div>
          </div>
          <div class="gallery-item item-3">
            <div class="gallery-img-white-layer grow-400">
              <img
                src="/images/hero_promo_3.png"
                loading="lazy"
                alt=""
                class="gallery-img"
              />
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="striplines-wrapper">
      <div class="strip-default background-color-darkorange"></div>
      <div class="strip-default background-color-orange"></div>
      <div class="strip-default background-color-light-yellow"></div>
    </div>
  </div>
  <section class="section_layout135 fade_in-300">
    <div class="padding-global">
      <div class="container-small">
        <div class="padding-top padding-small">
          <div class="max-width-custom-1 align-center">
            <p class="text-align-center text-size-medium">
              Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
</section>

<style lang="postcss">

</style>
