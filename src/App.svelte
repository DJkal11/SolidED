<script>
import { Router, Route} from "svelte-routing";
import Article1 from "./pages/Article1.svelte";
import Article2 from "./pages/Article2.svelte";
import Article3 from "./pages/Article3.svelte";
import Homepage from "./pages/Homepage.svelte";
import BeginnersGuide from "./pages/Beginners-guide.svelte";
</script>

<Router>
	<header class="bg-gray-100 p-10">
	<nav class="pb-3 px-14">
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
	</header>

	<Route path="/" component="{Homepage}" /> 
	<Route path="/Article1" component="{Article1}" /> 
	<Route path="/Article2" component="{Article2}" /> 
	<Route path="/Article3" component="{Article3}" /> 
    <Route path="/BeginnersGuide" component="{BeginnersGuide}" /> 

	
</Router>

<style global lang="postcss">
	@tailwind base;
	@tailwind components;
	@tailwind utilities;
  </style>