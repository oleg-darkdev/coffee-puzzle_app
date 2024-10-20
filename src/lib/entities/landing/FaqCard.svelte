

<script lang="ts">
    // import {  } from '$shared';
    // import {  } from '$widgets';
    // import {  } from '$entities'
  export let faq;
</script>

<div
  class="faq1_component faq1_accordion" on:click={()=> faq.showAnswer = !faq.showAnswer}
>
  <div class="faq1_question" >
    <h3 class="text-weight-bold text-size-regular">
      {faq.q}
    </h3>
    <a href="#" class="faq-arrow-icon">+</a>
  </div>

  {#if faq.showAnswer}
  <div
    class="faq1_answer"
  >
    <div class="margin-bottom ">
      {#each faq.a as answer}
        <p class="text-size-medium mb-2">
          {answer}
        </p>
      {/each}
    </div>
  </div>
  {/if}
</div>

<style lang="postcss">

</style>
