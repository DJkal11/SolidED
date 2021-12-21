<script>
    import {Link } from "svelte-routing";
  </script>
  
  <div>
      <div class="flex flex-col">
          <Link to="/"><button class="m-5 p-3 w-20 bg-indigo-500 text-white rounded-full hover:bg-indigo-700">Back</button></Link>
          <h1 class="p-7 text-5xl text-gray-700">Beginners guide to Svelte and Web3</h1>
      </div>
  
  <p class="p-7 text-2xl text-gray-900">Svelte provides a different approach to building web apps than some of the other 
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