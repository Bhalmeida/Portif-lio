# Portif-lio
Projetos

!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Redes Sociais</title>
</head>
<body>
    
<div class="conteiner">

<div class="tree conteiner">

    <div class="avatar">
     <img src="./capa.png" alt="">
    </div>

     <span class="insta-user">@bhianca_cca</span>

     <div class="links-container">
     <a href="" class="link">link1</a>
      <a href="" class="link">link2</a>
      <a href="" class="link">link3</a>
     </div>

     <div class="socials container">
        <a href="" class="social">
            <img src="./instagram.svg" alt="">
            <img src="./github.svg" alt="">
            <img src="./linkedin.svg" alt="">
        </a>
     
    </div>

</div>

</div>

</body>
</html>

<link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@1,300;1,600&display=swap" rel="stylesheet">

:root {
    --white-light: #FAF7FD;
    --purple: #BB99DD;
  }

  * {

    margin: 0;
    padding: 0;
    box-sizing: border-box;
    text-decoration: none;
  }

  body, html {
    font-family: 'poppins', sans-serif
    background; var:(#FAF7FD); 

  }

 .container {
   width: 100vw;
   height: 100vh;

   display: flex;
   align-items: center;
   justify-content: center;
}

.container .tree-container  {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

.tree-container .avatar {
  width: 213px;
  height: 213px;

   display: flex;
   align-items: center;
   justify-content: center;

   border: 1px solid var(--purple)
   border-radius: 50%;
}

.tree-container .avatar img {
    width: 200px;
    height: 200px;
}
