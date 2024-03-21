<a name="readme-top"></a>

<div align="center">
  
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

</div>

<br />

<div align="center">
    <h2 align="center">spanish_elections_results</h2>
  <a href="https://public.tableau.com/app/profile/juan.enrique/viz/ResultadosElectoralesalCongresodelosDiputadosEspaa23deJuliode2023/BUSCADORELECCIONES23J?publish=yes">
    <img src="images/qr_elecciones_generales_23J.png" alt="Logo" width="180" height="180">
  </a>

  <p align="center">
    Jupyter Notebook desarrollado para facilitar la representación en formato de archivo geoespacial (GeoJson & ShapeFile) de los resultados electorales al Congreso de los Diputados - España (julio 2023).
    <br />
    <br />
    <a href="https://github.com/juanenrique92/spanish_elections_results"><strong>Explorar el código »</strong></a>
    <br />
    <br />
    <a href="https://github.com/juanenrique92/spanish_elections_results">Tableau resultados con obtenidos</a>
    ·
    <a href="https://github.com/juanenrique92/spanish_elections_results/issues">Reportar Incidencia</a>
    ·
    <a href="https://github.com/juanenrique92/spanish_elections_results/issues">Solicitar desarrollo</a>
  </p>
</div>


<details>
  <summary>Índice</summary>
  <ol>
      <li><a href="#about-the-project">Descripción del proyecto</a>
      <li><a href="#built-with">Requerimientos</a></li>
      <li><a href="#built-with">Fuentes de información</a></li>
      <li><a href="#built-with">Uso</a></li>
      <li><a href="#built-with">Contribuciones</a></li>
      <li><a href="#built-with">Licencia</a></li>
      <li><a href="#built-with">Contacto</a></li>
  </ol>
</details>



### 1. Descripción del proyecto

[![Product Name Screen Shot][product-screenshot]](https://public.tableau.com/app/profile/juan.enrique/viz/ResultadosElectoralesalCongresodelosDiputadosEspaa23deJuliode2023/BUSCADORELECCIONES23J?publish=yes)

Con el objetivo de facilitar el acceso a los resultados electorales a nivel de sección censal y su representación cartográfica se ha desarrollado un script escrito en python mediante jupyter notebook que permite obtener la representación de estos resultados en los formatos GeoJson, ShapeFile (ESRI) y CSV.



### 2. Requerimientos

Enumeramos los requerimientos para ejecutar el jupyter notebook.

Entorno de ejecución:
- [Anaconda](https://www.anaconda.com/)
- [JupyterLAB](https://jupyter.org/)
- Python >= 3.10.13

Librerías Python:

- [Pandas](https://pandas.pydata.org/) >= 2.2.1 y sus dependencias
- [Geopandas](https://geopandas.org/) >= 0.14.2 y sus dependencias



### 3. Fuentes de información

Las fuentes de datos son dos, ambas oficiales:
- Resultados de las elecciones al congreso de los diputados a nivel de mesa electoral. Se descarga un fichero zip que contiene la documentación y 10 archivos .DAT de los cuales nos interesan 2 (03022307 y 10022307). [URL de la fuente](https://infoelectoral.interior.gob.es/es/elecciones-celebradas/area-de-descargas/)
- Fichero de geometrías (secciones censales). Se descarga un fichero llamado seccionado_2023.zip. [URL de la fuente](https://www.ine.es/ss/Satellite?L=es_ES&c=Page&cid=1259952026632&p=1259952026632&pagename=ProductosYServicios%2FPYSLayout)



### 4. Uso

Animamos a usar los datos generados como nuevas fuentes de información que pueden ser utilizadas en análisis espacial, identificación de patrones socio-políticos, planificación electoral, evaluación de la participación electoral, transparencia y cualquier otro campo que se considere de utilidad la información generada.

Un ejemplo de ello es el [dashboard que hemos desarrollado y publicado en Tableau Public](https://public.tableau.com/app/profile/juan.enrique/viz/ResultadosElectoralesalCongresodelosDiputadosEspaa23deJuliode2023/BUSCADORELECCIONES23J?publish=yes) que se muestra al principio del README y con el que se pretende demostrar la utilidad como herramienta de transparencia. 

Estaré agradecido si se cita este repositorio para que otras personas puedan hacer uso de él.  


### 5. Contribuciones
Las contribuciones son lo que hacen que la comunidad open source sea un lugar increíble para aprender, inspirar y crear. Cualquier contribución que realices es muy apreciada.

Si tienes una sugerencia que podría mejorar esto, por favor bifurca el repositorio y crea una solicitud de extracción. También puedes simplemente abrir un problema con la etiqueta "mejora".
¡No olvides darle una estrella al proyecto! ¡Gracias de nuevo!


### 6. Licencia

Distribuido bajo licencia GPL-3.0 . Ver `LICENSE.txt` para más información.


### 7. Contacto

Juan Enrique López Marcos - [LinkedIn][linkedin-url] - juanenrique.lopezmarcos@gmail.com

Link del proyecto: [https://github.com/juanenrique92/spanish_elections_results](https://github.com/juanenrique92/spanish_elections_results/)]

<p align="right">(<a href="#readme-top">ir al principio</a>)</p>



[contributors-shield]: https://img.shields.io/github/contributors/juanenrique92/spanish_elections_results.svg?style=flat
[contributors-url]: https://github.com/juanenrique92/spanish_elections_results/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/juanenrique92/spanish_elections_results.svg?style=flat
[forks-url]: https://github.com/juanenrique92/spanish_elections_results/network/members
[stars-shield]: https://img.shields.io/github/stars/juanenrique92/spanish_elections_results.svg?style=flat
[stars-url]: https://github.com/juanenrique92/spanish_elections_results/stargazers
[issues-shield]: https://img.shields.io/github/issues/juanenrique92/spanish_elections_results.svg?style=flat
[issues-url]: https://github.com/juanenrique92/spanish_elections_results/issues
[license-shield]: https://img.shields.io/github/license/juanenrique92/spanish_elections_results.svg?style=flat
[license-url]: https://github.com/juanenrique92/spanish_elections_results/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white
[linkedin-url]: https://www.linkedin.com/in/juanenriquelopezmarcos
[product-screenshot]: images/sc_tableau.png
[Python.js]: https://img.shields.io/badge/next.js-000000?style=flat&logo=nextdotjs&logoColor=white
[Python-url]: https://www.python.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
