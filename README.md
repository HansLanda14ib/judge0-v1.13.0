<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    ![image](https://github.com/HansLanda14ib/judge0-v1.13.1/assets/100965812/5809e207-653c-4716-bd22-f9bb31b54f53)
  </a>

  <h2 align="center">Judge0 CE</h2>

  <p align="center">
    Votre Environnement d'Exécution de Code en Ligne!
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    ·

  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
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



<!-- ABOUT THE PROJECT -->
## About The Project

Un environnement d'exécution de code en ligne sécurisé et polyvalent.

Fonctionnalités Puissantes de Judge0 : 
* Prise en charge étendue des langages de programmation : C, C++, Python, Java, et plus encore.
* Environnement sécurisé : exécution isolée du code pour garantir la sécurité des utilisateurs et des systèmes.
* API conviviale : permet une intégration facile de Judge0 dans diverses applications et plateformes.
* Utilisation via RapidAPI (payant) ou en déploiement en auto-hébergement (Gratuit) pour plus de contrôle et de personnalisation.
Of course, no one template will serve all projects since your needs may be different. So I'll be adding more in the near future. You may also suggest changes by forking this repo and creating a pull request or opening an issue. Thanks to all the people have contributed to expanding this template!


<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Getting Started


### Prerequisites

Judge0 has only been tested on Linux and might not work on other systems; thus, no support for it.

* Docker and Docker compose [Link](https://docs.docker.com/compose/install/)
 

### Installation


1. Download and extract the release archive:
   ```sh
    git clone https://github.com/HansLanda14ib/judge0-v1.13.1.git
    ```
2. Update the variable REDIS_PASSWORD POSTGRES_PASSWORD in the judge0.conf file.

4. run docker command :
   ```sh
    docker-compose up -d db redis
    sleep 10s
    docker-compose up -d
    sleep 5s
    ```

Your instance of Judge0 CE v1.13.1 is now up and running; visit docs at http://<IP ADDRESS OF YOUR SERVER>:2358/docs.


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Badreddine Ibzazne - [@hanslanda14ib](https://twitter.com/hanslanda14ib) - bibzazne@gmail.com

Project Link: [https://github.com/HansLanda14ib/judge0-v1.13.1](https://github.com/HansLanda14ib/judge0-v1.13.1)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Judge0 project](https://judge0.com/#clients)


<p align="right">(<a href="#readme-top">back to top</a>)</p>


