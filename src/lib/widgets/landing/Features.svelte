

<script lang="ts">
    import {
      featuresCommunicationCards,
	    featuresLeanCoffee,
	    featuresFacilitatorCards } from '$shared';
    // import {  } from '$widgets';
    // import {  } from '$entities'

      const features = [].concat(featuresCommunicationCards, featuresLeanCoffee, featuresFacilitatorCards )
</script>

<section class="section_testimonial16">
	<div class="padding-global">
		<div class="container-large">
			<div class="padding-section-medium mx-auto">
				<div
					class="testimonial16_component "
				>
					<div class="testimonial16_mask ">
						<div class="testimonial16_slide ">
							<div class="w-layout-grid testimonial16_content ">
								<div
									class="testimonial16_content-right"
								>
									<div class="margin-bottom margin-xsmall">
										<h2 class="heading-medium">Lorem Ipsum is simply dummy</h2>
									</div>
									<div class="margin-bottom margin-medium">
										<div class="text-size-medium">
											Lorem Ipsum is simply dummy printing and typesetting industry.
										</div>
									</div>
									<div class="margin-bottom margin-medium max-width-full">
										<div class="checklist-vertical-wrap _2cols">

                      {#each features as {title, icon, textColor}}
											<div class="checklist-item">
												<div>
                          <div class="checklist-icon">
                            <img src="/images/{icon}" class='w-full h-full' alt="">
                          </div>
												</div>
												<div class='{textColor}'>
                          {title}
                        </div>
											</div>
                      {/each}
										</div>
									</div>
								</div>
								<img
									src="/images/features.png"
									loading="lazy"

									alt=""

									class="testimonial16_lightbox-image"
								/>
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
