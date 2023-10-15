<script lang="ts">
	const features = [
		{
			title: 'Upload & Organize',
			icon: 'upload',
			description:
				'Upload in bulk, organize content in categories, add custom filters & upload extras.'
		},
		{
			title: 'Stream On-Demand',
			icon: 'record',
			description: 'Showcase your content in a beautiful on-demand video catalog.'
		},
		{
			title: 'Stream live',
			icon: 'stream',
			description: 'Schedule events in advance & build excitement with a countdown overlay.'
		},
		{
			title: 'Monetization',
			icon: 'monetization',
			description: 'Offer subscriptions or one-time purchases. Accept credit cards & PayPal.'
		},
		{
			title: 'Analytics',
			icon: 'stream',
			description: 'Know what your audience likes & how your content is performing.'
		},
		{
			title: 'For all devices',
			icon: 'device',
			description: 'Get organized on all devices'
		}
	]
</script>

<section class="py-20 text-white bg-black">
  <div class="max-w-screen-xl mx-auto">
    <div class="flex flex-col md:flex-row items-center space-y-8 md:space-y-0 md:space-x-24">
      <div class="flex flex-col w-full md:w-1/2">
        <div class="flex flex-col space-y-4">
          <h1 class="text-4xl md:text-5xl font-bold font-heading">Reach more people in real time</h1>
          <p>
            The Screeno ecosystem is designed to help you generate profit. Set up complete sales and
            marketing funnels with ease using the Screeno
          </p>
        </div>
        <div class="flex mt-8 md:mt-12 space-x-3">
          <button class="w-full md:w-1/3 primary">Start Free Trial</button>
          <button class="w-full md:w-1/3 outline">Login</button>
        </div>
      </div>
      <div class="relative w-full md:w-1/2">
        <img src="/images/hero-image-desktop.png" class="w-full h-full" alt="Hero" />
        <img src="/images/hero-image-mobile.png" class="absolute -bottom-4 -left-3 hidden md:block" alt="Hero" />
      </div>
    </div>
		<div class="flex flex-wrap justify-center items-center mt-12 md:mt-32 space-y-4 md:space-y-0 md:space-x-4">
			<img
				src="/images/apple-tv.svg"
				class="transform transition duration-300 hover:scale-110 cursor-pointer"
				alt="Apple TV"
			/>
			<img
				src="/images/android-tv.svg"
				class="transform transition duration-300 hover:scale-110 cursor-pointer"
				alt="Android TV"
			/>
			<img
				src="/images/apple-watch.svg"
				class="transform transition duration-300 hover:scale-110 cursor-pointer"
				alt="Apple Watch"
			/>
			<img
				src="/images/iphone.svg"
				class="transform transition duration-300 hover:scale-110 cursor-pointer"
				alt="iPhone"
			/>
			<img
				src="/images/android.svg"
				class="transform transition duration-300 hover:scale-110 cursor-pointer"
				alt="Android"
			/>
		</div>
	</div>
</section>

<section class="py-20">
  <div class="max-w-screen-lg mx-auto">
    <div class="flex flex-col justify-center text-center">
      <div class="flex flex-col space-y-3">
        <h2 class="text-3xl md:text-4xl font-bold font-heading">All-in-one platform</h2>
        <p>You take care of the video quality and we take care of everything else</p>
      </div>
      <div class="flex justify-center mt-8 md:mt-12 space-x-8">
        <button class="w-1/3 primary">Start Free Trial</button>
        <button class="w-1/3 outline-dark">Login</button>
      </div>
    </div>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8 md:gap-12 mt-12 md:mt-20">
      {#each features as feature}
        <div class="flex flex-col p-4 space-y-3 hover:shadow-xl transition duration-300 cursor-pointer">
          <div class="flex space-x-3">
            <img src={`/icons/${feature.icon}.svg`} class="transform transition duration-300 hover:rotate-12" alt={feature.title} />
            <h5 class="font-bold font-heading">{feature.title}</h5>
          </div>
          <p>{feature.description}</p>
        </div>
      {/each}
    </div>
  </div>
</section>

<section class="py-20 text-white bg-black">
  <div class="flex flex-col max-w-screen-xl mx-auto space-y-12 md:space-y-32">
    <div class="flex flex-col justify-center">
      <h2 class="text-3xl md:text-4xl font-bold text-center font-heading">We help you grow</h2>
    </div>
    <div class="flex flex-col md:flex-row space-y-6 md:space-y-0 md:space-x-24">
      <div class="w-full md:w-1/2 space-y-3">
        <h5 class="text-2xl md:text-3xl font-semibold">Monetize your way</h5>
        <p>
          Set up subscriptions, rentals, or one-time buys for access to your VOD and live streams.
          Create exclusive experiences for your subscribers with coupons and promotions. One predictable fee, transparent pricing, and same-day setup.
        </p>
        <div class="flex space-x-3 cursor-pointer group">
          <p class="transition font-heading group-hover:font-bold">Get started</p>
          <img src="/icons/arrow.svg" class="transition transform group-hover:translate-x-1" alt="Arrow Icon" />
        </div>
      </div>
      <div class="relative w-full md:w-1/2">
        <img src="/images/monetization.png" alt="Monetize your way" class="w-full h-full" />
        <div class="absolute flex flex-col md:flex-row py-8 space-y-3 md:space-x-16 text-black bg-white px-9 rounded-3xl -top-4 -right-4">
					<div
						class="flex w-full px-3 py-4 space-x-16 font-semibold transition duration-300 transform bg-gray-100 font-heading rounded-xl hover:bg-blue-100 hover:text-primary hover:translate-x-1 hover:-translate-y-1 hover:shadow-xl"
					>
						<p>Donate</p>
						<p>45$</p>
					</div>
					<div
						class="flex w-full px-3 py-4 space-x-16 font-semibold transition duration-300 transform bg-gray-100 font-heading rounded-xl hover:bg-blue-100 hover:text-primary hover:translate-x-1 hover:-translate-y-1 hover:shadow-xl"
					>
						<p>Donate</p>
						<p>45$</p>
					</div>
					<div
						class="flex w-full px-3 py-4 space-x-16 font-semibold transition duration-300 transform bg-gray-100 font-heading rounded-xl hover:bg-blue-100 hover:text-primary hover:translate-x-1 hover:-translate-y-1 hover:shadow-xl"
					>
						<p>Donate</p>
						<p>45$</p>
					</div>
				</div>
			</div>
		</div>

		<div class="max-w-screen-xl mx-auto">
			<div class="flex flex-col md:flex-row justify-center md:items-center space-y-12 md:space-y-0 md:space-x-24">
				<div class="w-full md:w-1/2 relative">
					<img src="/images/optimized.png" class="w-full h-full" alt="Optimized for growth" />
					<div class="absolute px-4 py-3 bg-white -top-4 -right-4 rounded-2xl">
						<div class="relative">
							<img src="/icons/email-black.svg" alt="Email Icon" class="w-8 h-6" />
							<span class="absolute text-xs rounded-full -top-2 -right-2 bg-primary px-[6px] py-[1px] font-heading font-bold">1</span>
						</div>
					</div>
				</div>
				<div class="w-full md:w-1/2 flex flex-col justify-center space-y-6">
					<h5 class="text-3xl font-semibold">Optimized for growth</h5>
					<p>
						The Screeno ecosystem is designed to help you generate profit. Set up complete sales and
						marketing funnels with ease using the Screeno built-in marketing tools and integrations.
						Generate leads and convert your audience into paying subscribers, at no extra cost.
					</p>
					<div class="flex space-x-3 cursor-pointer group">
						<p class="transition font-heading group-hover:font-bold">Get started</p>
						<img src="/icons/arrow.svg" class="transition transform group-hover:translate-x-1" alt="Arrow Icon" />
					</div>
				</div>
			</div>
		</div>
</section>

<section class="pt-20 pb-40 text-white bg-black">
  <div class="flex flex-col max-w-screen-xl mx-auto space-y-12 md:space-y-32">
    <div class="flex flex-col space-y-3 text-center">
      <h2 class="text-3xl md:text-4xl font-bold font-heading">Start your own business today</h2>
      <p>Consistent quality and experience across all platforms and devices.</p>
    </div>
    <div class="flex justify-center space-x-8 mt-8 md:mt-14">
      <button class="w-1/3 primary">Get started</button>
      <button class="w-1/3 outline">Login</button>
    </div>
    <div class="relative mt-12 md:mt-20">
      <img src="/images/business-desktop.png" alt="Business Desktop" class="w-full h-full" />
      <img src="/images/business-mobile.png" alt="Business Mobile" class="absolute -bottom-12 -left-3 hidden md:block" />
    </div>
  </div>
</section>

<section class="pt-20 pb-32">
	<div class="flex flex-col justify-center space-y-3 text-center">
		<h2 class="text-4xl font-bold font-heading">Famous live on our platform</h2>
		<p>At the end of the day have fun with celebrities</p>
	</div>

	<div class="flex flex-col overflow-hidden mt-24 space-y-6">
		<div class="flex space-x-8">
			<img src="/images/showcase-1.png" alt="Showcase 1" class="w-[360px] h-[201px]" />
			<img src="/images/showcase-2.png" alt="Showcase 2" class="w-[360px] h-[201px]" />
			<img src="/images/showcase-3.png" alt="Showcase 3" class="w-[360px] h-[201px]" />
			<img src="/images/showcase-4.png" alt="Showcase 4" class="w-[360px] h-[201px]" />
		</div>
		<div class="flex space-x-8 -translate-x-72">
			<img src="/images/showcase-5.png" alt="Showcase 5" class="w-[360px] h-[201px]" />
			<img src="/images/showcase-6.png" alt="Showcase 6" class="w-[360px] h-[201px]" />
			<img src="/images/showcase-7.png" alt="Showcase 7" class="w-[360px] h-[201px]" />
			<img src="/images/showcase-8.png" alt="Showcase 8" class="w-[360px] h-[201px]" />
			<img src="/images/showcase-9.png" alt="Showcase 9" class="w-[360px] h-[201px]" />
		</div>
	</div>
</section>
