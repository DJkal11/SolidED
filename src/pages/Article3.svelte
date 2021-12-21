<script>
    import {Link } from "svelte-routing";
  </script>
  
  <div>
      <div class="flex flex-col">
          <Link to="/"><button class="m-5 p-3 w-20 bg-indigo-500 text-white rounded-full hover:bg-indigo-700">Back</button></Link>
          <h1 class="p-7 text-5xl text-gray-700">Transactions</h1>
      </div>
  
  <p class="p-7 text-2xl text-gray-900">A blockchain is a globally shared, transactional database. 
      This means that everyone can read entries in the database just by participating in the network. 
      If you want to change something in the database, you have to create a so-called transaction which has to be accepted by all others. 
      The word transaction implies that the change you want to make (assume you want to change two values at the same time) 
      is either not done at all or completely applied. Furthermore, while your transaction is being applied to the database, 
      no other transaction can alter it.

    As an example, imagine a table that lists the balances of all accounts in an electronic currency. 
    If a transfer from one account to another is requested, the transactional nature of the database ensures that if the amount is 
    subtracted from one account, it is always added to the other account. If due to whatever reason, adding the amount to 
    the target account is not possible, the source account is also not modified.
    
    </p>
  
  </div>
  
  <style>
  
  </style>