<script>
	let title = window.location.pathname.slice(1).replaceAll("-", " ").toUpperCase();
</script>

<main>
  <title>Scratch News | {title}</title>

  <div class="navbar">
    <h3>Scratch News | <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ">Home</a> | <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ">Posts</a></h3>
  </div>
  <h1 id="title">{title}</h1>

  <div class="yt">
     <iframe id="iframe" width="auto" height="auto" src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allow=""></iframe>
    <div class="button">
      <span>⸻ Load Article ⸻</span>
    </div>
  </div>
</main>

<style>
  :root {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen,
      Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  }

  main {
    text-align: center;
    padding: 1em;
    margin: 0;
  }

  img {
    height: 16rem;
    width: 16rem;
  }

  h1 {
    color: white;
    text-transform: uppercase;
    font-size: 4rem;
    font-weight: 300;
    line-height: 1.1;
    margin: 2rem auto;
    max-width: 14rem;
    background-image: url(./bg.jpg);
    padding: 30px;
    background-position: center;
    background-size: cover;
  }

  h3 {
    margin-top: 0;
    color: coral;
    font-weight: 300;
  }

  p {
    max-width: 14rem;
    margin: 1rem auto;
    line-height: 1.35;
  }

  a {
    color: coral;
    text-decoration: none;
  }

  iframe {
    opacity: 0.1%;
    border-radius: 10px;
    width: 76px;
    height: 20px;
    transform: scaleX(5);
  }

  .navbar {
    border-bottom: #e9e9e9 2px solid;
  }

  .yt {
    display: flex;
    justify-content: center;
  }

  .button {
    position: absolute;
    z-index: -1;
    background-color: white;
    border-radius: 10px;
    width: 380px;
    text-align: center;
    color: coral;
  }


  @media (min-width: 480px) {
    h1 {
      max-width: none;
    }

    p {
      max-width: none;
    }
  }
</style>
