<script setup>
import IconLogo from './components/icons/IconLogo.vue'
import IconHomepage from './components/icons/IconHomepage.vue'
import IconConnection from './components/icons/iconConnection.vue'
import IconNetwork from './components/icons/IconNetwork.vue'
import IconNotification from './components/icons/IconNotification.vue'
import IconTool from './components/icons/IconTool.vue'
import IconArrowDown from './components/icons/IconArrowDown.vue'
import IconSettings from './components/icons/IconSettings.vue'
import IconGithub from './components/icons/IconGithub.vue'
import IconApple from './components/icons/IconApple.vue'
import IconTwitter from './components/icons/IconTwitter.vue'
import IconFace from './components/icons/IconFace.vue'
import IconHeart from './components/icons/IconHeart.vue'
import IconSend from './components/icons/IconSend.vue'
import IconChat from './components/icons/IconChat.vue'
import IconShare from './components/icons/IconShare.vue'
</script>

<template>
	<main class="bg-gray-100">
		<header class="mx-auto md:container flex items-center justify-between">
			<!-- Logo part -->
			<div class="flex items-center gap-x-4">
				<IconLogo class="w-10" />
				<input
					type="search"
					placeholder="Search"
					class="form-control block px-4 py-2 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded-xl"
				/>
			</div>
			<!-- navbar part -->
			<nav>
				<ul class="flex items-center gap-x-10">
					<li class="flex gap-x-3 cursor-pointer"><IconHomepage /> Homepage</li>
					<li class="flex gap-x-3 cursor-pointer">
						<IconConnection /> Connections
					</li>
					<li class="flex gap-x-3 cursor-pointer"><IconNetwork /> Messages</li>
					<li class="flex gap-x-3 items-center cursor-pointer">
						<IconNotification /> Notification
						<span class="bg-red-700 text-slate-200 px-2 rounded-full">2</span>
					</li>
				</ul>
			</nav>
			<!-- profile part -->
			<div class="flex items-center justify-between gap-x-2">
				<img src="./assets/images/head-3.png" alt="profile photo" class="w-7" />
				<p class="font-bold">Ershad Bashbag'</p>
				<IconArrowDown class="cursor-pointer" />
			</div>
		</header>
		<section
			class="mx-auto md:container flex justify-between gap-x-5 items-start"
		>
			<aside class="basis-1/4 border px-5 py-5 bg-white rounded-2xl">
				<div class="flex items-center justify-between gap-x-2">
					<img
						src="./assets/images/head-3.png"
						alt="profile photo"
						class="w-15"
					/>
					<div class="flex flex-col">
						<h1 class="font-bold">Ershad Bashbag'</h1>
						<p class="text-neutral-400">Istanbule,Turkey</p>
					</div>
					<IconSettings class="cursor-pointer" />
				</div>
				<h2 class="mt-8 mb-4 uppercase text-gray-400">Your Pages</h2>
				<div class="flex items-center justify-between mb-4">
					<div class="flex flex-row items-center">
						<IconTwitter />
						<div class="flex flex-col ml-3">
							<h1 class="font-bold">Twitter</h1>
							<p class="text-gray-300">Social Media Platform</p>
						</div>
					</div>
					<span class="bg-red-700 text-slate-200 px-2 rounded-full">2</span>
				</div>
				<a href="#" class="text-blue-400 font-bold">View All</a>
				<h2 class="mt-4 mb-4 uppercase text-gray-400">Your Projects</h2>
				<div class="flex items-center justify-between">
					<div class="flex flex-row items-center">
						<IconGithub />
						<div class="flex flex-col ml-3">
							<h1 class="font-bold">Github</h1>
							<p class="text-gray-300">Coding Platform</p>
						</div>
					</div>
					<span class="bg-red-700 text-slate-200 px-2 rounded-full">2</span>
				</div>
				<div class="flex items-center justify-between">
					<div class="flex flex-row items-center mt-4 mb-4">
						<IconApple />
						<div class="flex flex-col ml-3">
							<h1 class="font-bold">Apple</h1>
							<p class="text-gray-300">Business Company</p>
						</div>
					</div>
					<span class="bg-red-700 text-slate-200 px-2 rounded-full">2</span>
				</div>
				<a href="#" class="text-blue-400 font-bold">View All</a>
			</aside>
			<header>
				<section class="basis-1/2 border px-8 py-5 bg-white rounded-2xl">
					<div class="flex items-center gap-x-5 relative">
						<img src="./assets/images/head-2.png" />
						<input
							type="text"
							placeholder="Share something..."
							class="border px-4 py-4 w-full rounded-full outline-0 bg-gray-200"
						/>
						<IconFace class="absolute right-5 text-gray-400" />
					</div>
					<div class="flex justify-between mt-8">
						<ul class="flex items-center gap-x-8">
							<li><a href="#">Image</a></li>
							<li><a href="#">Video</a></li>
							<li><a href="#">Attachment</a></li>
							<li><a href="#">Hashtag</a></li>
							<li><a href="#">Mention</a></li>
						</ul>
						<div class="flex justify-between items-center gap-x-4">
							<p class="text-gray-300">Public</p>
							<span><IconArrowDown class="text-gray-300" /></span>
						</div>
					</div>
				</section>
				<br />

				<section class="basis-1/2 border px-8 py-5 bg-white rounded-2xl">
					<div class="flex gap-x-4 items-center">
						<img src="./assets/images/head-4.png" />
						<div>
							<h1 class="font-bold">Alan Patterson</h1>
							<p class="text-gray-400">2 hours ago</p>
						</div>
					</div>
					<p class="pt-4">
						Was great meeting up with Anna an Kate Bishop at the breakfast talk!
					</p>
					<span class="text-blue-400 font-bold">#breakfast</span>
					<img src="./assets/images/farm design.png " class="w-96 mt-5" />
					<div class="flex items-center justify-between">
						<div class="flex gap-x-4 items-center mt-5">
							<div class="flex items-center gap-x-3">
								<IconHeart class="text-red-600" />
								<span>45</span>
							</div>
							<div class="flex items-center gap-x-3">
								<IconChat />
								<span>16</span>
							</div>
							<div>
								<IconShare />
							</div>
						</div>
						<IconSend />
					</div>
				</section>
			</header>
			<aside class="basis-1/4"></aside>
		</section>
	</main>
</template>

<style scoped></style>
