<script>
import { Router, Route} from "svelte-routing";
import Article1 from "./pages/Article1.svelte";
import Article2 from "./pages/Article2.svelte";
import Article3 from "./pages/Article3.svelte";
import Homepage from "./pages/Homepage.svelte";
import BeginnersGuide from "./pages/Beginners-guide.svelte";
</script>

<Router>
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