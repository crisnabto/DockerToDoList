# Project Docker To Do List :bookmark: 

In this project, based on a full-stack task application, the following tasks were developed:

- Containerize applications
- Create a connection between them
- Orchestrate their operation

## :hammer_and_wrench: Tools

:green_circle: Javascript
<br>

:green_circle: Docker
<br>

:green_circle: Dockerfile
<br>

:green_circle: Docker compose


## :wrench:  Setup

Clone the repository:

```
git clone git@github.com:crisnabto/DockerToDoList.git
```

Install the dependencies:

```
npm install
```

## Tasks :heavy_check_mark:

<details>
  <summary>1. Create an interactive container named 01container, without running it, using the alpine image version 3.12</summary><br />
  
  - File `command01.dc`
  
 </details>
 
 <details>
  <summary>2. Start the 01container container</summary><br />
  
  - File `command02.dc`
  
 </details>
 
 <details>
  <summary>3. List the containers, filtering by the name 01container</summary><br />
  
  - File `command03.dc`
  
 </details>
 
  <details>
  <summary>4. Execute the command cat /etc/os-release in the 01container container without attaching to it</summary><br />
  
  - File `command04.dc`
  
 </details>
 
  </details>
 
  <details>
  <summary>5. Remove the 01container container</summary><br />
  
  - File `command05.dc`
  
 </details>
 
 <details>
  <summary>6. Download the nginx image with version 1.21.3-alpine without creating or running a container</summary><br />
  
  - File `command06.dc`
  
 </details>
 
  <details>
  <summary>7. Run a new container in the background named 02images with the nginx image version 1.21.3-alpine and map its default access port to port 3000 of the host system</summary><br />
  
  - File `command07.dc`
  
 </details>
 
  <details>
  <summary>8. Stop the running 02images container</summary><br />
  
  - File `command08.dc`
  
 </details>
 
  <details>
  <summary>9. Generate a build from the Dockerfile of the back-end of the todo-app, naming the image as todobackend</summary><br />
  
  - File `command09.dc`
  
  In the file `./docker/todo-app/back-end/Dockerfile`, write the commands that will make the image:

  - run from the `node` image in version 14;
  - expose port 3001;
  - add the `node_modules.tar.gz` file to the image;
  - copy all files from the `back-end` folder to the image (you can use the relative path, remembering that the `Dockerfile` is in `./docker/todo-app/back-       end/Dockerfile`);
  - start the application with the command `npm start`.
  
 </details>
 
   <details>
  <summary>10. Build the front-end of the todo-app using the Dockerfile and name the image as todofrontend</summary><br />
  
  - File `command10.dc`
  
  In the file `./docker/todo-app/front-end/Dockerfile`, write the commands that will make the image:

  - run from the `node` image in version 14;
  - expose port 3001;
  - add the `node_modules.tar.gz` file to the image;
  - copy all files from the `front-end` folder to the image (you can use the relative path, remembering that the `Dockerfile` is in `./docker/todo-app/front-end/Dockerfile`);
  - start the application with the command `npm start`.
  
 </details>
 
   <details>
  <summary>11. Build the back-end of the todo-app using the Dockerfile and name the image as todobackend</summary><br />
  
  - File `command11.dc`
  
  In the `./docker/todo-app/tests/Dockerfile` file, write the commands that will:

  - run the image from `mjgargani/puppeteer:trybe1.0`;
  - add the `node_modules.tar.gz` file to the image;
  - copy all files from the tests folder to the image (you can use the relative path, remembering that the Dockerfile is in ./docker/todo-                  app/tests/Dockerfile);
  - start the tests with the command `npm test`.
  
 </details>
 
---
 
### :envelope_with_arrow: Contact

[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:crisnabto@gmail.com)
[![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/crisna-bezerra/)

<!-- Olá, Tryber!
Esse é apenas um arquivo inicial para o README do seu projeto no qual você pode customizar e reutilizar todas as vezes que for executar o trybe-publisher.

Para deixá-lo com a sua cara, basta alterar o seguinte arquivo da sua máquina: ~/.student-repo-publisher/custom/_NEW_README.md

É essencial que você preencha esse documento por conta própria, ok?
Não deixe de usar nossas dicas de escrita de README de projetos, e deixe sua criatividade brilhar!
:warning: IMPORTANTE: você precisa deixar nítido:
- quais arquivos/pastas foram desenvolvidos por você; 
- quais arquivos/pastas foram desenvolvidos por outra pessoa estudante;
- quais arquivos/pastas foram desenvolvidos pela Trybe.
-->
