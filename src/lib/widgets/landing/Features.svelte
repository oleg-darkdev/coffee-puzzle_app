

<script lang="ts">
    // import {  } from '$shared';
    // import {  } from '$widgets';
    // import {  } from '$entities'
  const features = [
    `Lorem Ipsum is simply dummy.`,
    `Lorem Ipsum is simply dummy.`,
    `Lorem Ipsum is simply dummy.`,
    `Lorem Ipsum is simply dummy.`,
    `Lorem Ipsum is simply dummy.`,
    `Lorem Ipsum is simply dummy.`,
    `Lorem Ipsum is simply dummy.`,
  ]
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

                      {#each features as feature}
											<div class="checklist-item">
												<div>
													<div class="checklist-icon text-color-orange w-embed">
														<svg
															width="100%"
															height="100%"
															viewBox="0 0 25 24"
															fill="currentColor"
															xmlns="http://www.w3.org/2000/svg"
														>
															<path
																d="M23.18 2.55C23.1425 2.37 22.9625 2.23875 22.7938 2.25C20.8475 2.3475 19.19 2.91 17.78 3.735C16.0663 2.51625 14.0488 1.875 11.9375 1.875C6.35375 1.875 1.8125 6.41625 1.8125 12C1.8125 17.5838 6.35375 22.125 11.9375 22.125C17.5213 22.125 22.0625 17.5838 22.0625 12C22.0625 9.49125 21.1513 7.11 19.4825 5.25375C20.5738 4.21875 21.7438 3.41625 22.94 2.9775C23.1163 2.91375 23.2175 2.73375 23.18 2.55ZM20.5625 12C20.5625 16.755 16.6925 20.625 11.9375 20.625C7.1825 20.625 3.3125 16.755 3.3125 12C3.3125 7.245 7.1825 3.375 11.9375 3.375C13.5425 3.375 15.0913 3.81375 16.445 4.64625C13.6063 6.87 11.96 10.11 10.9775 12.0562L9.08375 8.65496C8.9975 8.49371 8.80625 8.42246 8.63375 8.48246L5.4425 9.57746C5.31875 9.61871 5.22875 9.71996 5.19875 9.84371C5.16875 9.96746 5.20246 10.0987 5.28875 10.1887C8.4125 13.5 9.02 16.905 9.0275 16.9387C9.0425 17.0362 9.09875 17.1262 9.18125 17.1825C9.245 17.2275 9.32 17.25 9.39496 17.25C9.42121 17.25 9.44371 17.2462 9.46621 17.2425L13.2987 16.5112C13.4562 16.4812 13.5762 16.3575 13.5987 16.2C14.075 13.0462 15.9687 9.14996 18.44 6.33746C19.8125 7.905 20.5625 9.9 20.5625 12Z"
																fill="currentColor"
															></path>
														</svg>
													</div>
												</div>
												<div>
                          {feature}
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
