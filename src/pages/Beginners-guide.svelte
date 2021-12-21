<script>
    import {Link } from "svelte-routing";
    import FaArrowLeft from 'svelte-icons/fa/FaArrowLeft.svelte'
  </script>
  
  <div>
      <div class="flex flex-col">
        <Link to="/"><button class="m-20 mb-2 mt-10 p-2 w-10 text-gray-700 h-10"><FaArrowLeft /></button></Link>
          <h1 class="p-20 pb-0 pt-5 text-2xl font-bold text-gray-700">Beginners guide to Svelte and Web3</h1>
      </div>
  
  <p class="p-20 pb-0 pt-5 text-gray-900">Svelte provides a different approach to building web apps than some of the other 
      frameworks covered in this module. While frameworks like React and Vue do the bulk of their work in the user's browser 
      while the app is running, Svelte shifts that work into a compile step that happens only when you build your app, 
      producing highly-optimized vanilla JavaScript.

    The outcome of this approach is not only smaller application bundles and better performance, 
    but also a developer experience that is more approachable for people that have limited experience of the modern tooling ecosystem.
    
    Svelte sticks closely to the classic web development model of HTML, CSS, and JS, just adding a few extensions to HTML and JavaScript.
     It arguably has fewer concepts and tools to learn than some of the other framework options.
    
    Its main current disadvantages are that it is a young framework — its ecosystem is therefore more limited in terms of tooling, 
    support, plugins, clear usage patterns, etc. than more mature frameworks, and there are also fewer job opportunities. 
    But its advantages should be enough to make you interested to explore it.
    
    </p>
  
  </div>
  
  <style>
  
  </style>