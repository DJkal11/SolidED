<script>
import {Link } from "svelte-routing";
import BeginnersGuide from "./Beginners-guide.svelte";
</script>

<body class="bg-white">
	<header class="bg-gray-100 p-10" style="padding-bottom: 5rem;">
	  <nav class="pb-14 px-14">
		<div class="flex justify-between items-center">
		  <h1 class="pr-6 border-r-2 text-2xl font-bold text-gray-500">Intern Academy</h1>
		  <div class="flex justify-between flex-grow">
			<div class="flex ml-6 items-center font-bold text-gray-500">
			  <h1>An OpenSource repository for Web3 knowledge</h1>
			</div>
			<div class="md:flex space-x-6 hidden">
			  <span class="text-gray-500 text-md">+ Add your article</span>
			</div>
		  </div>
		</div>
	  </nav>
	  <!-- Section Hero -->
	  <div class="container mx-auto bg-gray-400 h-96 rounded-md flex items-center outline outline-4  outline-offset-2 outline-violet-500">
		<div class="sm:ml-20 text-gray-50 text-center sm:text-left">
		  <h1 class="text-5xl font-bold mb-4">
			Article of the week
		  </h1>
		  <p class="text-lg inline-block sm:block">The beginners guide to Svelte and Web3</p>
		  <Link to="/BeginnersGuide"><button class="mt-8 px-4 py-2 bg-violet-600 rounded hover:bg-indigo-800">Read article</button></Link>
		</div>
	  </div>
	</header>
	<main class="py-16 container mx-auto px-4 md:px-0">
	  <section>
		<h1 class="text-3xl font-bold text-gray-600 mb-10">More content</h1>
		<div class="grid sm:grid-cols-3 gap-4 grid-cols-2">
		  <div>
			<div class="bg-gray-300 h-44"></div>
			<Link to="/Article1"><h3 class="text-lg font-semibold text-gray-500 mt-4 pl-4 hover:text-gray-700">Article 1</h3></Link>
			<p class="p-4">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
		  </div>
		  <div>
			<div class="bg-gray-300 h-44"></div>
			<Link to="/Article2"><h3 class="text-lg font-semibold text-gray-500 mt-4 pl-4 hover:text-gray-700">Article 2</h3></Link>
			<p class="p-4">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
		  </div>
		  <div>
			<div class="bg-gray-300 h-44"></div>
			<Link to="/Article3"><h3 class="text-lg font-semibold text-gray-500 mt-4 pl-4 hover:text-gray-700">Article 3</h3></Link>
			<p class="p-4">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
		  </div>
		</div>
		<hr class="w-40 my-14 border-4 rounded-md sm:mx-0 mx-auto" />
	  </section>
	  <section>
		<h1 class="inline-block text-gray-600 font-bold text-3xl">
		  How to create content
		</h1>
  
		<div class="grid grid-cols-3 gap-4 mt-10">
		  <div>
			<h3 class="text-lg font-semibold text-gray-500 mt-2">1.Go to the Github Repo</h3>
			<p class="text text-gray-400">Start by searching for a location. Once you find a sauna you like, simply check the availability, book it, and make a secure payment right away.</p>
		  </div>
		  <div>
			<h3 class="text-lg font-semibold text-gray-500 mt-2">2. Have a great bath</h3>
			<p class="text text-gray-400">Meet your host on the date you chose and enjoy the home sauna experience. We'll handle the payment to the host after your experience.</p>
		  </div>
		  <div>
			<h3 class="text-lg font-semibold text-gray-500 mt-2">3. Review the host</h3>
			<p class="text text-gray-400">If you enjoyed the experience, let others know by giving a review to your sauna host. This way others will know where to go.</p>
		  </div>
		</div>
	  </section>
	  <div class="mt-14">
		<p>Ps. You can also become a Saunatime host in few clicks!</p>
	  </div>
	</main>
	<footer class="mb-6 px-6 md:px-0">
	  <div class="grid gap-5 grid-cols-5 container mx-auto space-x-6">
		<div>
		  <h1 class="text-2xl font-bold text-gray-500">Intern Academy</h1>
		  <p>The largest online community to rent saunas in Finland.</p>
		  <spa>© 0xIntern 2021.</spa>
		</div>
		<div class="pt-2">
		  <ul>
			<li>About us</li>
			<li>F.A.Q</li>
			<li>Help</li>
		  </ul>
		</div>
		<div class="pt-2">
		  <div>
			<div class="flex space-x-4 text-gray-500 text-center">
			  <span
				><svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
				  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8.228 9c.549-1.165 2.03-2 3.772-2 2.21 0 4 1.343 4 3 0 1.4-1.278 2.575-3.006 2.907-.542.104-.994.54-.994 1.093m0 3h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z" /></svg
			  ></span>
			  <span
				><svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
				  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" /></svg
			  ></span>
			  <span
				><svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
				  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 8l2-2m0 0l2-2m-2 2l-2-2m2 2l2 2M5 3a2 2 0 00-2 2v1c0 8.284 6.716 15 15 15h1a2 2 0 002-2v-3.28a1 1 0 00-.684-.948l-4.493-1.498a1 1 0 00-1.21.502l-1.13 2.257a11.042 11.042 0 01-5.516-5.517l2.257-1.128a1 1 0 00.502-1.21L9.228 3.683A1 1 0 008.279 3H5z" /></svg
			  ></span>
			</div>
			<div class="flex mt-12">
			  <p>Privacy & Cookies</p>
			  <p>Terms of use</p>
			</div>
		  </div>
		</div>
	  </div>
	</footer>
  </body>

  <style global lang="postcss">
	@tailwind base;
	@tailwind components;
	@tailwind utilities;
  </style>