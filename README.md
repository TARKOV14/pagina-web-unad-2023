# pagina-web-unad-2023
CSS Grid. Daniel Alejandro Acuña Bulla 
<!DOCTYPE html>
<html>
<head>
  <title>CSS Grid - Mockup</title>
  <style>
    /* Estilos para el cuerpo de la página */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    
    /* Estilos para el encabezado */
    header {
      background-color: #333;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    
    /* Estilos para la barra de navegación */
    nav {
      background-color: #666;
      padding: 10px;
    }
    
    nav ul {
      list-style-type: none;
      margin: 0;
      padding: 0;
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 10px;
    }
    
    nav ul li {
      text-align: center;
    }
    
    /* Estilos para la sección principal */
    main {
      padding: 20px;
    }
    
    /* Estilos para el pie de página */
    footer {
      background-color: #333;
      color: #fff;
      padding: 10px;
      text-align: center;
    }
  </style>
</head>
<body>
  <header>
    <h1>CSS Grid</h1>
  </header>
  
  <nav>
    <ul>
      <li><a href="#inicio">Inicio</a></li>
      <li><a href="#tema">Tema seleccionado</a></li>
      <li><a href="#acerca">Acerca de</a></li>
    </ul>
  </nav>
  
  <main>
    <section id="inicio">
      <h2>Inicio</h2>
      <p>Bienvenido a la página sobre CSS Grid. Aquí encontrarás información y ejemplos relacionados con este poderoso sistema de diseño en CSS.</p>
    </section>
    
    <section id="tema">
      <h2>Tema seleccionado: CSS Grid</h2>
      <p>En esta sección puedes explorar el tema seleccionado sobre CSS Grid. A continuación, encontrarás un resumen sobre qué es CSS Grid y cómo se utiliza:</p>
      
      <h3>¿Qué es CSS Grid?</h3>
      <p>CSS Grid es un sistema de diseño en CSS que permite crear diseños de páginas web en una cuadrícula bidimensional. Con CSS Grid, puedes definir filas y columnas para posicionar y alinear elementos de manera precisa.</p>
      
      <h3>Características principales de CSS Grid:</h3>
      <ul>
        <li>Es una herramienta poderosa para el diseño de diseños complejos y responsivos.</li>
        <li>Permite controlar la ubicación y el orden de los elementos en una cuadrícula.</li>
        <li>Proporciona control total sobre el diseño en diferentes dispositivos y tamaños de pantalla.</li>
        <li>Facilita la creación de diseños flexibles y adaptables sin necesidad de recurrir a soluciones complicadas.</li>
      </ul>
      
      <h3>¿Cómo se utiliza CSS Grid?</h3>
      <p>Para utilizar CSS Grid, debes definir un contenedor como un elemento de cuadrícula y luego agregar elementos secundarios dentro de ese contenedor. Puedes establecer propiedades como <code>grid-template-rows</code> y <code>grid-template-columns</code> para definir la estructura de la cuadrícula.</p>
      
      <p>A continuación, puedes usar propiedades como <code>grid-row</code>, <code>grid-column</code>, <code>grid-area</code> para posicionar y ajustar el tamaño de los elementos secundarios dentro de la cuadrícula.</p>
      
      <p>Con CSS Grid, también puedes utilizar funciones como <code>repeat()</code> y <code>fr</code> (fracciones) para crear diseños flexibles y adaptativos.</p>
      
      <p>En resumen, CSS Grid es una herramienta poderosa para el diseño de páginas web, que ofrece un control preciso sobre la estructura y el diseño de una cuadrícula bidimensional.</p>
    </section>
    
    <section id="acerca">
      <h2>Acerca de</h2>
      <p>Esta página web fue creada como ejemplo para mostrar un mockup relacionado con el tema de CSS Grid.</p>
    </section>
  </main>
  
  <footer>
    <p>&copy; 2023 - UNAD 2023 DANIEL ACUÑA BULLA</p>
    <p>Última fecha de actualización: 2 de julio de 2023</p>
  </footer>
</body>
</html>
