# Java 2026 Carreira OS

> Idioma / Language: **Português (Brasil)** | [English](README.MD)

Roteiro completo para conquistar seu primeiro emprego com Java em 2026, crescer até se tornar um especialista de alto impacto, chegar a empresas de topo e, eventualmente, construir um negócio de mentoria com base em experiência real.

Atualizado em: **24 de fevereiro de 2026**

Este README substitui o prompt original do arquivo e cumpre a tarefa usando uma estrutura inspirada nos sistemas locais de agentes/workflows em:

- `AIOS\aios-core-main\aios-core-main`
- `antigravity-merged`
- `Great Agent`

Especificamente, este roadmap espelha:

- Workflows em fases no estilo AIOS (`development-cycle`, `qa-loop`, `spec-pipeline`, `brownfield-discovery`)
- Workflows Java do Great Agent / Antigravity (`/java-learn`, `/java-spring`, `/java-cloud`)
- Papéis especialistas do Great Agent (`java-senior-architect`, `backend-specialist`, `devops-engineer`, `debugger`, `performance-optimizer`, `security-auditor`, `product-manager`)

## O Que É Isto (e Como Usar)

Isto não é uma lista genérica de "aprender Java".

Isto é um **sistema operacional de carreira**:

- O que aprender
- Em que ordem
- Quais projetos construir
- Como ser contratado
- Como se tornar difícil de substituir
- Como se especializar
- Como transformar credibilidade em mentoria (de forma ética)

Uso recomendado:

1. Leia `Path at a Glance`.
2. Escolha seu nível atual.
3. Siga o checklist da fase.
4. Construa o projeto exigido antes de avançar.
5. Execute o ciclo semanal de revisão.
6. Acompanhe resultados (candidaturas, entrevistas, ofertas, funcionalidades entregues).

## Checagem de Realidade de 2026 (Mercado Java)

### Pelo que as empresas realmente pagam

Em 2026, empresas raramente contratam apenas "sintaxe Java". Elas contratam por:

- Desenvolvimento de APIs backend
- Design de banco de dados e performance
- Confiabilidade em produção
- Deploy em cloud e observabilidade
- Disciplina de segurança e testes
- Capacidade de trabalhar em codebases grandes já existentes
- Comunicação e tomada de decisão

### Quais versões de Java você deve conhecer em 2026

Em **2026-02-24**:

- **JDK 25** está disponível como release GA (a geração LTS mais recente para estudar de forma moderna).
- **JDK 26** está em early access (aprenda a direção, mas não baseie seus fundamentos em recursos de EA).

Estratégia prática para contratação:

- Fique confortável com **Java 17** e **Java 21** (ainda comuns em produção).
- Construa novos projetos de portfólio com **Java 21 ou 25**.
- Acompanhe novos recursos via páginas do JDK/JEP e talks de conferências.

### Realidade de frameworks em 2026

- **Spring Boot** continua sendo o caminho dominante para vagas de backend Java.
- **Quarkus** e **Micronaut** são alternativas fortes em ambientes cloud-native.
- Conhecimento sólido de Java + SQL + HTTP + testes + Docker ainda supera conhecimento apenas de framework.

### IA mudou o jogo, mas não os fundamentos

Ferramentas de IA aceleram a codificação.

Elas **não** substituem:

- julgamento de arquitetura
- habilidade de debugging
- raciocínio de produção
- tradeoffs de system design
- ownership

Os vencedores em 2026 usam IA para ganhar velocidade e ainda constroem profundidade humana.

## Visão Geral do Caminho (Path at a Glance)

| Fase | Objetivo | Tempo | Entrega |
| --- | --- | --- | --- |
| Fase 0 | Setup + sistema de aprendizagem | 1-2 semanas | Ambiente, plano, dashboard de acompanhamento |
| Fase 1 | Fundamentos de Java | 6-10 semanas | Apps CLI + OOP + collections + testes |
| Fase 2 | Backend pronto para vaga | 8-14 semanas | API REST em Spring Boot + DB + auth + testes + Docker |
| Fase 3 | Sistema de conquista do primeiro emprego | Paralelo (2-6 meses) | Currículo, GitHub, LinkedIn, preparação de entrevistas, candidaturas |
| Fase 4 | Crescimento nos primeiros 2 anos | 12-24 meses | Impacto em produção, confiabilidade, performance, arquitetura |
| Fase 5 | Domínio em especialização | 2-5 anos | Especialização reconhecida + OSS/blog/talks |
| Fase 6 | Productização de mentoria | Após prova real | Mentoria/coaching/cursos pagos com resultados reais |

## Modelo Operacional AIOS + Antigravity + Great Agent (Usado Neste README)

Use as pastas locais como seu motor de estudo/trabalho:

### 1. Planejamento e orquestração (inspirado em AIOS)

De `AIOS\aios-core-main\aios-core-main\.aios-core\development\workflows`:

- `development-cycle.yaml` -> seu loop semanal de aprendizagem/construção
- `qa-loop.yaml` -> disciplina de testes e revisão
- `spec-pipeline.yaml` -> transformar ideias de projeto em escopo + marcos
- `brownfield-discovery.yaml` -> aprender dissecando codebases Java existentes
- `greenfield-service.yaml` -> novos projetos backend de portfólio

### 2. Workflows de execução Java (Great Agent / Antigravity)

De:

- `Great Agent\.agent\workflows\java-learn.md`
- `Great Agent\.agent\workflows\java-spring.md`
- `Great Agent\.agent\workflows\java-cloud.md`
- `antigravity-merged\.agent\workflows\java-learn.md`
- `antigravity-merged\.agent\workflows\java-spring.md`
- `antigravity-merged\.agent\workflows\java-cloud.md`

Use em sequência:

1. `/java-learn` -> preencher lacunas conceituais
2. `/java-spring` -> estruturar e entregar APIs
3. `/java-cloud` -> containerizar e fazer deploy

### 3. Pensamento especialista (papéis do Great Agent)

De `Great Agent\.agent\agents\*.md`, rode esses mindsets enquanto constrói:

- `@java-senior-architect` -> correção + convenções + design de longo prazo
- `@backend-specialist` -> implementação de API e serviços
- `@database-architect` -> qualidade de schema e queries
- `@debugger` -> análise de causa raiz
- `@security-auditor` -> auth, segredos e superfície de ataque
- `@devops-engineer` -> deployabilidade e operações
- `@performance-optimizer` -> medição e tuning
- `@product-manager` -> construir algo que usuários realmente precisam

## Fase 0: Monte Seu Sistema de Carreira em Java (1-2 semanas)

### Setup técnico

- Instale JDK 21 e JDK 25 (use SDKMAN, Homebrew, winget ou instaladores dos vendors).
- Instale IntelliJ IDEA Community ou Ultimate.
- Instale Git e crie conta no GitHub.
- Instale Docker Desktop (ou Podman).
- Instale PostgreSQL localmente ou use Docker.
- Instale um cliente REST (Postman/Insomnia/Bruno).

### Setup de produtividade (baseline 2026)

- Aprenda workflows de desenvolvimento assistido por IA, mas exija testes e explicações para código gerado.
- Mantenha um arquivo markdown para registrar:
  - conceitos aprendidos
  - bugs corrigidos
  - projetos entregues
  - erros em entrevistas
  - perguntas para pesquisar

### Setup de carreira

- Crie perfil no LinkedIn (headline, resumo, links de prova).
- Crie README de perfil no GitHub.
- Crie uma página simples de portfólio (opcional no início, obrigatório depois).

Entrega:

- `career-tracker.md`
- Perfil público no GitHub
- Perfil de LinkedIn pronto para networking

## Fase 1: Fundamentos de Java (6-10 semanas)

Resultado alvo: você consegue resolver tarefas lógicas de complexidade média, escrever código OOP limpo, usar testes e explicar o que seu código faz.

### Módulo 1: Sintaxe básica e tipos

Aprenda:

- variáveis, primitivos, wrappers
- controle de fluxo
- métodos
- classes e objetos
- packages
- enums

Construa:

- calculadora CLI
- analisador de notas
- rastreador de gastos (baseado em arquivo)

### Módulo 2: OOP e bases de design

Aprenda:

- encapsulamento
- herança vs composição
- polimorfismo
- interfaces
- classes abstratas
- SOLID (nível introdutório)

Construa:

- sistema de inventário
- gerenciamento de biblioteca (CLI)

### Módulo 3: Collections + generics + estilo funcional

Aprenda:

- `List`, `Set`, `Map`, filas
- generics
- `equals/hashCode`
- streams
- optionals
- lambdas

Construa:

- analisador de logs
- processador CSV
- engine de ranking

### Módulo 4: Exceptions, I/O, datas e configuração

Aprenda:

- exceptions checked vs unchecked
- file I/O e NIO
- serialização básica (e quando não usar)
- `java.time`
- configuração por properties/env

Construa:

- app CLI orientado por configuração
- ferramenta de importação/exportação de arquivos

### Módulo 5: Testes + build tools

Aprenda:

- JUnit 5
- assertions e estrutura de testes
- testes parametrizados
- Mockito básico
- Maven ou Gradle

Regra:

- Nenhum projeto "se forma" sem testes.

### Módulo 6: Concorrência (diferencial que gera contratação)

Aprenda:

- threads e executors
- sincronização
- collections concorrentes
- `CompletableFuture`
- virtual threads (padrões práticos de uso)

Construa:

- demo de processamento concorrente de arquivos
- ferramenta CLI de simulação de carga de API

Entrega da Fase 1:

- **Repositório de Portfólio de Fundamentos Java** com 6-10 projetos pequenos
- 40-60 testes
- README limpo em cada projeto

## Fase 2: Backend Pronto para Vaga (8-14 semanas)

Resultado alvo: você consegue construir e entregar um backend Java com estilo de produção.

Esta fase se alinha diretamente aos workflows locais:

- `Great Agent\.agent\workflows\java-spring.md`
- `Great Agent\.agent\workflows\java-cloud.md`

### Projeto 1 (Obrigatório): API REST com Spring Boot

Construa um produto real (escolha um):

- rastreador de hábitos
- API de faturamento
- API de anotações de livros
- mini CRM
- rastreador de candidaturas a vagas
- serviço de notas de leitura digital

Funcionalidades obrigatórias:

- endpoints REST
- validação
- tratamento de exceções
- persistência com PostgreSQL
- migrations (Flyway ou Liquibase)
- auth (JWT ou login por sessão)
- paginação/filtros
- mapeamento de DTO
- testes de integração
- Dockerfile
- Docker Compose
- documentação OpenAPI
- configurações de ambiente (`dev`, `prod`)

### O que aprender enquanto constrói

#### Ecossistema Spring

- Spring Boot
- Spring Web
- Spring Data JPA
- Spring Validation
- Spring Security
- Actuator
- profiles de configuração

#### Fundamentos de banco de dados

- joins SQL
- índices
- transações
- noções de isolamento
- planos de execução (introdução)
- schema migrations

#### Fundamentos de produção

- logging (estruturado, se possível)
- métricas
- health checks
- padrões de timeout/retry
- config + gerenciamento de segredos

Entregas da Fase 2:

- 1 repositório backend polido
- demo implantada (cloud)
- docs da API
- suíte de testes
- README de decisões de arquitetura

## Fase 3: Sistema de Conquista do Primeiro Emprego (Trilha Paralela)

Resultado alvo: entrevistas e ofertas, não apenas "progresso de estudo".

### Currículo (versão para backend Java)

Seu currículo precisa mostrar:

- APIs backend construídas
- trabalho com dados (SQL, schema, performance)
- testes
- deploy/cloud
- resultados mensuráveis (latência, cobertura de testes, uptime, usuários, requests)

Fraco:

- "Aprendi Java e Spring Boot"

Forte:

- "Construí e implantei API Spring Boot/PostgreSQL com autenticação JWT, setup Docker para local+produção, testes de integração e endpoints de observabilidade; reduzi tempo de consulta em 65% com estratégia de índices e paginação."

### GitHub (prova para contratação)

Seu perfil deve conter:

- repositórios Java fixados
- READMEs limpos com screenshots/diagramas
- instruções de setup
- testes rodando em CI
- issues ou milestones

### LinkedIn (estratégia para 2026)

Use LinkedIn para:

- visibilidade para recrutadores
- networking direcionado
- aprendizado via criadores e engenheiros de empresas
- prova pública (posts, demos de projeto, writeups)

Checklist de perfil no LinkedIn:

- Headline com cargo + stack + valor (`Java Backend Developer | Spring Boot | PostgreSQL | Docker | API Design`)
- Seção About com provas e interesses
- Seção Featured (repos GitHub, demos, artigos)
- Skills alinhadas às descrições das vagas alvo
- "Open to work" configurado para os cargos alvo

### Funil de busca de vaga (trate como sistema)

Acompanhe semanalmente:

- candidaturas enviadas
- taxa de resposta
- triagens com recrutador
- entrevistas técnicas
- take-homes
- rounds finais/onsite
- ofertas
- motivos de rejeição

Cadência mínima de operação:

- 10-25 candidaturas qualificadas/semana
- 5 mensagens de networking/semana
- 2 mock interviews/semana
- 1 melhoria de projeto/semana

### Pilha de preparação para entrevistas

Você precisa das 5:

1. DSA/resolução de problemas (Java)
2. Perguntas práticas de Java + Spring
3. Perguntas de SQL/banco de dados
4. System design (de júnior-friendly -> nível pleno)
5. Comportamental/storytelling

## Fase 4: Primeiro Emprego -> Engenheiro Forte (Anos 1-2)

Seu trabalho não é mais "aprender tudo".

Seu trabalho é se tornar **confiável**.

### Áreas de foco

- Ler código existente mais rápido (habilidade brownfield)
- Entregar mudanças com segurança
- Escrever testes antes/depois de bugfix
- Melhorar observabilidade
- Aprender pipelines de deploy
- Melhorar uma métrica de performance
- Comunicar tradeoffs com clareza

### Movimentos de alavancagem de carreira (alto ROI)

- Assumir ownership de um serviço/módulo
- Corrigir um problema recorrente e doloroso em produção
- Melhorar tempo de build/teste
- Escrever documentação interna que as pessoas realmente usam
- Liderar uma migração pequena (biblioteca, JDK, versão de API)
- Deixar seu time mais seguro (alertas, runbooks, dashboards)

### O que separa engenheiros medianos de alto crescimento

Mediano:

- só escreve o código que foi atribuído

Alto crescimento:

- entende o comportamento do sistema
- faz perguntas melhores
- valida suposições
- mede impacto
- ensina outras pessoas

## Fase 5: Especialize-se e Torne-se Difícil de Substituir (Anos 2-5)

Escolha uma trilha principal e uma secundária.

### Trilha A: Backend Enterprise / APIs de Plataforma (mais comum)

Domine:

- Spring Boot + Spring Security
- REST + mensageria
- PostgreSQL + Redis
- estratégias de cache
- CI/CD e deploys
- observabilidade
- tuning de performance

Bom encaixe para:

- empresas SaaS
- fintechs
- plataformas B2B
- sistemas enterprise internos

### Trilha B: Java Cloud-Native (alta alavancagem)

Domine:

- containers
- Kubernetes
- runtimes de cloud
- fundamentos de infra-as-code
- resiliência de serviços
- autoscaling e noção de custo
- tuning de Java/JVM em containers

Bom encaixe para:

- times de plataforma
- backends de alta escala
- projetos de modernização para cloud

### Trilha C: Java para Dados/Streaming

Domine:

- Kafka
- arquitetura orientada a eventos
- evolução de schema
- idempotência
- tradeoffs de exactly-once
- ferramentas de stream processing (dependente da empresa)

Bom encaixe para:

- fintechs
- e-commerce
- plataformas de analytics/eventos

### Trilha D: Java de Performance / Baixa Latência

Domine:

- tuning de JVM e GC do básico ao avançado
- profiling de alocação
- design de concorrência
- armadilhas de benchmarking
- análise de memória e CPU

Bom encaixe para:

- infraestrutura de trading/mercado
- sistemas em tempo real
- serviços críticos em performance

### Trilha E: Backend Java com Foco em Segurança

Domine:

- OAuth2/OIDC
- conhecimento profundo de Spring Security
- secure coding
- gestão de segredos e chaves
- higiene de dependências e SAST/SCA
- threat modeling

Bom encaixe para:

- fintechs
- saúde
- serviços enterprise de identidade/autenticação

## Fase 6: Construa um Negócio de Mentoria (Só Depois de Prova Real)

Não comece com "quero vender mentoria".

Comece com:

- sistemas entregues
- writeups públicos
- resultados repetíveis com alunos/clientes

### Marcos de credibilidade antes de cobrar de verdade

- 2-5 anos de experiência profissional (dependendo da profundidade)
- portfólio visível e/ou contribuições OSS
- promoções/ofertas/vitórias em entrevistas documentadas
- depoimentos de pessoas que você realmente ajudou
- um nicho claro (exemplos abaixo)

Exemplos de nichos viáveis de mentoria:

- "Transição para backend Java em 6 meses"
- "Coaching de portfólio job-ready com Spring Boot"
- "Mentoria de promoção de júnior para pleno em Java"
- "Preparação para entrevistas de Java backend + system design"
- "Mentoria em backend Java com foco em performance"

### Escada de produtos (ética)

1. Conteúdo gratuito (posts, mini-guias, vídeos curtos)
2. Templates/checklists de baixo custo
3. Q&A em grupo / sessões de estudo
4. Mock interviews 1:1
5. Programa estruturado de mentoria
6. Treinamentos/workshops para times

### Regras que mantêm sua mentoria legítima

- Ensine a partir de experiência, não só teoria.
- Mostre código real e tradeoffs.
- Nunca prometa emprego ou salário.
- Acompanhe resultados com honestidade.
- Continue aprendendo em público.

## Escada de Projetos de Portfólio (O Que Construir)

Construa nesta ordem. Cada projeto deve ter README, testes e uma nota curta de arquitetura.

### Nível 1 (Fundamentos)

- rastreador de gastos CLI
- parser CSV/JSON
- processador concorrente de logs

### Nível 2 (Backend básico)

- API CRUD em Spring Boot (usuários/tarefas/livros)
- integração com PostgreSQL + migrations
- auth com JWT

### Nível 3 (Sinal de pronto para vaga)

- Serviço com estilo de produção contendo:
  - paginação/filtro/ordenação
  - validação
  - testes de integração
  - Docker Compose
  - docs de API
  - pipeline de CI

### Nível 4 (Sinal de pleno)

- Funcionalidade assíncrona/event-driven (Kafka ou simulação de fila)
- Cache + melhorias de performance
- Dashboard de observabilidade e alertas
- Deploy em cloud (containerizado)

### Nível 5 (Sinal de especialização)

Escolha um:

- backend SaaS multi-tenant
- simulador de fluxo de pagamentos
- serviço com foco em auditoria/compliance
- API de alta vazão com rate limiting
- protótipo event-sourced (com writeup de tradeoffs)

## Blueprint de Domínio de Entrevistas (Java 2026)

### 1. DSA (em Java)

Você precisa de competência, não teatro.

Foque em:

- arrays/strings
- hash maps/sets
- stacks/queues
- linked lists
- trees/graphs
- recursão/backtracking
- sorting/searching
- heaps
- intervals
- programação dinâmica (subconjunto prático)

Regra:

- Resolva usando collections do Java + nomes limpos + testes em edge cases.

### 2. Internals da linguagem Java

Tópicos comuns em entrevistas:

- imutabilidade de `String`
- `equals/hashCode`
- diferenças entre collections
- exceptions
- generics
- tradeoffs streams vs loops
- fundamentos de concorrência
- modelo de memória da JVM (intro para júnior, mais profundo para senior)
- noções de GC

### 3. Perguntas práticas de Spring / backend

Tópicos:

- ciclo de vida de beans no Spring (alto nível)
- dependency injection
- `@Transactional`
- armadilhas de JPA (N+1, lazy loading)
- paginação e índices
- fluxo de auth
- status codes REST e idempotência
- validação e tratamento de erros
- cache

### 4. System design (comece cedo, evolua gradualmente)

Caminho júnior/pleno:

- encurtador de URL (conceitual)
- serviço de notificações
- job scheduler
- rate limiter
- serviço de upload de arquivos
- reserva de inventário em e-commerce (tradeoffs)

### 5. Comportamental e comunicação

Use STAR, mas de forma técnica:

- contexto do problema
- restrições
- opções de decisão
- por que você escolheu uma
- resultado (métricas)
- o que você melhoraria hoje

## Loop Semanal de Execução (Agentic / Workflow-Driven)

Use diretamente a ideia dos workflows locais.

### Cadência semanal

Segunda (`/plan` + AIOS `spec-pipeline`)

- escolher 1 objetivo de estudo
- escolher 1 objetivo de feature/projeto
- escolher 1 objetivo de entrevista

Terça-Quinta (`/create`, `/java-learn`, `/java-spring`)

- implementar
- testar
- documentar

Sexta (`/debug`, `qa-loop`)

- caça a bugs
- refactor
- falhas de teste
- rodada de code review

Sábado (`/java-cloud`, `/deploy`)

- containerizar/fazer deploy/melhorar CI

Domingo (`/status` + revisão)

- medir progresso
- atualizar portfólio
- publicar 1 nota de aprendizado

## O Que Aprender em Paralelo (Pensamento, Não Só Código)

É assim que você se torna "imbatível" em especialização e pensamento.

### Pensamento de engenharia

- análise de tradeoffs
- clarificação de requisitos
- pensamento de modos de falha
- pensamento operacional (o que quebra às 2h da manhã)
- pensamento de custo/performance
- entrega incremental

### Pensamento de produto

- quem usa este serviço?
- qual é a dor central do usuário?
- qual é a menor versão útil?
- como o sucesso será medido?

### Pensamento de negócio

- confiabilidade afeta receita
- latência afeta conversão
- DX ruim desacelera times e aumenta custo
- observabilidade reduz custo de downtime

## Índice de Recursos (Cursos, Docs, Criadores, LinkedIn, YouTube, TikTok e Mais)

Este é um índice curado de "tudo o que você precisa". Use como menu, não como lista para maratonar sem critério.

### A. Fontes Oficiais de Java (Comece Aqui)

- [dev.java Learn](https://dev.java/learn/)
- [Oracle Java Downloads](https://www.oracle.com/java/technologies/downloads/)
- [OpenJDK Early Access / Releases](https://jdk.java.net/)
- [JDK 26 Early-Access page](https://jdk.java.net/26/)
- [JDK 25 page (superseded notice + release references)](https://jdk.java.net/25/)
- [OpenJDK JEP Index](https://openjdk.org/jeps/0)
- [Inside Java (blog de engenharia OpenJDK/Oracle)](https://inside.java/)
- [Java API Docs (latest)](https://docs.oracle.com/en/java/)

### B. Cursos de Fundamentos Java (Grátis + Pagos)

- [Java Programming MOOC (University of Helsinki)](https://java-programming.mooc.fi/)
- [Coursera: Java Programming and Software Engineering Fundamentals](https://www.coursera.org/specializations/java-programming)
- [Coursera Java catalog](https://www.coursera.org/courses?query=java)
- [edX Java courses](https://www.edx.org/learn/java)
- [Codecademy: Learn Java](https://www.codecademy.com/learn/learn-java)
- [Hyperskill / JetBrains Academy tracks](https://hyperskill.org/tracks)
- [Udemy Java courses (catalog)](https://www.udemy.com/topic/java/)
- [Pluralsight Java content](https://www.pluralsight.com/browse/software-development/java)
- [LinkedIn Learning Java search](https://www.linkedin.com/learning/search?keywords=java)
- [freeCodeCamp Java articles](https://www.freecodecamp.org/news/tag/java/)
- [freeCodeCamp YouTube (search Java)](https://www.youtube.com/@freecodecamp/search?query=java)

### C. Spring / Backend / Desenvolvimento de APIs

- [Spring Boot Reference Documentation (current)](https://docs.spring.io/spring-boot/reference/)
- [Spring Framework Docs](https://docs.spring.io/spring-framework/reference/)
- [Spring Security Docs](https://docs.spring.io/spring-security/reference/)
- [Spring Initializr](https://start.spring.io/)
- [Spring Guides](https://spring.io/guides)
- [Spring Blog](https://spring.io/blog)
- [Baeldung Java + Spring tutorials](https://www.baeldung.com/)
- [Baeldung Courses](https://www.baeldung.com/courses)
- [Jakarta EE](https://jakarta.ee/)
- [Hibernate ORM Documentation](https://hibernate.org/orm/documentation/)
- [Micronaut Guides](https://guides.micronaut.io/)
- [Micronaut Docs](https://docs.micronaut.io/)
- [Quarkus Guides](https://quarkus.io/guides/)
- [Quarkus Getting Started](https://quarkus.io/get-started/)

### D. Build Tools, Testes e Qualidade

- [Apache Maven Guides](https://maven.apache.org/guides/)
- [Gradle: Building Java Projects](https://docs.gradle.org/current/userguide/building_java_projects.html)
- [JUnit 5 User Guide](https://junit.org/junit5/docs/current/user-guide/)
- [Mockito Documentation](https://site.mockito.org/)
- [Testcontainers for Java](https://java.testcontainers.org/)
- [Testcontainers Guides](https://testcontainers.com/guides/)
- [AssertJ](https://assertj.github.io/doc/)
- [ArchUnit](https://www.archunit.org/)
- [SpotBugs](https://spotbugs.github.io/)
- [Checkstyle](https://checkstyle.org/)
- [SonarQube](https://www.sonarsource.com/products/sonarqube/)

### E. Bancos de Dados, Mensageria e Acesso a Dados

- [PostgreSQL Documentation](https://www.postgresql.org/docs/)
- [PostgreSQL Tutorial (official docs index)](https://www.postgresql.org/docs/current/tutorial.html)
- [Redis Learn](https://redis.io/learn/)
- [Redis Docs](https://redis.io/docs/)
- [Apache Kafka Documentation](https://kafka.apache.org/documentation/)
- [Confluent Developer](https://developer.confluent.io/)
- [RabbitMQ Tutorials (Java included)](https://www.rabbitmq.com/tutorials)
- [Elasticsearch Docs](https://www.elastic.co/guide/index.html)
- [OpenSearch Documentation](https://docs.opensearch.org/)

### F. Cloud, Containers, DevOps e Deploy

- [Docker Documentation](https://docs.docker.com/)
- [Docker Language Specific Guides](https://docs.docker.com/language/)
- [Kubernetes Tutorials](https://kubernetes.io/docs/tutorials/)
- [Helm Docs](https://helm.sh/docs/)
- [GitHub Actions Docs](https://docs.github.com/actions)
- [GitLab CI/CD Docs](https://docs.gitlab.com/ee/ci/)
- [Jenkins Docs](https://www.jenkins.io/doc/)
- [AWS Training and Certification](https://aws.amazon.com/training/)
- [AWS SDK for Java 2.x Developer Guide](https://docs.aws.amazon.com/sdk-for-java/latest/developer-guide/home.html)
- [Google Cloud Training](https://cloud.google.com/training)
- [Google Cloud Java Docs](https://cloud.google.com/java/docs)
- [Microsoft Learn (Azure)](https://learn.microsoft.com/training/)
- [Azure for Java Developers](https://learn.microsoft.com/azure/developer/java/)

### G. Observabilidade, Confiabilidade e Performance

- [OpenTelemetry Java](https://opentelemetry.io/docs/languages/java/)
- [Micrometer Docs](https://docs.micrometer.io/)
- [Prometheus Docs](https://prometheus.io/docs/)
- [Grafana Docs](https://grafana.com/docs/)
- [OpenJDK JMH (Java Microbenchmark Harness)](https://openjdk.org/projects/code-tools/jmh/)
- [async-profiler](https://github.com/async-profiler/async-profiler)
- [Java Flight Recorder / Mission Control docs (Oracle)](https://docs.oracle.com/en/java/)

### H. Segurança (Obrigatório, Não Opcional)

- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/)
- [OWASP ASVS](https://owasp.org/www-project-application-security-verification-standard/)
- [Spring Security Reference](https://docs.spring.io/spring-security/reference/)
- [OAuth 2.0 RFCs / IETF Datatracker (search)](https://datatracker.ietf.org/)
- [OpenID Connect](https://openid.net/developers/how-connect-works/)
- [Snyk Learn](https://learn.snyk.io/)

### I. DSA, Prática de Código e Preparação para Entrevistas

- [LeetCode](https://leetcode.com/)
- [NeetCode](https://neetcode.io/)
- [HackerRank Java](https://www.hackerrank.com/domains/java)
- [Exercism Java Track](https://exercism.org/tracks/java)
- [Codewars](https://www.codewars.com/)
- [CodinGame](https://www.codingame.com/start)
- [Interviewing.io](https://interviewing.io/)
- [Exponent (system design/behavioral prep)](https://www.tryexponent.com/)
- [Roadmap.sh Java](https://roadmap.sh/java)
- [Roadmap.sh Backend](https://roadmap.sh/backend)

### J. System Design e Profundidade em Engenharia de Software

- [ByteByteGo](https://blog.bytebytego.com/)
- [Martin Fowler](https://martinfowler.com/)
- [microservices.io](https://microservices.io/)
- [InfoQ Java](https://www.infoq.com/java/)
- [Thoughtworks Technology Radar](https://www.thoughtworks.com/radar)
- [Google SRE resources](https://sre.google/resources/)

### K. Busca de Vagas, Salários e Infraestrutura de Carreira

- [LinkedIn Jobs](https://www.linkedin.com/jobs/)
- [LinkedIn Learning](https://www.linkedin.com/learning/)
- [LinkedIn Salary](https://www.linkedin.com/salary/)
- [Indeed](https://www.indeed.com/)
- [Dice (tech jobs)](https://www.dice.com/)
- [Wellfound (startups)](https://wellfound.com/jobs)
- [Built In jobs](https://builtin.com/jobs)
- [Levels.fyi](https://www.levels.fyi/)
- [Hacker News Jobs / Who's Hiring](https://news.ycombinator.com/jobs)
- [Hiring Without Whiteboards](https://github.com/poteto/hiring-without-whiteboards)

### L. Comunidades e Aprendizado Contínuo

- [Foojay](https://foojay.io/)
- [Inside Java](https://inside.java/)
- [Stack Overflow Java tag](https://stackoverflow.com/questions/tagged/java)
- [Reddit r/java](https://www.reddit.com/r/java/)
- [Reddit r/learnjava](https://www.reddit.com/r/learnjava/)
- [JetBrains Guide for Java](https://www.jetbrains.com/guide/java/)
- [JetBrains State of Developer Ecosystem (annual)](https://www.jetbrains.com/lp/devecosystem-2025/)
- [Stack Overflow Developer Survey 2025](https://survey.stackoverflow.co/2025/)

### M. YouTube: O Que Assistir (Java + Backend + Carreira)

#### Criadores e canais de Java / Spring

- [Java Brains](https://www.youtube.com/@JavaBrainsChannel)
- [Amigoscode](https://www.youtube.com/@amigoscode)
- [Dan Vega](https://www.youtube.com/@DanVega)
- [Telusko](https://www.youtube.com/@Telusko)
- [Coding with John](https://www.youtube.com/@CodingWithJohn)
- [Devoxx](https://www.youtube.com/@DevoxxForever)
- [JetBrains](https://www.youtube.com/@JetBrainsTV)
- [IntelliJ IDEA](https://www.youtube.com/@IntelliJIDEA)
- [Confluent](https://www.youtube.com/@Confluent)

#### Backend / plataforma / pensamento de sistemas

- [ByteByteGo](https://www.youtube.com/@ByteByteGo)
- [TechWorld with Nana](https://www.youtube.com/@TechWorldwithNana)
- [Docker](https://www.youtube.com/@Docker)
- [Kubernetes / conteúdo CNCF](https://www.youtube.com/@cncf)
- [Google Cloud Tech](https://www.youtube.com/@googlecloudtech)
- [AWS](https://www.youtube.com/@amazonwebservices)
- [Microsoft Azure](https://www.youtube.com/@MicrosoftAzure)

#### O que assistir (procure estes temas nos canais acima)

- deep dives de recursos do Java 21/25
- virtual threads e structured concurrency
- guias de migração Spring Boot 3.x -> 4.x
- performance de JPA e problema de N+1
- testes de integração com Testcontainers
- Dockerizando Spring Boot
- Kubernetes para engenheiros backend
- observabilidade com OpenTelemetry + Grafana
- design de consumers Kafka e retries
- profiling de performance Java / tuning de JVM

### N. TikTok / Aprendizado em Conteúdo Curto (Use com Cuidado)

TikTok é útil para:

- explicações rápidas
- dicas de entrevista
- posicionamento de carreira
- descobrir criadores para seguir em outros lugares

TikTok **não** é suficiente para domínio técnico.

Use como camada de descoberta e depois valide com docs.

Tags/buscas iniciais:

- [TikTok #java](https://www.tiktok.com/tag/java)
- [TikTok #springboot](https://www.tiktok.com/tag/springboot)
- [TikTok #backenddeveloper](https://www.tiktok.com/tag/backenddeveloper)
- [TikTok #softwareengineer](https://www.tiktok.com/tag/softwareengineer)
- [TikTok #leetcode](https://www.tiktok.com/tag/leetcode)
- [TikTok #systemdesign](https://www.tiktok.com/tag/systemdesign)
- [TikTok #interviewtips](https://www.tiktok.com/tag/interviewtips)

Regra de filtro:

- Se um vídeo curto não linka código/docs/exemplos, trate como inspiração, não como verdade.

### O. LinkedIn: Criadores, Conteúdo e Estratégia

#### Use o LinkedIn para 4 coisas

- descoberta de vagas
- descoberta de recrutadores
- rede de pares
- prova pública de aprendizado

#### Tipos de pessoas para seguir (pesquise no LinkedIn)

- Java champions e contribuidores de JDK/OpenJDK
- engenheiros/advocates de Spring
- especialistas em performance de JVM
- hiring managers em times de backend/plataforma
- engenheiros das empresas alvo
- recrutadores especializados em vagas JVM/backend

Exemplos (pesquise/siga no LinkedIn + conteúdo público em outros lugares):

- Josh Long (Spring)
- Dan Vega (Spring/Java)
- Venkat Subramaniam
- Trisha Gee
- Gunnar Morling
- Nicolai Parlog
- Heinz Kabutz
- Vlad Mihalcea
- Sander Mak
- Rafael Winterhalter

#### O que postar no LinkedIn (para conseguir entrevistas, não só likes)

- vídeos curtos de demo de projeto (30-90s)
- posts "o que aprendi construindo X"
- estudos de caso de bug/debug
- melhorias de performance com números
- writeups de tradeoffs de arquitetura
- marcos de certificação (se relevante)

### P. Conferências e Conteúdo de Eventos (Aceleração de Carreira)

- [Devoxx](https://www.devoxx.com/)
- [Spring I/O](https://springio.net/)
- [Oracle JavaOne](https://www.oracle.com/javaone/)
- [Jfokus](https://www.jfokus.se/)
- [QCon](https://qconferences.com/)
- [KubeCon + CloudNativeCon](https://www.cncf.io/kubecon-cloudnativecon-events/)
- [GOTO Conferences](https://gotopia.tech/)

Assista talks de conferências regularmente. É uma das formas mais rápidas de elevar seu nível de pensamento.

### Q. Certificações (Opcionais, mas Úteis em Alguns Mercados)

Certificações não substituem projetos nem experiência.

Elas podem ajudar com:

- filtros de RH
- ambientes de consultoria enterprise
- disciplina de estudo estruturada

Boas opções (dependendo dos objetivos):

- Certificações Oracle Java (procure trilhas Java SE atuais na Oracle University)
- Certificações cloud (AWS/GCP/Azure) se você mira vagas cloud-heavy
- Certificações Kubernetes se você mira plataforma/cloud-native

Comece aqui:

- [Oracle University / Training & Certification](https://education.oracle.com/)
- [Oracle Learning Explorer](https://learn.oracle.com/)
- [AWS Training and Certification](https://aws.amazon.com/training/)
- [Google Cloud Training](https://cloud.google.com/training)
- [Microsoft Learn](https://learn.microsoft.com/training/)
- [CNCF Certifications](https://training.linuxfoundation.org/certification/)

## Livros (Ainda Valem a Pena em 2026)

Leia para profundidade, não para velocidade.

### Java e JVM (base)

- *Effective Java* (Joshua Bloch)
- *Java Concurrency in Practice* (Brian Goetz et al.) - clássico; combine com talks mais novos de concorrência no JDK
- *Modern Java in Action*
- *Core Java* (Cay S. Horstmann)

### Spring / Java Enterprise

- *Spring Start Here* (Laurentiu Spilca)
- *Spring Security in Action* (para trilha com foco em segurança)
- *High-Performance Java Persistence* (Vlad Mihalcea)

### Arquitetura / Sistemas / Engenharia

- *Designing Data-Intensive Applications*
- *Fundamentals of Software Architecture*
- *Building Microservices* (entenda tradeoffs, não dogmas)
- *Domain-Driven Design* (conceitos selecionados)
- *Refactoring*
- *The Pragmatic Programmer*
- *Site Reliability Engineering* / *The SRE Workbook*

## Plano de 30 / 60 / 90 / 180 Dias (Caminho Mais Rápido para o Primeiro Emprego)

### Primeiros 30 dias

- Concluir módulos de fundamentos Java (sintaxe, OOP, collections)
- Entregar 3 apps CLI
- Começar JUnit
- Configurar LinkedIn + GitHub

### Dias 31-60

- Streams, exceptions, build tools, fundamentos de SQL
- Iniciar projeto Spring Boot
- Adicionar PostgreSQL e migrations
- Iniciar prática de DSA (3-5 problemas/semana)

### Dias 61-90

- Adicionar auth, testes, Docker e CI
- Fazer deploy do projeto
- Escrever README do projeto e notas de arquitetura
- Começar candidaturas e networking

### Dias 91-180

- Construir segundo projeto ou elevar o primeiro a nível de produção
- Mock interviews semanais
- Aprender fundamentos de observabilidade e performance
- Aplicar com consistência e iterar com base no feedback

## Plano de Crescimento de 2 Anos (De "Empregado" para "Perigosamente Bom")

### Ano 1

- Tornar-se confiável em um time/serviço
- Corrigir bugs mais rápido que seus pares
- Melhorar hábitos de testes e debugging
- Aprender deploy/monitoramento
- Escrever 5-10 notas/posts técnicos fortes

### Ano 2

- Assumir melhorias em um subsistema
- Liderar uma migração ou iniciativa de confiabilidade
- Aprofundar especialização (escolha uma trilha)
- Contribuir para OSS ou frameworks internos
- Construir expertise pública reconhecível

## Alvo de Empresas Gigantes (Big Tech / Enterprise Top-Tier / Alta Escala)

Para chegar a empresas poderosas, você precisa de mais do que familiaridade com stack.

Você precisa de evidência de:

- profundidade (em uma área)
- amplitude (backend + ops + fundamentos de dados)
- clareza (comunicação)
- consistência (entrega)

### Sinais de portfólio que importam nesse nível

- writeups de benchmarking e tuning de performance
- docs de arquitetura focadas em tradeoffs
- observabilidade com cara de produção
- testes de carga e tratamento de falhas
- raciocínio de segurança
- automação de CI/CD e deploy

### Estude o que times de topo publicam

Leia blogs de engenharia das empresas alvo e mapeie as ideias de volta para seus projetos.

Exemplos:

- Netflix TechBlog
- Uber Engineering
- Stripe Engineering
- Airbnb Engineering
- Cloudflare Blog
- AWS Architecture Blog
- Google Cloud Blog

## Erros Comuns Que Atrasam Carreiras em Java

- Aprender frameworks antes de aprender Java e SQL
- Fazer muitos tutoriais e poucos projetos originais
- Sem testes
- Sem deploy
- Sem documentação
- Sem networking
- Esperar se sentir "pronto" para começar a aplicar
- Consumir conteúdo curto como substituto de estudo profundo
- Correr atrás de certificações sem projetos práticos

## Conjunto Final de Regras

- Construa enquanto aprende.
- Teste enquanto constrói.
- Faça deploy do que constrói.
- Documente o que faz deploy.
- Meça o que melhora.
- Ensine o que domina.
- Monetize só depois que os resultados forem reais.

## Notas Sensíveis a Data (Validadas em 2026-02-24)

- A página de downloads do Java da Oracle lista releases atuais do JDK e trilhas de suporte.
- `jdk.java.net` mostra JDK 26 em early-access e o status da página de release do JDK 25.
- A documentação de referência atual do Spring Boot foi checada e mostra links versionados atuais (incluindo referências 4.x e 3.5.x).

## Próximo Passo Sugerido (Use as Pastas Locais de Agentes Imediatamente)

1. Rode uma sessão `/plan` baseada neste README.
2. Rode `/java-learn` para sua lacuna atual.
3. Rode `/java-spring` para estruturar sua API principal de portfólio.
4. Rode `/java-cloud` para fazer o deploy.
5. Repita semanalmente com `development-cycle` + `qa-loop` no estilo AIOS.
