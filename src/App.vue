<script setup>
import IconLogo from './components/icons/IconLogo.vue'
import IconHomepage from './components/icons/IconHomepage.vue'
import IconConnection from './components/icons/iconConnection.vue'
import IconNetwork from './components/icons/IconNetwork.vue'
import IconNotification from './components/icons/IconNotification.vue'
import IconTool from './components/icons/IconTool.vue'
import IconArrowDown from './components/icons/IconArrowDown.vue'
</script>

<template>
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
				<li class="flex gap-x-3"><IconHomepage /> Homepage</li>
				<li class="flex gap-x-3"><IconConnection /> Connections</li>
				<li class="flex gap-x-3"><IconNetwork /> Messages</li>
				<li class="flex gap-x-3 items-center">
					<IconNotification /> Notification
					<span class="bg-red-700 text-slate-200 px-2 rounded-full">2</span>
				</li>
			</ul>
		</nav>
		<!-- profile part -->
		<div class="flex items-center justify-between gap-x-2">
			<img src="./assets/images/head-1.png" alt="profile photo" class="w-7" />
			<p>Ershad Bashbag'</p>
			<IconArrowDown class="cursor-pointer" />
		</div>
	</header>
</template>

<style scoped></style>
