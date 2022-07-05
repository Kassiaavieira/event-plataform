# event-plataform
An application for conducting online events, where each class is made available during each day of the week.

## 💻 O projeto

Aplicação desenvolvida durante o Ignite Lab, evento oferecido pela [Rocketseat](https://rocketseat.com.br/), que consiste em uma plataforma para a realização de eventos
on-line, onde cada aula é disponibilizada em um dia específico da semana.

Todas as aulas disponibilizadas no evento são cadastradas no [GraphCMS](https://graphcms.com/), uma ferramenta CMS que oferece uma API GraphQL de conteúdos, sendo utilizada
tanto na criação das aulas, cadastradas no próprio painel da ferramenta, quanto a gravação de inscritos (através das Mutations do GraphQL)no banco de dados da ferramenta.

## ✨ Tecnologias

- [ ] Vite
- [ ] React
- [ ] Typescript
- [ ] TailwindCSS
- [ ] GraphQL
- [ ] Apollo
- [ ] Codegen GraphQL
- [ ] vime

## 🚀Como executar

Clone o repositório:

``` bash
git clone https://github.com/lucasgabriel13/event-platform.git

```

Execute os comandos:

```bash

# Entre na pasta clonada
cd event-platform

# Instale as dependências
npm install

# Crie um arquivo .env.local e insira as variáveis que estão no .env.example
VITE_API_URL=
VITE_API_ACCESS_TOKEN=

# Execute a aplicação
npm run dev

```

A aplicação estará disponível no seu browser pelo endereço http://localhost:3000.

<p align="center">Desenvolvido com 💜 por Kássia Vieira e Rocketseat</p>
