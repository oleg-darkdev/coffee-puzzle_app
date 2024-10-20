

<script lang="ts">
    import { faqData } from '$shared';
    import { FaqCard } from '$entities';
</script>

<section class="section_faq1">
  <div class="padding-global">
    <div class="max-w-3xl align-center">
      <div class="padding-bottom padding-xhuge">
        <div class="margin-bottom margin-large">
          <a name="faq"></a>

          <div class="text-align-center">
            <div class="max-width-large">
              <div class="margin-bottom">
                <h2 class="heading-medium">Frequently Asked Questions</h2>
              </div>
            </div>
          </div>


        </div>
        {#each faqData as faq}
          <FaqCard {faq}/>
        {/each}
      </div>
    </div>
  </div>
</section>

<style lang="postcss">

</style>
