<template>
	<form method="get" action="/" class="max-w-md mx-auto bg-white rounded-lg shadow overflow-hidden px-12 py-6 space-y-10">
		<h2 class="text-2xl font-bold text-center">Register</h2>
		<div class="relative border-2 py-1 rounded focus-within:border-blue-500">
			<input type="text" name="name" placeholder="Name" class="placeholder-transparent floating-input px-2 block w-full appearance-none focus:outline-none bg-transparent" />
			<label for="name" class="absolute cursor-pointer bg-white px-0.5 top-[2px] left-2 -z-1 duration-300">Name</label>
		</div>
		<div class="relative border-2 py-1 rounded focus-within:border-blue-500">
			<input type="text" name="email" placeholder=" " class="floating-input px-2 block w-full appearance-none focus:outline-none bg-transparent" />
			<label for="email" class="absolute bg-white px-0.5 top-[2px] left-2 -z-1 duration-300">Email</label>
		</div>
		<div class="relative border-2 py-1 rounded focus-within:border-blue-500">
			<input type="password" name="password" placeholder=" " class="floating-input px-2 block w-full appearance-none focus:outline-none bg-transparent" />
			<label for="password" class="absolute bg-white px-0.5 top-[2px] left-2 -z-1 duration-300">Password</label>
		</div>
		<div class="relative border-2 py-1 rounded focus-within:border-blue-500">
			<input type="password" name="password_confirm" placeholder=" " class="floating-input px-2 block w-full appearance-none focus:outline-none bg-transparent" />
			<label for="password_confirm" class="absolute bg-white px-0.5 top-[2px] left-2 -z-1 duration-300">Password Confirm</label>
		</div>
		<div class="flex items-center justify-end">
			<button class="px-8 py-2 w-full rounded bg-blue-600 text-white font-semibold text-sm focus:ring-1 focus:outline-none">Register</button>
		</div>
		<div>
			<p class="-mt-6 text-center text-sm text-gray-500">If you already register please <a href="#" class="text-blue-500">login</a> here.</p>
		</div>
	</form>
</template>