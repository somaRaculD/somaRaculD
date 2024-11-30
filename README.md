<head>
  <style>
    @keyframes showWelcome {
      from {
        opacity: 0;
        transform: translateY(16px);
      }
      to {
        opacity: 1;
      }
  }
    .welcome {
      margin-bottom: 24px;
      animation: 1s showWelcome ease-in-out;
background: linear-gradient(to right, #f26b13, #f11111);
 padding: 16px 24px; 
 border-radius: 8px; box-shadow: -4px 4px 10px rgba(0, 0, 0, 0.1);
backdrop-filter: blur(5px);
-webkit-backdrop-filter: blur(5px);
border: 1px solid rgba(255, 255, 255, 0.3); color:white;
    }
    .icon {
      padding: 2px;
      background: #117baa;
      width: 30px;
      height: 30px;
      padding: 12px;
      display: flex;
      justify-content: center;
      align-items: center;
      margin: 4px 0;
      border-radius: 30px;
      background: linear-gradient(to right, #f26b13, #f11111);
      font-weight: 700;
      color: white;
      cursor: pointer;
      position: relative;
      overflow: hidden;
      box-shadow: -2px 3px 5px #ccc;
    }
    .icon:hover > .glass{
      delay: 1s;
      height: 100%;
      width: 100%;
      display: block;
      position: absolute;
      bottom:0;
      z-index: 2;
    }
    .glass {
      display: none;
      float: none;
      background: rgba(0,0,0,.2);
      animation: showWelcome 500ms ease-in-out;
      border-radius: 30px;
    }
  </style>
 </head>
<div>

  <h1 class="welcome">Bem Vindo</h1>
  <div style='font-size: 15px; margin-bottom: 12px'>Sou um jovem principiante na programação...continuando a nadar nesse mar de criação</div>

<div id="embed-iframe">
<iframe style="border-radius:12px" src="https://open.spotify.com/embed/album/2KSWrd22LGc0Hmqs2Z5i7z?utm_source=generator" width="100%" height="352" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
</div>

<div class="icon">JS <div class="glass"></div>
</div>

<div class="icon">JAVA <div class="glass"></div></div>

<div class="icon">PHP <div class="glass"></div></div>

<div class="icon">GO <div class="glass"></div></div>
</div>
