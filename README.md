# Google-page
page google pour me m'améliorer 


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="syles.css">
    <script src="https://kit.fontawesome.com/7101c27beb.js" crossorigin="anonymous"></script>

    <title>Document</title>
</head>
<body>
    <section>
        <header>
            <ul>
              
    <div class="link">

      

        <a href="https://mail.google.com/mail/u/0/?tab=rm&ogbl#inbox" target="_blank" class="lien">Gmail</a>



        <a href="https://mail.google.com/mail/u/0/?tab=rm&ogbl#inbox" class="lien2">images</a>

        <img src="bars.png" alt="">
       
        <button id="hamburger-btn">
            <img src="images.jpg" alt="Logo" class="image">
           
          </button>

          
     
        

         </div>
      
 
                
        
            </ul>
        </header>
        <div class="main">
            <img src="google.png" alt="">
            <div class="searchbox">
                <form action="https://www.google.com/search" method="get">
                <input type="text" class="search"  name="q" placeholder="  Rechercher sur Google ou saisir une URL">
                <div class="icons">
                    <div><img src="search.png" alt=""></div>
                    <div><img src="mic.png" alt=""></div>
                </div>
                 </div>
                 <div class="buttons">

                 </div>
                 <div class="favs">
                    <div class="fav">
                    <span class="text">. . .</span>
                        
                      <div class="round">
                      <a href="https://discord.com/channels/@me/1060248338877919252" target="_blank"> <img src="discord.png" alt="" class="dis"></a> 
                      </div>
                      <p>Discord<p>
                    </div>
                    <div class="fav">
                        <span class="text">...</span>
                      <div class="round">
                      <a href="https://chat.openai.com/" target="_blank">  <img src="chat.png" alt="" class="chatt"></a>
                      </div>
                      <p>Chat-GPt <p>
                    </div>
                     <div class="fav">
                        <div class="dot"></div>
                        <div class="dot"></div>
                        <div class="dot"></div>
                      <div class="round">
                        <a href="https://chat.openai.com/" target="_blank">  <img src="download.png" alt="" class="chatt"></a>
                      </div>
                      <p>Ajoutez  <p>
                    </div>
                    
                  </div>
        </div> 
    </section>
    

</body>
</html>


<style>
    *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;

}
section{
    position: relative;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
}
section header{
    position: absolute;
    top: 0;
    width: 100%;
    display: flex;
    justify-content: flex-end;
    padding: 20px;
}

section header ul {
    display: flex;
    justify-content: center;
    align-items: center;
}


section .main{
    width: 580px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
 
} 

section .main .searchbox{
    position: relative;
    width: 100%;
    margin-top: 20px;

}
section .main .searchbox .search{
    width: 100%;
    padding: 13px;
    padding-left: 45px;
    padding-right: 60px;
    border-radius: 30px;
    border: 1px solid #ccc;
    outline: none;
    font-size: 16px;
}

section .main .searchbox .icons{
  position: absolute;
  top: 0;
  width: 100%;
  display:flex;
  padding: 12px 20px;
  justify-content: space-between;
  align-items: center;
  pointer-events: none;

}
a {
    text-decoration: none;
    color: black;

}


.dis {
  
  width: 30px;
  height: 30px;
  border-radius: 25px;
  background-color: red;
}

.chatt{
  width: 30px;
  height: 30px;
  border-radius: 25px;
  background-color: red;
}
.favs {
  padding: 30px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}

.fav {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 20px;
  width: 100px;
  height: 100px;
}

.fav:hover {
  background-color: rgba(108, 107, 107, 0.421);
  border-radius: 10px;
  transform: scale(1.09);
  width: 100px;
  height: 100px;
}

.fav .text {
  display: none;
}

.fav:hover .text {
  display: block;
  position: absolute;
  right: 13px;
  top: 0;
  animation: appear 0s linear 1s forwards;
}

@keyframes appear {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}

.text {
  display: inline-block;
  width: 3px;
  height: 3px;
  border-radius: 50%;
 
  margin-top: 2px;
  position: absolute;
  margin-top: 10px; 
}

.image {
  width: 30px; /* Ajustez la taille selon vos préférences */
  height: 30px;
  border-radius: 50%;
}


.link{
        position: absolute;
        top: 20px;
        right: 10px;
        font-size: 14px;
        align-items: center;
     
    justify-content: flex-end;
    gap: 20px;
   
    display: flex;

      
        
      
    }
    button{
    background-color: transparent;
    border: none;
}


.lien::after {
    content: "";
    display: block;
    position: absolute;
    width: 20%;
    height: 2px;
    background: #1e1e1e;
    transform: scale(0);
    transition: transform 0.2s ease-in-out;
}

.lien:hover::after {
    transform: scale(1);
}
.lien2::after {
    content: "";
    display: block;
    position: absolute;
    left: 50px;
    width: 23%;
    height: 2px;
    background: #131414;
    transform: scale(0);
    transition: transform 0.2s ease-in-out;
}

.lien2:hover::after {
    transform: scale(1);
}


.penss{
  position: absolute;
        top: 93%;
        right: 3px;
}


</style>

