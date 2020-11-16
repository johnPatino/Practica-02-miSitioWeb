# Practica-02-miSitioWeb

-Primer punto realizar la pagina home codigo csss que se utilizo fue

 font-family: "Mystery Quest", cursive; que srive para poder cambiar el estilo de la fuente 
 
 admas tambien le puse un efecto en la parte del cuerpo con estos colores 
 
 -moz-box-shadow: rgba(31, 61, 31, 0.9) 20px 0px 25px,
    rgba(31, 61, 31, 0.9) -20px 0px 25px;
  -webkit-box-shadow: rgba(31, 61, 31, 0.9) 20px 0px 25px,
    rgba(31, 61, 31, 0.9) -20px 0px 25px;
  box-shadow: rgba(31, 61, 31, 0.9) 20px 0px 25px,
    rgba(31, 61, 31, 0.9) -20px 0px 25px;
    
   -Para el de dos columnas utilice id y tabine utilice los div para poder dividr y utilice clases para que se me haga mas facil
   
   .columna1 {
  float: left;
  width: 30%;
}

.columna2 {
  float: left;
  width: 65%;
}

-para el de tres columnas hice lo mismo pero aunmete un div mas
.cabecera {
  float: left;
  width: 30%;
}

.contenido {
  text-align: justify;

  float: left;
  width: 46%;
}

.conten1 {
  padding: 1em;
  float: left;
  width: 20%;
}
-y por ultimo el formulario lo que hice fue hacer que sea interactivo con el comando form

 <form action="/my-handling-form-page" method="POST">
        <div>
            <label for="name">Nombre:</label>
            <input type="text" id="name" />
        </div>
        <div>
            <label for="mail">E-mail:</label>
            <input type="email" id="mail" />
        </div>
        <div>
            <label for="msg">Mensaje:</label>
            <textarea id="msg"></textarea>
        </div>

        <div class="button">
            <button type="submit">Enviar Mensaje</button>
        </div>
    </form>
    
 y luego con los css fue dandole el color y el ancho para que se vea mas 
 
 y por ultimo implemente un boton con una imagen que accede al formulario de contacto 
 
  <a href="formulario.html" ><button id=boton><img id=car src="../img/carta.png" alt="Zona Gaming" /></button><br> aquie creo y pongo la imgaen
