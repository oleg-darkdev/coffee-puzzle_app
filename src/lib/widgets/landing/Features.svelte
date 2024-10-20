

<script lang="ts">
    import {
      featuresCommunicationCards,
	    featuresLeanCoffee,
	    featuresFacilitatorCards } from '$shared';
    // import {  } from '$widgets';
    // import {  } from '$entities'

      const features = [].concat(featuresCommunicationCards, featuresLeanCoffee, featuresFacilitatorCards )
</script>

<section class="">
	<div class="padding-global">
		<div class="container-large">
			<div class="padding-section-medium mx-auto">
				<div
					class="testimonial16_component "
				>
					<div class=" ">
						<div class="testimonial16_slide mx-auto">
							<div class="w-layout-grid testimonial16_content ">
								<div
									class="testimonial16_content-right "
								>
									<div class="margin-bottom margin-xsmall">
										<h2 class="heading-medium lg:text-left md:text-left text-center">Lorem Ipsum is simply dummy</h2>
									</div>
									<div class="margin-bottom margin-medium">
										<div class="text-size-medium lg:text-left md:text-left text-center">
											Lorem Ipsum is simply dummy printing and typesetting industry.
										</div>
									</div>
										<div class="checklist-vertical-wrap _2cols mx-auto">

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
.testimonial16_component {
  background-color: #0000;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  height: auto;
  position: relative;
}
.testimonial16_rating-icon {
  color: var(--black);
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 1.25rem;
  height: 1.25rem;
  margin-right: 0.25rem;
  display: flex;
}
.testimonial16_slide {
  height: 100%;
  /* margin-right: 5rem; */
}
.testimonial16_lightbox-image {
  width: 100%;
  max-height: 580px;
  max-width: 25rem;
  height: 100%;
}
.testimonial16_content-right {
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  height: 100%;
  padding-bottom: 1rem;
  padding-left: 2px;
  display: flex;
  position: relative;
}


.testimonial16_divider {
  background-color: var(--black);
  align-self: stretch;
  width: 1px;
  margin-left: 1.25rem;
  margin-right: 1.25rem;
}
.testimonial16_content {
  grid-column-gap: 5rem;
  grid-template-rows: auto;
  grid-template-columns: 1fr 1fr;
  grid-auto-columns: 1fr;
  place-items: center;
  padding-top: 2rem;
  padding-bottom: 2rem;
  display: grid;
}
.testimonial16_arrow {
  border: 1px solid var(--black);
  background-color: var(--white);
  border-radius: 100%;
  justify-content: center;
  align-items: center;
  width: 3rem;
  height: 3rem;
  display: flex;
  inset: auto 0% 0% auto;
}
.testimonial16_arrow.is-left {
  right: 4rem;
}
.testimonial16_client {
  text-align: left;
  align-items: center;
  display: flex;
}
.testimonial16_rating-wrapper {
  display: flex;
}
.testimonial16_slide-nav {
  height: 1.75rem;
  font-size: 0.5rem;
  display: none;
  inset: auto auto 0% 0%;
}
.testimonial16_lightbox {
  justify-content: center;
  align-items: center;
  width: 100%;
  display: flex;
  position: relative;
}
.testimonial16_logo {
  max-height: 3rem;
}

@media screen and (max-width: 991px) {
 .testimonial16_content {
    grid-column-gap: 2.5rem;
    grid-row-gap: 2.5rem;
    grid-template-columns: 1fr 1fr;
    grid-auto-flow: row;
    min-height: auto;
  }
  .testimonial16_lightbox-image {
    object-fit: fill;
    width: 100%;
    height: 100%;
  }

}
@media screen and (max-width: 767px) {
  .testimonial16_content {
    grid-column-gap: 3rem;
    grid-row-gap: 3rem;
    flex-direction: column-reverse;
    grid-template-columns: 1fr;
    align-items: center;
    display: flex;
  }
  .testimonial16_arrow {
    inset: 0% 0% auto auto;
  }
  .testimonial16_arrow.is-left {
    right: 3.5rem;
  }
  .testimonial16_client {
    align-items: center;
    width: 100%;
  }
  .testimonial16_slide-nav {
    inset: 0% auto auto 0%;
  }
  .testimonial16_component {
    padding-top: 0;
    padding-bottom: 0;
  }
  .testimonial16_slide {
    padding-left: 0;
    padding-right: 0;
    max-width: 300px;
  }
  .testimonial16_lightbox-image {
    width: 80%;
  }
  .testimonial16_content-right {
    justify-content: flex-start;
    height: auto;
    padding-top: 0;
  }
}
@media screen and (max-width: 479px) {
  .testimonial16_divider {
    margin-left: 1rem;
    margin-right: 1rem;
  }
  .testimonial16_content {
    grid-column-gap: 0rem;
    grid-row-gap: 0rem;
    grid-template-columns: 1fr;
  }
  .testimonial16_lightbox-image {
    margin-bottom: 2rem;
  }
}
</style>
