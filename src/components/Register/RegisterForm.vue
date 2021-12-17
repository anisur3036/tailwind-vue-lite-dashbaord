<template>
	<div>
		<form class="mt-10">
			<div class="relative">
				<input
					type="email"
					id="email"
					name="email"
					class="peer h-10 w-full border-b-2 border-gray-300 text-gray-900 placeholder-transparent focus:outline-none focus:border-rose-600"
					placeholder="Email address"
				/>
				<label for="email" class="absolute left-0 -top-3.5 text-gray-600 text-sm transition-all peer-placeholder-shown:text-base peer-placeholder-shown:text-gray-400 peer-placeholder-shown:top-2 peer-focus:-top-3.5 peer-focus:text-gray-600 peer-focus:text-sm">Email address</label>
			</div>
			<div class="mt-6">
				<input 
					type="password" 
					id="password" 
					name="password" 
					class="h-10 w-full border-b-2 border-gray-300 text-gray-900 focus:outline-none focus:border-rose-600"
					placeholder="Password" 
				/>

			</div>
		</form>

	</div>	
</template>