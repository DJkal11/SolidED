<script>
  import {Link } from "svelte-routing";
  import FaArrowLeft from 'svelte-icons/fa/FaArrowLeft.svelte'
</script>

<div>
    <div class="flex flex-col">
        <Link to="/"><button class="m-20 mb-2 mt-10 p-2 w-10 text-gray-700 h-10"><FaArrowLeft /></button></Link>
        <h1 class="p-20 pb-0 pt-5 text-2xl font-bold text-gray-700">Solidity</h1>
    </div>

<p class="p-20 pb-0 pt-5 text-gray-900">Solidity is an object-oriented, high-level language for implementing smart contracts. Smart contracts are programs which govern the behaviour of accounts within the Ethereum state.

    Solidity is a curly-bracket language. It is influenced by C++, Python and JavaScript, and is designed to target the Ethereum Virtual Machine (EVM). You can find more details about which languages Solidity has been inspired by in the language influences section.
    
    Solidity is statically typed, supports inheritance, libraries and complex user-defined types among other features.
    
    With Solidity you can create contracts for uses such as voting, crowdfunding, blind auctions, and multi-signature wallets.
    
    When deploying contracts, you should use the latest released version of Solidity. 
    Apart from exceptional cases, only the latest version receives security fixes. 
    Furthermore, breaking changes as well as new features are introduced regularly. 
    We currently use a 0.y.z version number to indicate this fast pace of change.</p>

</div>

<style>

</style>