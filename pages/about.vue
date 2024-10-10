<template>
  <div class="relative flex size-full min-h-screen flex-col group/design-root overflow-x-hidden"
    style='font-family: "Public Sans", "Noto Sans", sans-serif;'>
    <div class="layout-container flex h-full grow flex-col">
      <div class="px-40 flex flex-1 justify-center py-5">
        <div class="layout-content-container flex flex-col max-w-[960px] flex-1">
          <div class="@container">
            <div class="flex flex-col gap-6 px-4 py-10 @[480px]:gap-8 @[864px]:flex-row">
              <div
                class="w-full bg-center bg-no-repeat aspect-video bg-cover rounded-xl @[480px]:h-auto @[480px]:min-w-[400px] @[864px]:w-full"
                style='background-image: url("https://cdn.usegalileo.ai/sdxl10/ea468b77-f07c-4328-bd3f-eb58e2218312.png");'>
              </div>
              <div class="flex flex-col gap-6 @[480px]:min-w-[400px] @[480px]:gap-8 @[864px]:justify-center">
                <div class="flex flex-col gap-2 text-left">
                  <h1
                    class="text-[#0e101b] text-4xl font-black leading-tight tracking-[-0.033em] @[480px]:text-5xl @[480px]:font-black @[480px]:leading-tight @[480px]:tracking-[-0.033em]">
                    Deep clean, every time
                  </h1>
                  <h2
                    class="text-[#0e101b] text-sm font-normal leading-normal @[480px]:text-base @[480px]:font-normal @[480px]:leading-normal">
                    At UMQ, we're dedicated
                    to providing deep cleaning services at affordable prices. Our
                    mission is to provide the best possible service to our clients, and we're always looking for ways
                    to improve.
                  </h2>
                </div>
              </div>
              <h1
                class="text-[#0e101b] tracking-light text-[32px] font-bold leading-tight @[480px]:text-4xl @[480px]:font-black @[480px]:leading-tight @[480px]:tracking-[-0.033em] max-w-[720px]">
                Who We Are
              </h1>
              <h2
                class="text-[#0e101b] text-sm font-normal leading-normal @[480px]:text-base @[480px]:font-normal @[480px]:leading-normal">
                We are a professional cleaning company committed to excellence and client satisfaction. With a highly trained team of skilled professionals and the latest cleaning technologies, we ensure that every service is executed with utmost efficiency and care. Our focus is on building long-term relationships with our customers by exceeding their expectations in every job we undertake.
              </h2>

              <h1
                class="text-[#0e101b] tracking-light text-[32px] font-bold leading-tight @[480px]:text-4xl @[480px]:font-black @[480px]:leading-tight @[480px]:tracking-[-0.033em] max-w-[720px]">
                Our Mission
              </h1>
              <h2
                class="text-[#0e101b] text-sm font-normal leading-normal @[480px]:text-base @[480px]:font-normal @[480px]:leading-normal">
                At UMQ Cleaning Services, our mission is to provide top-quality cleaning solutions while maintaining a commitment to safety, reliability, and environmental sustainability. We strive to exceed customer expectations and build long-lasting relationships through our exceptional service and professionalism.
              </h2>
            </div>
          </div>


          <div class="flex flex-col gap-10 px-4 py-10 @container">
            <h1
              class="text-[#0e101b] tracking-light text-[32px] font-bold leading-tight @[480px]:text-4xl @[480px]:font-black @[480px]:leading-tight @[480px]:tracking-[-0.033em] max-w-[720px]">
              Our Goals
            </h1>
            <div class="grid grid-cols-[repeat(auto-fit,minmax(158px,1fr))] gap-3 p-0">
              <div class="flex flex-1 gap-3 rounded-lg border border-[#d0d3e7] bg-[#f8f9fc] p-4 flex-col">
                <div class="text-[#0e101b]" data-icon="ShieldCheck" data-size="24px" data-weight="regular">
                  <ShieldCheckIcon />
                </div>
                <div class="flex flex-col gap-1">
                  <h2 class="text-[#0e101b] text-base font-bold leading-tight">
                    High-Quality Services
                  </h2>
                  <p class="text-[#4e5997] text-sm font-normal leading-normal">
                    Our primary focus is on providing high-quality cleaning services tailored to meet the unique needs of each client. We employ the latest industry techniques and technologies to ensure exceptional cleaning results, leaving every space spotless and hygienic.
                  </p>
                </div>
              </div>
              <div class="flex flex-1 gap-3 rounded-lg border border-[#d0d3e7] bg-[#f8f9fc] p-4 flex-col">
                <div class="text-[#0e101b]" data-icon="HandHeart" data-size="24px" data-weight="regular">
                  <HandHeartIcon />
                </div>
                <div class="flex flex-col gap-1">
                  <h2 class="text-[#0e101b] text-base font-bold leading-tight">
                    Reputation and Trust
                  </h2>
                  <p class="text-[#4e5997] text-sm font-normal leading-normal">
                    Building a reputation based on trust and reliability is at the core of what we do. We strive to exceed client expectations and build long-term relationships through transparent communication, dependability, and a commitment to delivering on our promises.
                  </p>
                </div>
              </div>
              <div class="flex flex-1 gap-3 rounded-lg border border-[#d0d3e7] bg-[#f8f9fc] p-4 flex-col">
                <div class="text-[#0e101b]" data-icon="Truck" data-size="24px" data-weight="regular">
                  <TruckIcon />
                </div>
                <div class="flex flex-col gap-1">
                  <h2 class="text-[#0e101b] text-base font-bold leading-tight">
                    Customer Satisfaction
                  </h2>
                  <p class="text-[#4e5997] text-sm font-normal leading-normal">
                    Customer satisfaction is our top priority. We are committed to understanding your requirements and going above and beyond to ensure your needs are met. Our team takes every step necessary to achieve a level of cleanliness and service that exceeds your expectations.
                  </p>
                </div>
              </div>
              <div class="flex flex-1 gap-3 rounded-lg border border-[#d0d3e7] bg-[#f8f9fc] p-4 flex-col">
                <div class="text-[#0e101b]" data-icon="Clock" data-size="24px" data-weight="regular">
                  <ClockIcon />
                </div>
                <div class="flex flex-col gap-1">
                  <h2 class="text-[#0e101b] text-base font-bold leading-tight">
                    Qualified and Trained Team
                  </h2>
                  <p class="text-[#4e5997] text-sm font-normal leading-normal">
                    We believe that a well-trained and professional team is essential for providing top-notch services. Our staff undergoes continuous training and certification to stay up-to-date with the best practices and safety standards in the industry.
                  </p>
                </div>
              </div>
              <div class="flex flex-1 gap-3 rounded-lg border border-[#d0d3e7] bg-[#f8f9fc] p-4 flex-col">
                <div class="text-[#0e101b]" data-icon="Tag" data-size="24px" data-weight="regular">
                  <TagIcon />
                </div>
                <div class="flex flex-col gap-1">
                  <h2 class="text-[#0e101b] text-base font-bold leading-tight">
                    Punctuality and Adherence to Schedules
                  </h2>
                  <p class="text-[#4e5997] text-sm font-normal leading-normal">
                    We respect your time and the importance of maintaining a clean environment. Our team strictly adheres to the agreed schedules and ensures timely delivery of services without compromising on quality, ensuring that every appointment is met with precision.
                  </p>
                </div>
              </div>
              <div class="flex flex-1 gap-3 rounded-lg border border-[#d0d3e7] bg-[#f8f9fc] p-4 flex-col">
                <div class="text-[#0e101b]" data-icon="ShieldCheck" data-size="24px" data-weight="regular">
                  <ShieldCheckIcon />
                </div>
                <div class="flex flex-col gap-1">
                  <h2 class="text-[#0e101b] text-base font-bold leading-tight">
                    Eco-Friendly Approach
                  </h2>
                  <p class="text-[#4e5997] text-sm font-normal leading-normal">
                    We are dedicated to using eco-friendly products and techniques that are safe for both our clients and the environment. By minimizing the use of harmful chemicals, we ensure a safer, healthier, and more sustainable cleaning process.
                  </p>
                </div>
              </div>
              <div class="flex flex-1 gap-3 rounded-lg border border-[#d0d3e7] bg-[#f8f9fc] p-4 flex-col">
                <div class="text-[#0e101b]" data-icon="ShieldCheck" data-size="24px" data-weight="regular">
                  <ShieldCheckIcon />
                </div>
                <div class="flex flex-col gap-1">
                  <h2 class="text-[#0e101b] text-base font-bold leading-tight">
                    Efficiency in Cleaning and Sanitization
                  </h2>
                  <p class="text-[#4e5997] text-sm font-normal leading-normal">
                    Our cleaning processes are designed for maximum efficiency, ensuring that every area is thoroughly cleaned and sanitized. We use state-of-the-art equipment and tested methodologies to guarantee effective cleaning and sanitization of all spaces, big or small.
                  </p>
                </div>
              </div>
            </div>
          </div>
          
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
</script>
