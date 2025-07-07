# Projeto Spotify

Um clone do Spotify desenvolvido com React.js no front-end e Node.js no back-end. O projeto foi feito em meados de 2025, ao participar do evento gratuito da Hashtag Programação.

## Pré-requisitos

Antes de começar, você precisará ter instalado em sua máquina:

- [Node.js](https://nodejs.org/) (versão 14 ou superior)
- [npm](https://www.npmjs.com/) (geralmente vem com o Node.js)
- [Git](https://git-scm.com/) (para clonar o repositório)

## Como executar o projeto

### 1. Clone o repositório
```bash
git clone https://github.com/josecardozoif/projeto-spotify.git
cd projeto-spotify
```

### 2. Configurar o Back-end
```bash
# Navegar para a pasta do back-end
cd back-end

# Instalar as dependências
npm install

# Opcional
npm install -g nodemon

# Executar o servidor em modo de desenvolvimento
npm run dev

# Ou executar em modo de produção
npm start
```

O servidor back-end estará rodando na porta 3001.

### 3. Configurar o Front-end
**Abra um novo terminal** e execute:
```bash
# Navegar para a pasta do front-end (a partir da raiz do projeto)
cd front-end

# Instalar as dependências
npm install

# Executar a aplicação React
npm run dev
```

O front-end estará disponível em `http://localhost:5173`.

## Estrutura do Projeto

```
projeto-spotify/
├── back-end/
│   ├── api/
│   │   ├── connect.js      # Conexão com banco de dados
│   │   ├── insertMany.js   # Inserção de dados
│   │   └── server.js       # Servidor principal
│   ├── package.json
│   ├── package-lock.json
│   └── node_modules/
├── front-end/
│   ├── .vite/
│   │   └── deps/
│   │   │   └── _metadata.json
│   ├── api/
│   │   └── api.js
│   ├── src/
│   │   └── assets/
│   │   │   └── database/
│   │   │   │   └── artists.js
│   │   │   │   └── songs.js
│   │   │   └── logo/
│   │   │       └── spotify-logo.png
│   │   └── componentes/
│   │   │   └── Header.jsx
│   │   │   └── ItemList.jsx
│   │   │   └── Main.jsx
│   │   │   └── Player.jsx
│   │   │   └── SingleItem.jsx
│   │   │   └── SongItem.jsx
│   │   │   └── SongList.jsx
│   │   └── pages/
│   │   │   └── Artist.jsx
│   │   │   └── Artists.jsx
│   │   │   └── Home.jsx
│   │   │   └── Song.jsx
│   │   │   └── Songs.jsx
│   │   └── App.jsx
│   │   └── App2.jsx
│   │   └── main.jsx
│   │   └── index-aula.css
│   │   └── index.css
│   ├── .gitignore
│   ├── eslint.config.js
│   ├── index.html
│   ├── package.json
│   ├── package-lock.json
│   ├── node_modules/
│   └── vite.config.js
└── README.md
```

## Scripts Disponíveis

### Back-end
- `npm start` - Executa o servidor em modo de produção
- `npm run dev` - Executa o servidor em modo de desenvolvimento com nodemon
- `npm test` - Executa os testes (atualmente não configurado)

### Front-end
- `npm run dev` - Executa a aplicação React em modo de desenvolvimento
- `npm run build` - Cria uma versão otimizada para produção
- `npm run preview` - Visualiza a versão de produção localmente

## Tecnologias Utilizadas

### Front-end
- React.js
- Vite
- CSS3
- JavaScript (ES6+)

### Back-end
- Node.js
- Express.js
- JavaScript (ES6+)

## Como usar

1. **Inicialize o back-end primeiro** executando `npm run dev` na pasta `back-end`
2. **Em seguida, inicie o front-end** executando `npm run dev` na pasta `front-end`
3. **Acesse** `http://localhost:5173` no seu navegador

## Autor

- **José Cardozo** - [josecardozoif](https://github.com/josecardozoif)
