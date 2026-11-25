<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/profile/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/profile/banner-light.svg">
  <img src="./assets/profile/banner-light.svg" width="100%" alt="">
</picture>

<div align="center">

# Matheus Santos

**Engenheiro de Software**

Construo aplicações web com foco em back-end, dados e integrações de IA local.

[**Portfólio**](https://mthsantos.vercel.app) &nbsp;·&nbsp; [**LinkedIn**](https://linkedin.com/in/mthsantos061) &nbsp;·&nbsp; [**E-mail**](mailto:mmarinhods@gmail.com)

</div>

## Projetos em destaque

### NexaDesk · Central de atendimento

Criei uma central de atendimento que roda localmente. A equipe organiza solicitações em filas e no Kanban, registra respostas e controla o acesso por papel.

**Testes de integração** exercitam o fluxo de atendimento e verificam quem pode acessar notas internas e anexos.

**Stack** · Next.js · TypeScript · PostgreSQL

[**Ver código**](https://github.com/mmarinhods-cloud/nexadesk) · [Ver teste de integração](https://github.com/mmarinhods-cloud/nexadesk/blob/main/tests/workflows.integration.mjs)

<img src="./assets/profile/nexadesk-kanban.webp" width="100%" alt="Kanban do NexaDesk com tickets fictícios distribuídos pelas colunas Aberto, Em andamento, Aguardando cliente e Resolvido.">

<details>
<summary>Ver o fluxo em ação</summary>

![O ticket 1042 é arrastado da coluna Aberto para Em andamento no NexaDesk.](./assets/profile/nexadesk-kanban.gif)

</details>

### NexusChat · Conversas com IA local

Criei uma interface para conversar com modelos rodando no Ollama e consultar documentos sem precisar carregar o texto manualmente a cada pergunta. As respostas aparecem em streaming.

Na **rota de chat**, recupero o conteúdo do documento selecionado e o adiciono ao contexto enviado ao modelo.

**Stack** · Next.js · TypeScript · Ollama · PostgreSQL · Prisma

[**Ver código**](https://github.com/mmarinhods-cloud/nexuschat) · [Ver rota de chat](https://github.com/mmarinhods-cloud/nexuschat/blob/main/src/app/api/chat/route.ts)

<img src="./assets/profile/nexuschat-conversa.webp" width="650" alt="Conversa no NexusChat sobre os três marcos de um plano fictício, com plano-aurora.md selecionado como contexto.">

*Captura com documento fictício e resposta de teste.*

### Estante · Acompanhamento de leitura

Criei um acervo pessoal para importar livros do Google Books e da Open Library, registrar o progresso e acompanhar o ritmo de leitura.

Busco nos **dois catálogos em paralelo**. Se um falha, a busca exibe os resultados do outro e informa a falha parcial.

**Stack** · Angular · TypeScript · RxJS

[**Ver código**](https://github.com/mmarinhods-cloud/Estante) · [Ver busca nos catálogos](https://github.com/mmarinhods-cloud/Estante/blob/main/src/app/features/explore/explore-page.ts)

<img src="./assets/profile/estante-painel.webp" width="650" alt="Painel do Estante com indicadores de um acervo fictício, conclusões por mês e distribuição por status de leitura.">

<details>
<summary>Outros projetos</summary>

- [**TaskTracker**](https://github.com/mmarinhods-cloud/tasktracker) · Gerenciador de tarefas em Python com validação de entradas e testes automatizados.
- [**Matheus Browser**](https://github.com/mmarinhods-cloud/Navegador-python) · Navegador desktop em Python e PyQt6 com abas e favoritos.

</details>

## Tecnologias

**Back-end e dados**

<p>
  <img src="./assets/profile/icons/nodedotjs.svg" width="24" height="24" align="middle" alt="">&nbsp;Node.js&nbsp;
  <img src="./assets/profile/icons/postgresql.svg" width="24" height="24" align="middle" alt="">&nbsp;PostgreSQL&nbsp;
  <img src="./assets/profile/icons/prisma.svg" width="24" height="24" align="middle" alt="">&nbsp;Prisma&nbsp;
  <img src="./assets/profile/icons/python.svg" width="24" height="24" align="middle" alt="">&nbsp;Python
</p>

**Interfaces**

<p>
  <img src="./assets/profile/icons/typescript.svg" width="24" height="24" align="middle" alt="">&nbsp;TypeScript&nbsp;
  <img src="./assets/profile/icons/nextdotjs.svg" width="24" height="24" align="middle" alt="">&nbsp;Next.js&nbsp;
  <img src="./assets/profile/icons/react.svg" width="24" height="24" align="middle" alt="">&nbsp;React&nbsp;
  <img src="./assets/profile/icons/angular.svg" width="24" height="24" align="middle" alt="">&nbsp;Angular
</p>

**IA local**

<p>
  <img src="./assets/profile/icons/ollama.svg" width="24" height="24" align="middle" alt="">&nbsp;Ollama
</p>

**Aprofundando agora** · FastAPI, AWS e aplicações com LLMs.

## Sobre mim

Sou formado em **Análise e Desenvolvimento de Sistemas** e curso **Ciência da Computação**. Me interesso pela engenharia por trás dos produtos, especialmente APIs, modelagem de dados e integração de IA.

<details>
<summary>Atividade no GitHub</summary>

![Uma animação Snake percorre minha grade de contribuições no GitHub.](https://raw.githubusercontent.com/mmarinhods-cloud/mmarinhods-cloud/output/github-contribution-grid-snake.svg)

</details>
