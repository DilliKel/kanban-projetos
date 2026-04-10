# Kanban Projetos
> Aplicação web de quadro Kanban para organizar projetos, tarefas e status de execução.

## Sobre
O Kanban Projetos foi criado para permitir o gerenciamento visual, simples e eficiente de projetos e atividades, possibilitando cadastrar projetos, tarefas/cards, atribuir responsáveis e mover cards entre estágios (Pendente, Fazendo e Feito) via drag-and-drop.  
O desenvolvimento foi conduzido como projeto final do Módulo 04 no curso de Desenvolvimento Full Stack (ITEAM), na matéria de Frontend com React.  
Liderei um squad de 5 pessoas, delegando e codificando a maior parte das funcionalidades, arquitetando a estrutura básica, revisão e testes do sistema.

## Funcionalidades
- [x] Cadastro de novos projetos
- [x] Criação de cards/tarefas em cada projeto
- [x] Edição, remoção e atribuição de responsáveis por card
- [x] Arrastar e soltar cards entre "Pendente", "Fazendo" e "Feito"
- [x] Armazenamento e persistência dos dados no navegador (sem backend)
- [x] Interface responsiva (PC e mobile)
- [ ] Integração com APIs externas (não implementado)
- [ ] Controle de permissões de usuário (não implementado)
- [ ] Busca e filtros avançados (não implementado)

## Stack utilizada
- **React**: Construção de componentes e lógica do aplicativo
- **Vite**: Bundler e ambiente de desenvolvimento
- **React Router Dom**: Navegação entre views/páginas do app
- **LocalStorage**: Persistência dos dados no navegador
- **CSS/Styled Components** (conforme estrutura): Estilização responsiva e visual

## Como rodar localmente
1. Clone o repositório:
   ```bash
   git clone https://github.com/DilliKel/kanban-projetos.git
   cd kanban-projetos
   ```
2. Instale as dependências:
   ```bash
   npm install
   ```
3. Inicie o servidor local:
   ```bash
   npm run dev
   ```
4. Acesse `http://localhost:5173` no navegador.

Ou acesse online: [kanban-projetos.vercel.app](https://kanban-projetos.vercel.app/)

> Não é necessário backend ou configuração adicional. Tudo é salvo localmente.

## Aprendizados
- Liderança técnica de squad: divisão de tarefas e revisão/auxílio individual
- Arquitetura de quadros kanban usando React de forma componentizada e sustentável
- Implementação precisa de lógica de drag-and-drop para controlar status das tarefas
- Persistência de dados offline via localStorage sem dependência de backend
- Montagem de UI responsiva e usável em desktop e mobile

## Status do projeto
Concluído  
Todas as funcionalidades propostas e requisitos mínimos foram implementados e aprovados com nota máxima na avaliação acadêmica.

---
