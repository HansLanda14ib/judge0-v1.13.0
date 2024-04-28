<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h2 align="center">Judge0 CE</h2>

  <p align="center">
   open-source online code execution system.
    <br />
    <a href="https://ce.judge0.com/"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://ide.judge0.com/">View Demo</a>

  </p>
</div>


<!-- ABOUT THE PROJECT -->
## About The Project
Robust, scalable, and open-source online code execution system that can be used to build a wide range of applications that need online code execution features. Some examples include competitive programming platforms, e-learning platforms, candidate assessment and recruitment platforms, online code editors, online IDEs, and many more.


## Prerequisites

Judge0 has only been tested on Linux and might not work on other systems; thus, no support for it.

* Docker and Docker compose [Link](https://docs.docker.com/compose/install/)
 

## Installation

1. Download and extract the release archive:
   ```sh
    git clone https://github.com/HansLanda14ib/judge0-v1.13.1.git
    ```
2. Set the variable REDIS_PASSWORD POSTGRES_PASSWORD in the judge0.conf file.

3. cd judge0-v1.13.1 and run :
   ```sh
    docker-compose up -d db redis
    sleep 10s
    docker-compose up -d
    sleep 5s
    ```

Your instance of Judge0 CE v1.13.1 is now up and running; visit docs at http://<IP ADDRESS OF YOUR SERVER>:2358/docs.



<!-- USAGE EXAMPLES -->
## Supported languages

<details>
  <summary>Explore the list</summary>

| ID            | Language      |
| ------------- | ------------- |
| 62            | Java          |
| 70            | Python        |
| 62            | Java          |
| 70            | Python        |
| 62            | Java          |
| 70            | Python        |
| 62            | Java          |
| 70            | Python        |
| 62            | Java          |
| 70            | Python        |
| 62            | Java          |
| 70            | Python        |
| 62            | Java          |
| 70            | Python        |
| 62            | Java          |
| 70            | Python        |
| 62            | Java          |
| 70            | Python        |


</details>


## Disclaimer

This project is not originally created by me. It is a modified version of the Judge0 CE project, originally developed and owned by [Herman Zvonimir Došilović](https://github.com/hermanzdosilovic). My modifications primarily involve changes to the configuration settings. All original rights belong to the initial owner.

<a href="https://judge0.com/#clients"><strong>Judge0 project</strong></a>
<a href="https://scholar.google.com/scholar?q=10.23919%2FMIPRO48935.2020.9245310"><strong>Paper</strong></a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>


