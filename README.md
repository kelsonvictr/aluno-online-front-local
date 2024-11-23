# Aluno Online Front - Local Build

Este repositório contém o front-end do sistema **Aluno Online**, já buildado e pronto para execução local. Este projeto foi desenvolvido em **ReactJS** e utiliza **Bootstrap**.

## Pré-requisitos

- **Node.js**: Certifique-se de ter o Node.js instalado em sua máquina. Você pode baixar e instalar a partir do site oficial: [Node.js](https://nodejs.org/).

## Passos para Instalação e Execução

Siga os passos abaixo para configurar e executar o front-end localmente:

1. **Clone o Repositório**  
   No terminal, execute o seguinte comando para clonar o repositório:
   ```bash
   git clone https://github.com/kelsonvictr/aluno-online-front-local.git
   ```

2. **Instale o Servidor Local**  
   Instale o pacote `serve` globalmente para hospedar o front-end:
   ```bash
   npm install -g serve
   ```

3. **Acesse o Diretório do Projeto**  
   Navegue até a pasta onde o repositório foi clonado:
   ```bash
   cd aluno-online-front-local
   ```

4. **Execute o Servidor**  
   Execute o comando abaixo para iniciar o servidor local:
   ```bash
   serve -s .
   ```

5. **Acesse o Sistema**  
   Abra o navegador e acesse o sistema no endereço:
   ```
   http://localhost:3000
   ```

## Observação

Certifique-se de que o backend do sistema está rodando localmente na máquina do aluno, acessível em `http://localhost:8080`. Este front-end depende do backend para funcionar corretamente.

## Tecnologias Utilizadas

- **ReactJS**
- **Bootstrap**
- **Vite**
