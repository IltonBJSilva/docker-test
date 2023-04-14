# Projeto básico de Docker

Este é um projeto simples para você começar a se familiarizar com o Docker e suas funcionalidades básicas.

## Pré-requisitos

Antes de começar, certifique-se de ter instalado o Docker em sua máquina. Você pode baixá-lo [aqui](https://www.docker.com/products/docker-desktop).

## Como usar

1.  Clone o repositório em sua máquina local:
        
    `git clone https://github.com/IltonBJSilva/docker-test.git` 
    
2.  Navegue até o diretório do projeto:
        
    `cd nome-do-repositorio` 
    
3.  Crie uma imagem do Docker a partir do arquivo Dockerfile:
    
    
    `docker build -t nome-da-imagem .` 
    
4.  Execute o container:
      
    `docker run -p 3000:3000 nome-da-imagem` 
    
5.  Abra seu navegador e acesse `http://localhost:3000` para ver o projeto em execução.
    

## Licença

Este projeto é licenciado sob a [MIT License](https://chat.openai.com/LICENSE).