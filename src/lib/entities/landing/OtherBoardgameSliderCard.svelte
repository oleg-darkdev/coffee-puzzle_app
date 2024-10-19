

<script lang="ts">
    // import {  } from '$shared';
    // import {  } from '$widgets';
    // import {  } from '$entities'
  export let boardgame;
</script>

<div role="listitem" class="testimonial15_slide splide__slide w-dyn-item">
  <div>
    <div class="w-layout-grid testimonial15_content">
      <div class="testimonial15_client-image-wrapper">
        <div class="testimonial-image-border">
        <img loading="lazy" alt="{boardgame.title} logo" src="{boardgame.logo}" class="testimonial15_client-image">
        </div>
      </div>
      <!-- <div class="testimonial15_client-image-wrapper">
        <div class="testimonial-image-border">
          <img loading="lazy" alt="{boardgame.title} logo" src="{boardgame.logo}" class="testimonial15_client-image">
        </div>
      </div> -->


      <div class="testimonial15_content-right">
        <div class="margin-bottom margin-small">
          <div>
            {boardgame.shortDesc}
          </div>
        </div>
        <div class="testimonial15_client">
          <div class="testimonial15_client-info">
            <p class="text-weight-semibold"> {boardgame.title} </p>
          </div>
          <div class="testimonial15_client-info separator">
            <p class="text-weight-semibold">-</p>
          </div>
          <div class="testimonial15_client-info">
            <a href={boardgame.link} target="_blank" class="text-color-dark-orange text-weight-bold">więcej szczegółów</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>




<style lang="postcss">

</style>
