---
title: Ikcerog's SWG Legends Adventures 
---
<div class="blog-container">
  <div class="blog-post">
    <h2>Post Title 1</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
    <a href="#">Read more</a>
  </div>

  <div class="blog-post">
    <h2>Post Title 2</h2>
    <p>Ut enim ad minim veniam, quis nostrud exercitation ullamco.</p>
    <a href="#">Read more</a>
  </div>

  <div class="blog-post">
    <h2>Post Title 3</h2>
    <p>Duis aute irure dolor in reprehenderit in voluptate velit esse.</p>
    <a href="#">Read more</a>
  </div>
</div>

<div class="galaxy">
    <div class="card-container">
      <div class="card jedi">
        <div class="card-header">
          <h2>Luke Skywalker</h2>
        </div>
        <div class="card-body">
          <p>The last hope of the Jedi.</p>
        </div>
      </div>
      <div class="card rebel">
        <div class="card-header">
          <h2>Princess Leia</h2>
        </div>
        <div class="card-body">
          <p>Royal diplomat and leader of the Rebel Alliance.</p>
        </div>
      </div>
      <div class="card sith">
        <div class="card-header">
          <h2>Darth Vader</h2>
        </div>
        <div class="card-body">
          <p>The dark lord of the Sith.</p>
        </div>
      </div>
    </div>
  </div>

<style>
  /*@import url('https://fonts.googleapis.com/css2?family=Oswald:wght@200;400;700&display=swap');

  * {
    font-family: Oswald !important;
  }*/

  
  
  .blog-container {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
  }

  .blog-post {
    flex: 0 0 calc(33.33% - 20px);
    padding: 10px;
    border: 1px solid #ccc;
    margin: 10px;
  }

body {
  font-family: 'Arial', sans-serif;
  margin: 0;
  padding: 0;
  background-color: #000;
  color: #fff;
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
}

.galaxy {
  position: relative;
  width: 100%;
  height: 100vh;
  background: radial-gradient(ellipse at center, #000 0%, #111 100%);
  overflow: hidden;
}

.stars {
  width: 1px;
  height: 1px;
  background-color: #fff;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  animation: twinkle 5s infinite;
  opacity: 0;
  transition: opacity 0.5s;
}

@keyframes twinkle {
  0%, 100% { opacity: 0; }
  10%, 90% { opacity: 1; }
}

.card-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  padding: 20px;
}

.card {
  width: 300px;
  margin: 20px;
  background-color: rgba(0, 0, 0, 0.8);
  border: 1px solid #444;
  border-radius: 10px;
  box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.3);
  display: flex;
  flex-direction: column;
}

.card-header {
  padding: 20px;
  background-color: rgba(0, 0, 0, 0.6);
  border-top-left-radius: 10px;
  border-top-right-radius: 10px;
}

.card-header h2 {
  margin: 0;
  text-align: center;
}

.card-body {
  padding: 20px;
}

.card-body p {
  margin: 0;
}

.jedi {
  background-color: #2B96C4;
}

.rebel {
  background-color: #E63946;
}

.sith {
  background-color: #DAA520;
}

  
</style>
