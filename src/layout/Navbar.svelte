  <script>
    import { Link } from 'svelte-routing';
  </script>
  
  <nav>
    <div class="nav-wrapper">
     <div class = "container">
        <Link to="/"><span class="brand-logo">Linguage</span></Link>
        <ul id="nav-mobile" class="right hide-on-med-and-down">
        <li><Link to="/">Explore</Link></li>
        <li><Link to="/">Compare</Link></li>
        <li><Link to="/">Create</Link></li>
      </ul>
     </div>
    </div>
  </nav>