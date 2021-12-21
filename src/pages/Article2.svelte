<script>
    import {Link } from "svelte-routing";
    import FaArrowLeft from 'svelte-icons/fa/FaArrowLeft.svelte'
  </script>
  
  <div>
      <div class="flex flex-col">
        <Link to="/"><button class="m-20 mb-2 mt-10 p-2 w-10 text-gray-700 h-10"><FaArrowLeft /></button></Link>
          <h1 class="p-20 pb-0 pt-5 text-2xl font-bold text-gray-700">Contracts</h1>
      </div>
  
  <p class="p-20 pb-0 pt-5 text-gray-900">Contracts in Solidity are similar to classes in object-oriented languages. 
      They contain persistent data in state variables, and functions that can modify these variables. 
      Calling a function on a different contract (instance) will perform an EVM function call and 
      thus switch the context such that state variables in the calling contract are inaccessible. 
      A contract and its functions need to be called for anything to happen. 
      There is no “cron” concept in Ethereum to call a function at a particular event automatically.</p>
  
  </div>
  
  <style>
  
  </style>