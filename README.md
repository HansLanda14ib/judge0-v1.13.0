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

<strong>ID,Language</strong>

43,Plain Text

44,Executable

45,Assembly (NASM 2.14.02)

46,Bash (5.0.0)

47,Basic (FBC 1.07.1)

48,C (GCC 7.4.0)

49,C (GCC 8.3.0)

50,C (GCC 9.2.0)

51,C# (Mono 6.6.0.161)

52,C++ (GCC 7.4.0)

53,C++ (GCC 8.3.0)

54,C++ (GCC 9.2.0)

55,Common Lisp (SBCL 2.0.0)

56,D (DMD 2.089.1)

57,Elixir (1.9.4)

58,Erlang (OTP 22.2)

59,Fortran (GFortran 9.2.0)

60,Go (1.13.5)

61,Haskell (GHC 8.8.1)

62,Java (OpenJDK 13.0.1)

63,JavaScript (Node.js 12.14.0)

64,Lua (5.3.5)

65,OCaml (4.09.0)

66,Octave (5.1.0)

67,Pascal (FPC 3.0.4)

68,PHP (7.4.1)

69,Prolog (GNU Prolog 1.4.5)

70,Python (2.7.17)

71,Python (3.8.1)

72,Ruby (2.7.0)

73,Rust (1.40.0)

74,TypeScript (3.7.4)

75,C (Clang 7.0.1)

76,C++ (Clang 7.0.1)

77,COBOL (GnuCOBOL 2.2)

78,Kotlin (1.3.70)

79,Objective-C (Clang 7.0.1)

80,R (4.0.0)

81,Scala (2.13.2)

82,SQL (SQLite 3.27.2)

83,Swift (5.2.3)

84,Visual Basic.Net (vbnc 0.0.0.5943)

85,Perl (5.28.1)

86,Clojure (1.10.1)

87,F# (.NET Core SDK 3.1.202)

88,Groovy (3.0.3)

89,Multi-file program


</details>


## Disclaimer

This project is not originally created by me. It is a modified version of the Judge0 CE project, originally developed and owned by [Herman Zvonimir Došilović](https://github.com/hermanzdosilovic). My modifications primarily involve changes to the configuration settings. All original rights belong to the initial owner.

<a href="https://judge0.com/#clients"><strong>Judge0 project</strong></a>
<a href="https://scholar.google.com/scholar?q=10.23919%2FMIPRO48935.2020.9245310"><strong>Paper</strong></a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>


