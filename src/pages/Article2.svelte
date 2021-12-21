<script>
    import {Link } from "svelte-routing";
  </script>
  
  <div>
      <div class="flex flex-col">
          <Link to="/"><button class="m-5 p-3 w-20 bg-indigo-500 text-white rounded-full hover:bg-indigo-700">Back</button></Link>
          <h1 class="p-7 text-5xl text-gray-700">Contracts</h1>
      </div>
  
  <p class="p-7 text-2xl text-gray-900">Contracts in Solidity are similar to classes in object-oriented languages. 
      They contain persistent data in state variables, and functions that can modify these variables. 
      Calling a function on a different contract (instance) will perform an EVM function call and 
      thus switch the context such that state variables in the calling contract are inaccessible. 
      A contract and its functions need to be called for anything to happen. 
      There is no “cron” concept in Ethereum to call a function at a particular event automatically.</p>
  
  </div>
  
  <style>
  
  </style>