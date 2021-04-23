# Fundamentos-Node.js

## Requisitos

Para desenvolvimento, você precisará apenas do Node.js e o gerenciador de pacotes global, Yarn, instalado em seu ambiente.

### Node

- #### Instalando Node no Windows

  Acesse o [site oficial do Node.js](https://nodejs.org/) e baixe o instalador.
  Além disso, certifique-se de ter o `git` disponível em seu PATH, o `npm` pode precisar dele (Você pode obtê-lo [aqui](https://git-scm.com/)).

- #### Instalando Node no Ubuntu

  Você pode instalar o _nodejs_ e o _npm_ facilmente com `apt install`, apenas execute os comandos a seguir.

      $ sudo apt install nodejs
      $ sudo apt install npm

- #### Outros Sitemas Operacionais
  Você pode obter mais informações sobre a instalação no [site oficial do Node.js](https://nodejs.org/) e no [site oficial do NPM](https://npmjs.org/).

Se a instalação foi bem-sucedida, você deve ser capaz de executar o seguinte comando.

    $ node --version
    v14.15.4

    $ npm --version
    6.14.10

Se você precisar atualizar o `npm`, pode fazê-lo usando o próprio `npm`. Basta executar o seguinte comando.

    $ npm install npm -g

### Instalando Yarn

Depois de instalar o node, este projeto também precisará do yarn, então apenas execute o seguinte comando.

      $ npm install -g yarn

##Conceitos estudados

### Métodos HTTP

- **GET** - Buscar uma informação dentro do servidor.
- **POST** - Inserir uma informação no servidor.
- **PUT** - Alterar uma informação no servidor.
- **PATCH** - Alterar uma informação específica.
- **DELETE** - Delatar uma informação no servidor.

### Tipos de parâmetros

- **Route Params** - Identificar um recurso buscar/editar/deletar.
- **Query Params** - Paginação/Filtro.
- **Body Params** - Objetos {JSON} para inserção/alteração.

## Conclusão

O intuito do simples projeto é apenas abordar os conceitos de forma introdutória para que tornar a compreensão mais fácil. Projetos futuros abordarão mais conceitos relacionados ao desenvolvimento back-end utilizando Node.js.
