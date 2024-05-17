# Anima_CSS_1
Animação Feita por mim utilizando apenas CSS e HTML, representa o magnetismo.<br>
Feito pelo [|Codepen](https://codepen.io/sawwzozo-the-vuer/pen/RwmWxrw?editors=1100)
<br>
<div align="center">
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Nerd%20Face.png" alt="Nerd Face" width="100" height="100" /></div>
--------------------------------------------------------------------------------------------------------------------------------------------------------------
<div align="center"> GABRIEL CAMARA DE OLIVEIRA </div>
--------------------------------------------------------------------------------------------------------------------------------------------------------------
<div align="center">
<a href="https://www.instagram.com/gabriel_c137/">Siga-me no Instagram</a>    <br>and<br>  <a href="https://github.com/Gabriel-C137">Acompanhe o meu perfil para ver a evolução</a>
</div>
--------------------------------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------------------------------

##  🖇️ Colaboração:

* Professor Márcio - Fatec Franca
* W3Schools.com.br - Site de Ensino sobre Programação [w3School](https://www.w3schools.com/html/default.asp)
* Gustavo Guanabra - Curso em Vídeo [Acesse aqui](https://www.cursoemvideo.com/curso/curso-html5-e-css3-modulo-2-de-5-40-horas/)
* Canal dpw - Youtube.com.br [Acesse aqui](https://www.youtube.com/@dpwoficial)

<br>

### 📋 Pré-requisitos:

Esse também não é nessesário nenhuma pré-instalação para a execução/vizualização desse projeto, basta um navegador de internet (como Google Chrome, Mozilla 
Firefox e/ou Microsoft Edge)
<hr>
<br>


![3acabdec-1c9e-4078-8333-00b5f64cd8d1](https://github.com/Gabriel-C137/Anima_CSS_1/assets/91295561/b27ecb18-6073-4012-b168-0f1e35b2b4bb)


### Código HTML5 do meu projeto

```
<div class="planet"></div>
<div class="star"></div>
```

#### Código CSS3 do meu projeto

```
body {
 background-color: #090948;
 margin: 0;
 padding: 0;
  }
  
 .planet {
 width: 200px;
 height: 200px;
 border-radius: 50%;
 background: radial-gradient(circle, #2a6590 20%, #7fc8f8 100%);
 box-shadow: inset 10px 10px 20px rgba(0, 0, 0, 0.5);
 position: relative;
 overflow: hidden;
 box-shadow: 45px 10px 10px 10px #084d6e;
 animation: aniMoon 20s;
}
.planet:before {
 content: "";
 position: absolute;
 width: 80px;
 height: 80px;
 background: radial-gradient(circle, rgba(255, 255, 255, 0.7) 20%, transparent 60%);
 border-radius: 50%;
 top: 20px;
 left: 20px;
    }

.planet:after {
 content: "";
 position: absolute;
 width: 50px;
 height: 50px;
 background: radial-gradient(circle, rgba(255, 255, 255, 0.7) 20%, transparent 60%);
 border-radius: 50%;
 bottom: 40px;
 right: 40px;
    }

@keyframes aniMoon {
    from {
      box-shadow: 20px 15px 10px 10px #084d6e;}
    to{
      box-shadow: -20px 15px 10px 10px #084d6e;}
}


.star {
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: #000;
  }
  
  .star:before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 60px;
  height: 60px;
  border-radius: 50%;
  background: transparent;
  box-shadow: 530px 200px 2px 2px #fff;
  animation: animStar 35s;
  }
  
  @keyframes animStar {
    from {
      transform: rotate(0deg);
    }
    to {
      transform: rotate(270deg);
    }
  }

.orbit {
  width: 600px;
  height: 600px;
  border-radius: 50%;
  border: 3px;
  border-color: white;
}
.orbit-line {
  width: 590px;
  height: 590px;
  border-radius: 50%;
  display: flex;
  justify-content: center;
}
```
<br>
<hr>
<div align="center">...FIM...</div>
