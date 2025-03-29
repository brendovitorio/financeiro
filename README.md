# Gestão Financeira

Este é um projeto de um site de gestão financeira desenvolvido com **Next.js** e **MongoDB**, permitindo aos usuários cadastrar, visualizar e gerenciar despesas.

## Tecnologias Utilizadas

- **Frontend:** Next.js, React, TailwindCSS
- **Backend:** Express.js, MongoDB
- **Bibliotecas:** Axios, Mongoose, ShadCN/UI

## Funcionalidades

- Adicionar despesas com nome, valor, data e data de expiração
- Listar todas as despesas cadastradas
- Editar e excluir despesas
- Validação de entrada e expiração futura das despesas

## Como Rodar o Projeto

### 1. Clone o repositório
```bash
git clone https://github.com/seu-usuario/gestao-financeira.git
cd gestao-financeira
```

### 2. Instale as dependências
```bash
npm install
# ou
yarn install
```

### 3. Configure o ambiente
Crie um arquivo `.env.local` na raiz do projeto e defina sua conexão com o MongoDB:
```
MONGODB_URI=mongodb+srv://usuario:senha@cluster.mongodb.net/nome-do-banco
```

### 4. Inicie o servidor backend
```bash
node server.js
```

### 5. Inicie o frontend
```bash
npm run dev
# ou
yarn dev
```

## Estrutura do Projeto
```
/
├── components/
│   ├── ui/
│   │   ├── Input.js
│   │   ├── Button.js
│   │   ├── Card.js
│   ├── ExpenseManager.js
├── pages/
│   ├── api/
│   │   ├── expenses.js
│   ├── index.js
├── server.js
├── package.json
├── README.md
```

## Melhorias Futuras
- Implementação de autenticação de usuários
- Melhorias na interface com animações e responsividade
- Exportação de relatórios financeiros em PDF/Excel

## Contribuição
Sinta-se à vontade para contribuir! Basta fazer um fork do repositório e enviar um pull request com suas melhorias.

---

Desenvolvido com ❤ por Brendo Vitorio
