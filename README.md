# devjob

## tools
HTML, CSS, Javascript, Typescript
SASS, Botstrap, React, MongoDB, Node.js

## description (remove after)
Um site semelhante ao linkdin, com a diferença que possuira 1 teste vocacional, e com foco em informática, o teste servira para saber qual área de tecnologia melhor se encaixa com o usuário

## structure (remove after)
meu-projeto/
│
├── client/                  # Frontend (React + TS + SASS)
│   ├── public/              # Arquivos públicos (index.html, favicon, etc.)
│   ├── src/
│   │   ├── assets/          # Imagens, ícones
│   │   ├── components/      # Componentes reutilizáveis React
│   │   ├── pages/           # Páginas principais
│   │   ├── styles/          # SCSS global e variáveis
│   │   ├── App.tsx          # Raiz da aplicação React
│   │   ├── index.tsx        # Ponto de entrada React
│   │   └── react-app-env.d.ts
│   ├── package.json
│   └── tsconfig.json
│
├── server/                  # Backend (Node.js + TS + MongoDB)
│   ├── src/
│   │   ├── config/          # Conexão com banco, variáveis
│   │   ├── controllers/     # Lógica das rotas
│   │   ├── models/          # Schemas do MongoDB
│   │   ├── routes/          # Rotas da API
│   │   ├── index.ts         # Ponto de entrada do servidor
│   └── package.json
│
├── .gitignore
├── README.md
└── package.json             # Pode existir no root se usar monorepo
