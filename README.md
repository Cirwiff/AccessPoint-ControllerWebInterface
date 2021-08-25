# AccessPoint-ControllerWebInterface
Este repositório contém os arquivos relacionados a interface web do servidor controlador de pontos de acesso (roteadores wireless)
 
<h2 align="center">Procedimentos para instalação</h2>

<h3 align="left">1 - Backend</h3>

Primeiramente, é necessário que o servidor controlador (backend), já esteja instalado, configurado e em execução. Link para procedimentos: https://github.com/davi109/AccessPoint-Controller

<h3 align="left">2 - Node.js</h3>

Para que seja possível a instalação da interface web, é necessário que o servidor que estará rodando o serviço tenha o node.js instalado:
Link para instalação caso ainda não tenha: https://nodejs.org/en/download/package-manager/

<h3 align="left">3 - Instalação e configuração da interface web</h3>

Acesso o terminal/cmd da máquina e execute os seguintes comandos:

```bash
# Clone este repositório
git clone https://github.com/davi109/AccessPoint-ControllerWebInterface.git

# Acesse a pasta do projeto no terminal/cmd
$ cd AccessPoint-ControllerWebInterface

# Instale as dependências
$ npm install

# Execute a aplicação em modo de desenvolvimento
$ npm start

# O servidor inciará na porta:3000 - acesse <http://localhost:3333>
```

### 🛠 Tecnologias utilizadas

As seguintes ferramentas foram usadas na construção do projeto:

- [React.js](https://pt-br.reactjs.org/)
- [Node.js](https://nodejs.org/en/)

### Links importantes

- [Servidor Contralador](https://github.com/davi109/AccessPoint-Controller)
- [Scripts para os pontos de acesso](https://github.com/davi109/AccessPoint-Scripts)



