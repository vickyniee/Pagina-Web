# Pagina-Web
![logo de nuestra Web](https://github.com/user-attachments/assets/c9d7e1c0-4368-4956-94df-5d600fda4139)

<em> Hot Wheels Store </em>

#Introduccion 

Pagina Web realizada por Alejandro vargas, Yuliana Abreu y Victoria Rangel 

-- --
[DESCRIPCION DEL PROYECTO](#descripción-del-proyecto)

## :hammer:Funcionalidades del proyecto

- `Funcionalidad 1`:Tienda online que permite a los usarios comprar en linea
-   `Funcionalidad 2`: Tienda para Niños
-   `Funcionalidad 3`:  Basado en Hot Wheels, funciona mendiante una tienda online que cuenta con menu, precios, descuentos etc

-   -- -- -- --

-   \## 📁 Acceso al proyecto

** Abre el Visual studio code, luego crea un folder, al tener esto abre la terminal del visual, luego en la terminal colocas git clone https://github.com/vickyniee/Pagina-Web.git esto hara que se clone y lo tengas directamente desde tu consola**

\## 🛠️ Abre y ejecuta el proyecto

**Un tip: descarga la extension de visual studio code llamda Live server, y asi puedes ver los cambios que le haces en tiempo real, vas a tu html presionas click derecho y le das open with live server, se ta va a un servidor y se ejecuta la web, o simplemente le das al index.html abrir con; google. Asi se puede ejecutar**

-- ---
## Support

Para dudas o acontecimientos; rangelperezva@uvm.edu.ve

## Uso y ejemplos/Explicacion del codigo

 *javascript*
```javascript
let slideIndex = 1;
showSlides(slideIndex);

// Next/previous controls
function plusSlides(n) {
  showSlides(slideIndex += n);
}

// Thumbnail image controls
function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";
  }
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";
  dots[slideIndex-1].className += " active";
}
```
**Codigo utilizado para crear un carrusel de imagenes**

-- --- --- --- ---
 *html*
```html

    <div class="header">
        <div class="logo">
         <img src="img/logo.png" alt="">
        </div>
         <div class="header-right">
           <a class="active" href="#home">Home</a>
           <a href="#contact">Contact</a>
           <a href="#about">About</a>
         </div>
       </div>

       <section class="main content">
        <div class="slideshow-container">
          <div class="mySlides fade">
            <div class="numbertext">1 / 3</div>
            <img src="img/carrito 1.jpg" style="width:500px">
            <div class="text">ORIGINAL</div>
          </div>
        
          <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
          <a class="next" onclick="plusSlides(1)">&#10095;</a>
        </div>
        <br>
        <div style="text-align:center">
          <span class="dot" onclick="currentSlide(1)"></span>
          <span class="dot" onclick="currentSlide(2)"></span>
          <span class="dot" onclick="currentSlide(3)"></span>
        </div>
        <section class="container global-products">
          <h1 class="heading-1"> Productos a nivel global</h1>
          <div class="container-options">
              <span class="active">Destacados</span>
              <span>Recientes</span>
              <span>Proximos</span>
          </div>
          <div class="container-products">
              <div class="card-product">
                  <div class="container-img">
                      <img src="img/carrito 4.jpg" alt="HotWheels">
                      <span class="discount">-45%</span>
                      <div class="button-group">
                      </div>
                  </div>
                  <div class="content-card-product">
                      <h3>Carrito Hot Wheels</h3>
                      <span class="add-cart"> </span>
                      <div class="price">742.5$ <span> 1650$</span></div>
    </section>
    <section class="footer">
      <footer>
        <p>HOT WHEELS STORE BY AYV </p>
        <p><a href="hotWheels.com">hotWheels.com</a></p> 
        </footer> 
       </section>
 
```
**Etiquetas html, cremos secciones para separar las partes entre si, dentro de esta creamos las clases dentro de los divs, agregamos lo que era referente en cada seccion para cada uno, img, los dots, etc**
 -- --- --- --- --



 *css*
```css
* responsive, cuando la pantalla tenga 500 píxeles de ancho o menos, esto lo que hara es q se apilen los enlaces uno encima del otro para que quepan*/
  @media screen and (max-width: 500px) {
    .header a {
      float: none;
      display: block;
      text-align: left;
    }
    .header-right {
      float: none;
    }
  }
```

**con las demas etiquetas lo que hicimos fue darle estilos a cada uno de ellos; letras, titulos, logo, menu, etc**


## Autores

- [@vickyniee , @yulianabreuc  , @Alegabriel232310](https://github.com/vickyniee , https://github.com/yulianabreuc , https://github.com/Alegabriel232310 )


## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/vickyniee/Pagina-Web)

**YOUTUBE** (https://www.youtube.com/channel/UCuBMlgJvj38qlmplkCD2dmA) 







    

