# animação de backgrund

esse exemplo consiste em um fundo gradiente e vai mudando de cor conforme o tempo
___
![exemplo]()
____
## codigo 
### html
```` html
  <body>    
    <h1><a href="https://github.com/igorrzinho/igorrzinho">igorzinho</a></h1>
  </body>
````
### css
```` css
 body{
        background-repeat:no-repeat;
        background-image: linear-gradient(45deg,#14283e,#C4C4C4);
        text-align: center;
        line-height: 100vh;
        background-size: 200% 200%;
        animation: backgroudAnimation 5s ease infinite;
        height:100vh;
      }
      
@keyframes backgroudAnimation{
        0%{
          background-position: 0% 50%;
        }
        50%{
          background-position: 100% 50% ;
        }
        100%{
          background-position: 0% 50%;
        }
      }
````
