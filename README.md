<a name="readme-top"></a>

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]


<br />
<div align="center">
  <a href="https://github.com/juanenrique92/spanish_elections_results">
    <img src="images/qr_elecciones_generales_23J.png" alt="Logo" width="120" height="120">
  </a>
  <h3 align="center">spanish_elections_results</h3>
  <p align="center">
    Jupyter Notebook creado explotar la información electoral de las elecciones generales al Congreso de los Diputados
    <br />
    <a href="https://github.com/juanenrique92/spanish_elections_results"><strong>Explora el código »</strong></a>
    <br />
    <br />
    <a href="https://github.com/juanenrique92/spanish_elections_results">Tableau resultados con obtenidos</a>
    ·
    <a href="https://github.com/juanenrique92/spanish_elections_results/issues">Reportar Incidencia</a>
    ·
    <a href="https://github.com/juanenrique92/spanish_elections_results/issues">Solicitar desarrollo</a>
  </p>
</div>



<!-- Tabla de contenido -->
<details>
  <summary>Índice</summary>
  <ol>
    <li>
      <a href="#about-the-project">Descripción del proyecto</a>
      <ul>
        <li><a href="#built-with">Requerimientos</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- Descripción del proyecto -->
## Descripción del proyecto


[![Product Name Screen Shot][product-screenshot]](https://public.tableau.com/app/profile/juan.enrique/viz/ResultadosElectoralesalCongresodelosDiputadosEspaa23deJuliode2023/BUSCADORELECCIONES23J?publish=yes)

Con el objetivo de facilitar el acceso a los resultados electorales a nivel de sección censal y su representación cartográfica se ha desarrollado un script escrito en python mediante jupyter notebook que permite obtener la representación de estos resultados en los formatos GeoJson, ShapeFile (ESRI) y CSV.

Las fuentes de datos son dos, ambas oficiales:
- Resultados de las elecciones al congreso de los diputados a nivel de mesa electoral. Se descarga un fichero zip que contiene la documentación y 10 archivos .DAT de los cuales nos interesan 2 (03022307 y 10022307). [URL de la fuente](https://infoelectoral.interior.gob.es/es/elecciones-celebradas/area-de-descargas/)
- Fichero de geometrías (secciones censales). Se descarga un fichero llamado seccionado_2023.zip. [URL de la fuente](https://www.ine.es/ss/Satellite?L=es_ES&c=Page&cid=1259952026632&p=1259952026632&pagename=ProductosYServicios%2FPYSLayout)


<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Requerimientos

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

* [![Next][Next.js]][Next-url]
* [![React][React.js]][React-url]
* [![Vue][Vue.js]][Vue-url]
* [![Angular][Angular.io]][Angular-url]
* [![Svelte][Svelte.dev]][Svelte-url]
* [![Laravel][Laravel.com]][Laravel-url]
* [![Bootstrap][Bootstrap.com]][Bootstrap-url]
* [![JQuery][JQuery.com]][JQuery-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [x] Add Changelog
- [x] Add back to top links
- [ ] Add Additional Templates w/ Examples
- [ ] Add "components" document to easily copy & paste sections of the readme
- [ ] Multi-language Support
    - [ ] Chinese
    - [ ] Spanish

See the [open issues](https://github.com/othneildrew/spanish_elections_results/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@your_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/juanenrique92/spanish_elections_results.svg?style=for-the-badge
[contributors-url]: https://github.com/juanenrique92/spanish_elections_results/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/juanenrique92/spanish_elections_results.svg?style=for-the-badge
[forks-url]: https://github.com/juanenrique92/spanish_elections_results/network/members
[stars-shield]: https://img.shields.io/github/stars/juanenrique92/spanish_elections_results.svg?style=for-the-badge
[stars-url]: https://github.com/juanenrique92/spanish_elections_results/stargazers
[issues-shield]: https://img.shields.io/github/issues/juanenrique92/spanish_elections_results.svg?style=for-the-badge
[issues-url]: https://github.com/juanenrique92/spanish_elections_results/issues
[license-shield]: https://img.shields.io/github/license/juanenrique92/spanish_elections_results.svg?style=for-the-badge
[license-url]: https://github.com/juanenrique92/spanish_elections_results/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/juanenriquelopezmarcos
[product-screenshot]: images/sc_tableau.png
[Python.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Python-url]: https://www.python.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
