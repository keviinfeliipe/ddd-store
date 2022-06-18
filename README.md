<h1>Análisis del problema: Cuarta Pauta (Implementación)</h1>
<h2>Dominio - Tienda</h2>
<p>Se crea un pet project basado en el servicio de envíos de una tienda, se implementó la parte estratégica y táctica con base a las pautas.</p>
<h2>Integrantes</h2>
<ul>
  <li>Sebastián Huertas Cardona</li>
  <li>Kevin Felipe Vargas Bermudez</li>
</ul>
<hr>
<h2>Diagramas</h2>
<p>Para el diseño de los diagramas se hace uso de la aplicación <a href="https://www.diagrams.net">diagrams.net</a>, se realizó el diagrama de análisis, modelo de dominio y eventos del dominio, tomando como base el ejemplo de las pautas presentadas en la plataforma Sofka-U.</p>
            
<p>Link de los diagramas: <a href="https://app.diagrams.net/#G1jRlUH5L5G-6SgRsECem8IapsRVNvsgDf">Diagramas ddd-store.</a></p>
    
<h2>Analisis del problema - BigPicture</h2>


<img src="https://i.postimg.cc/zXPjkjnp/Analisis-del-problema-Big-Picture-domain.png" width="500" title="hover text"/>
<img src="https://i.postimg.cc/x1w3w1pz/Analisis-del-problema-Big-Picture-subdomain-cliente.png" width="500" title="hover text"/>
<img src="https://i.postimg.cc/YCGxDWR7/Analisis-del-problema-Big-Picture-subdomain-orden.png" width="500" title="hover text"/>
<img src="https://i.postimg.cc/vm5tbwCS/Analisis-del-problema-Big-Picture-subdomain-producto.png" width="500" title="hover text"/>

<h3>Modelo de Dominio</h3>


<img src="https://i.postimg.cc/gj2VVXjf/Modelo-de-dominio-Cliente.png" width="500" title="hover text"/>
<img src="https://i.postimg.cc/J0YbPrBt/Modelo-de-dominio-Envio.png" width="500" title="hover text"/>
<img src="https://i.postimg.cc/m2h3hH09/Modelo-de-dominio-Producto.png" width="500" title="hover text"/>

<h3>Diagrama de Dominio</h3>

<img src="https://i.postimg.cc/k49F5hmM/Eventos-de-dominio-Persona.png" width="500" title="hover text"/>
<img src="https://i.postimg.cc/zBjwHSzC/Eventos-de-dominio-Envio.png" width="500" title="hover text"/>
<img src="https://i.postimg.cc/c1FMsm5Z/Eventos-de-dominio-Producto.png" width="500" title="hover text"/>
<hr>
<h2>Implementación</h2>
<p>Para la implantación del modelo de dominó se trabajó de la siguiente manera:</p>
<ul>
  <li>Sub-dominio envio:</li>
  <p>Este sub-dominio se trabajó con la metodología de pair programming en donde Kevin Vargas conducía y Sebastián Huertas dirigía, se crea el agregado root, las entidades, objetos de valor, eventos de dominio y comando según lo indica el modelo.</p>
  <li>Sub dominio persona:</li>
  <p>Este sub-dominio fue implementado por Kevin Vargas.</p>
  <li>Sub dominio producto:</li>
  <p>Este sub-dominio fue implementado por Sebastián Huertas.</p>
</ul>
<hr>
