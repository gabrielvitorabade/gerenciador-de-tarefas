# ✅ Gerenciador de Tarefas — React 

Uma aplicação simples e funcional de lista de tarefas desenvolvida com React, ideal para praticar conceitos fundamentais como gerenciamento de estado, manipulação de eventos e renderização de listas. Com uma interface minimalista e responsiva, este projeto é perfeito para quem está começando no ecossistema React.

## 🚀 Tecnologias Utilizadas

- React (Create React App) — Biblioteca principal para construção da interface
- JavaScript (ES6+) — Lógica da aplicação e manipulação de dados
- CSS Puro — Estilização leve e responsiva
- npm / yarn — Gerenciadores de pacotes
  
## ✨ Funcionalidades

-  🔍 Pesquisar tarefas por nome/ palavra chave 
-  ➕ Adicionar novas tarefas
- ✅ Marcar e desmarcar tarefas como concluídas
- 🗑️ Excluir tarefas individualmente
- 🧹 Limpar todas as tarefas concluídas
- 📱 Interface responsiva e minimalista
  
## 📁 Estrutura do Projeto
gerenciador-de-tarefas/

├── public/

│   └── index.html

├── src/

│   ├── components/

│   ├── App.jsx

│   ├── index.js

│   └── styles.css

├── package.json

└── README.md


## 🧠 Desafios Enfrentados

1. Gerenciamento de Estado
- Utilização do useState para controlar a lista de tarefas e seus estados (pendente/concluída).
- Atualização eficiente da UI com base nas interações do usuário.
2. Manipulação de Eventos
- Captura de eventos de clique e teclado para adicionar, concluir ou excluir tarefas.
- Prevenção de ações inválidas (como adicionar tarefas vazias).
3. Renderização Condicional
- Exibição dinâmica de tarefas com base no status.
- Ocultação de botões e mensagens conforme o contexto da lista.
4. Pesquisa com listagem automatica
- Renderização automatica de resultados
- Design de busca intuítivo 

## 🧪 Próximos Passos

- 🔍 Filtro por status (Todas, Pendentes, Concluídas)
- 💾 Persistência de tarefas no LocalStorage
- 🧪 Testes unitários com Jest e React Testing Library
- 🚀 Deploy em Netlify, Vercel ou GitHub Pages
📦 Como Executar Localmente

# Clone o repositório
git clone https://github.com/gabrielvitorabade/gerenciador-de-tarefas

# Acesse o diretório
cd gerenciador-de-tarefas

# Instale as dependências
npm install

# Inicie o servidor de desenvolvimento
npm start


Acesse em: http://localhost:3000
🤝 Contribuição
- Faça um fork do repositório
- Crie uma branch: git checkout -b feature/nova-feature
- Commit suas alterações: git commit -m 'Adiciona nova feature'
- Push para a branch: git push origin feature/nova-feature
- Abra um Pull Request


