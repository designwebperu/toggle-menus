<html>
    <head></head>
    <body>
        <div>
            <h1><a href="/" style="color:red;">MENUS TOGGLE DESIGN WEB PERÚ</a></h1>             
        </div>
          
          
                 <h3><strong>Estructura general</strong></h3>
        
        
                <header class="main-header" id="main-header">
            <div class="menu-small">
              <div class="box-logo">
                <img src="https://www.designwebperu.com/img/logo/logo.png" alt="Logo empresa" class="logo">
              </div>
              <div class="box-anburguer" id="togle-menu"></div>
            </div>
            <nav class="main-nav" id="main-nav">
              <div class="box-logo hidden-logo">
                <img src="https://www.designwebperu.com/img/logo/logo.png" alt="Logo empresa" class="logo">
              </div>
              <div class="box-navigation">
                <ul class="menu">
                  <li class="menu-item"><a href="#" class="menu-link">Home</a></li>
                  <li class="menu-item active-view"><span class="menu-link active">Services</span>
                    <ul class="drowpmenu">
                      <li class="menu-item"><a href="#" class="menu-sub-link">Service 1</a></li>
                      <li class="menu-item"><a href="#" class="menu-sub-link">Service 2</a></li>
                      <li class="menu-item"><a href="#" class="menu-sub-link">Service 3</a></li>
                      <li class="menu-item"><a href="#" class="menu-sub-link">Service 4</a></li>
                    </ul>
                  </li>
                  <li class="menu-item"><a href="#" class="menu-link">Abouts</a></li>
                  <li class="menu-item"><a href="#" class="menu-link">Blog</a></li>
                  <li class="menu-item"><a href="#" class="menu-link">Contact</a></li>
                </ul>
              </div>
              </nav>
             </header>  
 
 
 <p><strong> Dentro de la etiqueta <a href="/">HEAD</a> añade la siguiente ruta:</strong></p>	    
 	
	<link rel="stylesheet" href="https://designwebperu.com/dwp-assets-v01/assets-css/dwp-menu-togle-v01.min.css">
<p  style="font-size:10px;">al añadir la ruta se estarán aplicando los estilos de los diferentes menus</p>

 <p><strong>al final de la etiqueta <a href="/">BODY</a> añadir el <a href="/">SCRIPT</a>:</strong></p>
 
 	<script src="https://designwebperu.com/dwp-assets-v01/assets-js/dwp-menu-v01.min.js"></script>
<p>la función del script es fundamental ya que es quien le da funcionalidad y animaciones al <a href="/">MENU</a></p>
<h5><a href="/">EJEMPLOS DE APLICAR ANIMACIONES AL MENÚ</a></h5>  
<p>Lo primero que debemos saber es que existen <strong>4</strong> tipos de animaciones <strong>toggle-l,   toggle-vh,    toggle-b y main-nav</strong></p>
<p>Si queremos añadir una animación lo único que hayque hacer es, añadir una de las clases despues de la clase <strong>main-nav</strong> recuerda que la animacion <strong>main-nav</strong> biene por defecto y no se deberia de quitar por ningun motivo</p>
<h6>Ejemplo1</h6>

	 <nav class="main-nav">
	 /* el main nav ya trae una animacion por fecto
	 </nav>
   
<h6>Ejemplo2</h6>

	<nav class="main-nav toggle-l">
	/* animación desde la parte izquierda del dispositivo
	</nav>
<h6>Ejemplo3</h6>

	<nav class="main-nav toggle-b">
	/* animación desde la parte inferior del dispositivo
	</nav>
<h6>Ejemplo4</h6>

	<nav class="main-nav toggle-vh">
	/* animación desde la parte superior del dispositivo
	</nav>
	
