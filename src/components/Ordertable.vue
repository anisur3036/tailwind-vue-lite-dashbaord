<template>
	<div>
		<h1 class="text-xl mb-2">Your orders</h1>
		<div class="overflow-hidden hover:overflow-auto rounded-lg shadow">
		  <table class="w-full">
		    <thead class="bg-gray-50 border-b-2 border-gray-200">
		      <tr>
		        <th class="w-20 p-3 text-sm font-semibold tracking-wide text-left">No.</th>
		        <th class="p-3 text-sm font-semibold tracking-wide text-left">Details</th>
		        <th class="w-24 p-3 text-sm font-semibold tracking-wide text-left">Status</th>
		        <th class="w-20 p-3 text-sm font-semibold tracking-wide text-left">Date</th>
		        <th class="w-30 p-3 text-sm font-semibold tracking-wide text-left">Total</th>
		      </tr>
		    </thead>
		    <tbody class="divide-y-2 divide-gray-200">
		      <tr class="bg-white">
		        <td class="p-3 text-sm text-gray-700 whitespace-nowrap">
		          <a class="font-bold text-blue-500 hover:underline" href="#">12345</a>
		        </td>
		        <td class="p-3 text-sm text-gray-700 whitespace-nowrap">Iphone 9X</td>
		        <td class="p-3 text-sm text-gray-700 whitespace-nowrap">
		          <span
		            class="p-1.5 uppercase text-sm tracking-wider bg-green-300 bg-opacity-50 text-yellow-800 rounded-lg"
		          >Shiped</span>
		        </td>
		        <td class="p-3 text-sm text-gray-700 whitespace-nowrap">12/12/2021</td>
		        <td class="p-3 text-sm text-gray-700 whitespace-nowrap">100000Tk</td>
		      </tr>
		      <tr class="bg-gray-100">
		        <td class="p-3 text-sm text-gray-700 whitespace-nowrap">
		          <a class="font-bold text-blue-500 hover:underline" href="#">45214</a>
		        </td>
		        <td class="p-3 text-sm text-gray-700 whitespace-nowrap">Lorem ipsum dolor sit amet</td>
		        <td class="p-3 text-sm text-gray-700 whitespace-nowrap">
		          <span
		            class="p-1.5 uppercase text-sm tracking-wider bg-green-300 bg-opacity-50 text-yellow-800 rounded-lg"
		          >Deleverd</span>
		        </td>
		        <td class="p-3 text-sm text-gray-700 whitespace-nowrap">12/12/2021</td>
		        <td class="p-3 text-sm text-gray-700 whitespace-nowrap">100000Tk</td>
		      </tr>
		      <tr class="bg-white">
		        <td class="p-3 text-sm text-gray-700 whitespace-nowrap">
		          <a class="font-bold text-blue-500 hover:underline" href="#">44345</a>
		        </td>
		        <td
		          class="p-3 text-sm text-gray-700 whitespace-nowrap"
		        >Amet consectetur adipisicing elit</td>
		        <td class="p-3 text-sm text-gray-700 whitespace-nowrap">
		          <span
		            class="p-1.5 uppercase text-sm tracking-wider bg-red-300 bg-opacity-50 text-yellow-800 rounded-lg"
		          >cancel</span>
		        </td>
		        <td class="p-3 text-sm text-gray-700 whitespace-nowrap">12/12/2021</td>
		        <td class="p-3 text-sm text-gray-700 whitespace-nowrap">100000Tk</td>
		      </tr>
		    </tbody>
		  </table>
		</div>
	</div>
</template>