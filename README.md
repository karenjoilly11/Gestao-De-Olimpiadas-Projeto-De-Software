# 🏅 Sistema de Gestão das Olimpíadas (SGO)

Este projeto consiste na modelagem de um sistema para coordenar os diferentes aspectos dos Jogos Olímpicos, incluindo o gerenciamento de competições, inscrições de atletas, alocação de locais e controle de resultados.

## 🚧 Status do Projeto

[![Versão](https://img.shields.io/badge/Versão-v1.0.0-blue?style=for-the-badge)](https://github.com/joaopauloaramuni/laboratorio-de-desenvolvimento-de-software/releases) 
![GitHub repo size](https://img.shields.io/github/repo-size/joaopauloaramuni/laboratorio-de-desenvolvimento-de-software?style=for-the-badge&logo=files) 
![GitHub directory file count](https://img.shields.io/github/directory-file-count/joaopauloaramuni/laboratorio-de-desenvolvimento-de-software?style=for-the-badge&logo=files) 
![GitHub stars](https://img.shields.io/github/stars/joaopauloaramuni/laboratorio-de-desenvolvimento-de-software?style=for-the-badge&logo=github) 
![GitHub forks](https://img.shields.io/github/forks/joaopauloaramuni/laboratorio-de-desenvolvimento-de-software?style=for-the-badge&logo=git) 
![GitHub language count](https://img.shields.io/github/languages/count/joaopauloaramuni/laboratorio-de-desenvolvimento-de-software?style=for-the-badge&logo=python) 
![GitHub license](https://img.shields.io/github/license/joaopauloaramuni/laboratorio-de-desenvolvimento-de-software?style=for-the-badge&color=007ec6&logo=opensourceinitiative) 
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/joaopauloaramuni/laboratorio-de-desenvolvimento-de-software?style=for-the-badge&color=007ec6&logo=gitkraken) 
![GitHub last commit](https://img.shields.io/github/last-commit/joaopauloaramuni/laboratorio-de-desenvolvimento-de-software?style=for-the-badge&logo=clockify) 
![Views Counter](https://views-counter.vercel.app/badge?pageId=https%3A%2F%2Fgithub%2Ecom%2Fjoaopauloaramuni%2Flaboratorio-de-desenvolvimento-de-software&leftColor=555555&rightColor=007ec6&type=total&label=RepoViews)

---

## 📚 Índice
- [Links Úteis](#-links-úteis)
- [Sobre o Projeto](#-sobre-o-projeto)
- [Histórias do Usuário](#-histórias-do-usuário)
- [Funcionalidades Principais](#-funcionalidades-principais)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Arquitetura](#-arquitetura)
  - [Diagramas](#exemplos-de-diagramas)
- [Estrutura de Pastas](#-estrutura-de-pastas)
- [Autores](#-autores)
- [Contribuição](#-contribuição)
- [Agradecimentos](#-agradecimentos)
  
---

## 🔗 Links Úteis
* 🌐 **Construção de Diagrama:** [Acesse o PlantUML](<https://www.plantuml.com/plantuml/uml/SyfFKj2rKt3CoKnELR1Io4ZDoSa70000>)
  > 💻 **Descrição:** Link para a acessar o PlantUML e testar os diagramas.

---

## 📝 Sobre o Projeto

O Sistema de Gestão das Olimpíadas (SGO) é uma plataforma integrada desenvolvida para coordenar a logística, as inscrições e os resultados do maior evento esportivo do mundo. O sistema atua como o núcleo operacional das Olimpíadas, garantindo que o cronograma de provas ocorra sem conflitos e que o quadro de medalhas seja atualizado com precisão.

* 🎯 **Propósito:**
  - Por que existe: Para centralizar o gerenciamento de múltiplos eventos esportivos simultâneos, eliminando falhas de coordenação logística e de comunicação entre delegações e organizadores.
  - Problema que resolve: A complexidade de alocar locais de prova sem sobreposição de horários e a necessidade de validar regras rígidas de representação nacional dos atletas.
  - Contexto: Projeto desenvolvido no ambiente acadêmico para simular um ecossistema real de fidelização educacional.
  - Onde utilizar: Comitês organizadores de eventos poliesportivos e federações que necessitam de um controle rigoroso sobre competições e atletas.

* ✨ **Entrega de Valor:**
  - O projeto transforma a gestão esportiva em um processo automatizado e seguro: os organizadores garantem o uso eficiente da infraestrutura disponível, os atletas asseguram sua participação conforme as regras internacionais e o público ganha transparência total no acesso aos resultados oficiais.

---

## Histórias do Usuário

*   **HS01 - Cadastrar Competição**: Como Operador, desejo cadastrar novas competições (modalidade, data, hora e local) para estabelecer o calendário olímpico.
*   **HS04 - Alocar Local de Prova**: Como Operador, desejo alocar locais específicos para evitar conflitos de horário.
*   **HS07 - Realizar Inscrição**: Como Atleta, desejo me inscrever em uma competição representando apenas um país por modalidade.
*   **HS05 - Registrar Resultados**: Como Operador, desejo registrar os vencedores para alimentar o quadro de medalhas.
*   **HS06 - Gerar Relatório de Medalhas**: Como Operador, desejo visualizar o ranking oficial por país.

---

## ✨ Funcionalidades Principais
As funcionalidades do SGO foram projetadas para atender às necessidades de Operadores e Atletas durante o evento olímpico.

- 🔐 **Autenticação Segura:** Login, Cadastro e Recuperação de Senha.
- ⚙️ **Gerenciamento de CRUD Competições:** Cadastro, alteração e cancelamento de competições, incluindo definição de modalidade, data, hora e local.
- ⚙️ **Gerenciamento de CRUD Locais:** Criação, Leitura, Atualização e Deleção de Locais.
- 📍 **Alocação Inteligente de Locais:** Conexão com serviços de terceiros (pagamentos, mapas, autenticação, etc.).
- ⚙️ **Gerenciamento de CRUD Empresas:** Criação, Leitura, Atualização e Deleção de Empresas.
- 📝 **Gerenciamento de CRUD Atletas:** Criação, Leitura, Atualização e Deleção de Atletas.
- 🥇 **Registro de Resultados e Medalhas:** Lançamento dos vencedores (1º, 2º e 3º lugares) após o encerramento das competições para oficialização no sistema.
- 📊 **Relatórios de Desempenho dos países :** Geração de quadros de medalhas e rankings oficiais por país para visualização do desempenho geral das delegações.
- 📨 **Sistema de Notificações:** Envio de alertas por e-mail, push ou notificações internas.
- 🌐 **Consulta Pública de Resultados:** Visualização dos resultados das competições encerradas para usuários não autenticados, facilitando o acompanhamento público do evento.
- 🌐 **Internacionalização (i18n):** Suporte a múltiplos idiomas.

---

## 🛠 Tecnologias Utilizadas

*   **Linguagem de Modelagem**: UML 2.0
*   **Ferramenta de Diagramação**: [PlantUML](https://plantuml.com/)
*   **Versionamento**: Git e GitHub

---

## 🏗 Arquitetura

### 1. Diagrama de Caso de Uso
Modela as interações entre os atores (Operador, Atleta e Usuário) e as funcionalidades principais.
<img width="600px" src="./Modelagem/Caso%20de%20Uso%20/diagrama-de-caso-de-uso.png"/>

### 2. Diagrama de Classes
Reflete a estrutura estática do sistema, organizando as classes em pacotes de responsabilidade.
<img width="600px" src="./Modelagem/Classe/diagrama-de-classes.png"/>

### 3. Diagrama de Pacotes
Reflete a estrutura estática do sistema, organizando as classes em pacotes de responsabilidade.
<img width="600px" src="./Modelagem/Pacote/diagrama-de-pacotes.png"/>

### 4. Diagrama de Componentes
Ilustra a organização modular do software (Módulo de Inscrições, Alocação, Relatórios, etc.).
<img width="600px" src="./imagens/diagrama-de-componentes.png"/>

### 5. Diagrama de Implantação
Representa a infraestrutura física, incluindo servidores de aplicação, banco de dados e dispositivos.
<img width="600px" src="./imagens/diagrama-de-implantacao.png"/>

---

## 📂 Estrutura de Pastas

Descreva o propósito das pastas principais.

```
.
├── .editorconfig                # ✍️ Padronização de estilo de código.
├── .env.local                   # 🔒 Variáveis SENSÍVEIS do ambiente LOCAL (não versionado).
├── .env.test                    # 🧪 Variáveis de ambiente para TESTES AUTOMATIZADOS.
├── .env.staging                 # ☁️ Variáveis de ambiente para STAGING/HOMOLOGAÇÃO.
├── .env.example                 # 🧩 Exemplo de TODAS as variáveis necessárias (sem valores sensíveis).
├── .gitignore                   # 🧹 Ignora arquivos/pastas não versionadas (.env, node_modules, target, etc.).
├── .vscode/                     # ⚙️ Configurações de ambiente da IDE (opcional).
├── .github/                     # 🤖 CI/CD (Actions), templates de Issues e Pull Requests.
├── README.md                    # 📘 Documentação principal do projeto.
├── CONTRIBUTING.md              # 🤝 Guia de contribuição.
├── LICENSE                      # ⚖️ Licença do projeto.
├── docker-compose.yml           # 🐳 Orquestração dos containers (front/back/db/etc).
├── docker-compose.override.yml  # 🐳 Configurações extras apenas para desenvolvimento.
│
├── /frontend                    # 📁 Aplicação React
│   ├── .env.example             # 🧩 Variáveis de ambiente do Front-end.
│   ├── Dockerfile               # 🐳 Docker build do Front-end.
│   ├── .eslintrc.js             # ✨ Regras do ESLint.
│   ├── .prettierrc              # 🎨 Configuração do Prettier.
│   ├── /public                  # 📂 Arquivos estáticos e index.html.
│   ├── /src                     # 📂 Código-fonte React
│   │   ├── /components          # 🧱 Componentes reutilizáveis (UI).
│   │   ├── /pages               # 📄 Páginas/rotas da aplicação.
│   │   ├── /services            # 🔌 Serviços e chamadas HTTP.
│   │   ├── /hooks               # 🎣 Hooks personalizados.
│   │   ├── /styles              # 🎨 Estilos globais, temas, Design System.
│   │   ├── /assets              # 🖼️ Recursos estáticos importados
│   │   │   ├── /images          # 🖼️ Imagens.
│   │   │   ├── /icons           # 💡 Ícones.
│   │   │   └── /fonts           # ✒️ Fontes personalizadas.
│   │   └── /utils               # 🛠️ Funções utilitárias.
│   ├── package.json             # 📦 Dependências e scripts.
│   └── yarn.lock / package-lock.json # 🔒 Lockfile das dependências.
│
├── /backend                     # 📁 Aplicação Spring Boot
│   ├── .env.example             # 🧩 Variáveis de ambiente do Back-end.
│   ├── Dockerfile               # 🐳 Docker build do Back-end.
│   │
│   ├── /src/main/java           # 📂 Código-fonte Java
│   │   └── /com/exemplo/app
│   │       ├── /controller      # 🎮 Endpoints REST.
│   │       ├── /service         # ⚙️ Regras e lógica de negócio.
│   │       ├── /repository      # 🗄️ Repositórios (JPA/Hibernate).
│   │       ├── /model           # 🧬 Entidades persistentes (JPA).
│   │       ├── /domain          # 🌐 Objetos de Domínio puro (sem anotações).
│   │       ├── /dto             # ✉️ Data Transfer Objects.
│   │       ├── /config          # 🔧 Configurações gerais (DB, Swagger, CORS, etc.).
│   │       ├── /exception       # 💥 Exceptions e handlers globais.
│   │       └── /security        # 🛡️ Autenticação e Autorização (Spring Security).
│   │
│   ├── /src/main/resources      # 📂 Recursos do Spring Boot
│   │   ├── application.yml         # ⚙️ Configuração principal da aplicação
│   │   ├── application-dev.yml     # 🧪 Configurações específicas do ambiente de DESENVOLVIMENTO
│   │   ├── application-prod.yml    # 🚀 Configurações específicas para PRODUÇÃO
│   │   ├── application-test.yml    # 🧪 Configurações usadas nos testes automatizados
│   │   ├── /static                # 🌐 Arquivos estáticos (HTML/CSS/JS).
│   │   ├── /templates             # 🖼️ Templates Thymeleaf/Freemarker.
│   │   ├── /messages              # 🌎 Arquivos de internacionalização (i18n).
│   │   └── /db                    # 💾 Scripts de banco usados pela aplicação
│   │       └── /migration         # 📜 Migrações do banco (Flyway/Liquibase).
│   │
│   ├── /src/test/java            # 🧪 Testes unitários e de integração.
│   └── pom.xml / build.gradle    # 🛠️ Build e dependências.
│
├── /scripts                      # 📜 Scripts de automação
│   ├── dev.sh                    # 🚀 Ambiente de desenvolvimento completo.
│   ├── build_all.sh              # 🛠️ Build geral (front + back).
│   └── deploy.sh                 # ☁️ Deploy em produção/homologação.
│
├── /docs                         # 📚 Documentação, arquitetura, modelos C4, Swagger/OpenAPI.
└── /tests                        # 🧪 Testes End-to-End (Cypress/Playwright).
```

---

## 👥 Autores
Liste os principais contribuidores. Você pode usar links para seus perfis.

| 👤 Nome | 🖼️ Foto | :octocat: GitHub | 💼 LinkedIn | 📤 Gmail |
|---------|----------|-----------------|-------------|-----------|
| Vinícius Simões  | <div align="center"><img src="https://avatars.githubusercontent.com/u/80927829?v=4" width="70px" height="70px"></div> | <div align="center"><a href="https://github.com/ViniSimoesV"><img src="https://joaopauloaramuni.github.io/image/github6.png" width="50px" height="50px"></a></div> | <div align="center"><a href="https://www.linkedin.com/in/user1"><img src="https://joaopauloaramuni.github.io/image/linkedin2.png" width="50px" height="50px"></a></div> | <div align="center"><a href="mailto:user1@gmail.com"><img src="https://joaopauloaramuni.github.io/image/gmail3.png" width="50px" height="50px"></a></div> |
| Karen Joilly | <div align="center"><img src="https://avatars.githubusercontent.com/u/182118759?v=4" width="70px" height="70px"></div> | <div align="center"><a href="https://github.com/karenjoilly11"><img src="https://joaopauloaramuni.github.io/image/github6.png" width="50px" height="50px"></a></div> | <div align="center"><a href="https://www.linkedin.com/in/user2"><img src="https://joaopauloaramuni.github.io/image/linkedin2.png" width="50px" height="50px"></a></div> | <div align="center"><a href="mailto:user2@gmail.com"><img src="https://joaopauloaramuni.github.io/image/gmail3.png" width="50px" height="50px"></a></div> |

---

## 🙏 Agradecimentos
Em ambiente acadêmico, citar fontes e inspirações é crucial (integridade acadêmica). Em ambiente profissional, mostra humildade e conexão com a comunidade.

Gostaria de agradecer aos seguintes canais e pessoas que foram fundamentais para o desenvolvimento deste projeto:

* [**Engenharia de Software PUC Minas**](https://www.instagram.com/engsoftwarepucminas/) - Pelo apoio institucional, estrutura acadêmica e fomento à inovação e boas práticas de engenharia.
* [**Prof. Dr. João Paulo Aramuni**](https://github.com/joaopauloaramuni) - Pelos valiosos ensinamentos sobre **Arquitetura de Software** e **Padrões de Projeto**.
* [**Fernanda Kipper**](https://www.instagram.com/kipper.dev/) - Pelos valiosos ensinamentos em **Desenvolvimento Web**, **DevOps** e melhores práticas em **Front-end**.
* [**Rodrigo Branas**](https://branas.io/) - Pela didática excepcional em **Clean Architecture** e **Clean Code**.
* [**Código Fonte TV**](https://codigofonte.tv/) - Pelo vasto conteúdo e cobertura de notícias, tutoriais e apoio à comunidade de **Desenvolvimento Web**.

---
