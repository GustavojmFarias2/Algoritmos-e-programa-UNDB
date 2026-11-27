# 📓 LOGBOOK AFP — Algoritmos e Programação (2026.2)

> **Como usar este arquivo:** copie-o para a raiz do **seu** repositório (ou para `logbook/LOGBOOK.md`) e preencha **direto no GitHub** (botão ✏️ *Edit this file*) ou no VS Code. Ele reúne todos os instrumentos do Protocolo AFP 2026.2 (Logbook Individual — Campos 01 a 04, 06 e 07; Registro de Revisão por Pares — Campo 05; Checkpoint Conceitual; Rubrica de Defesa Técnica).
>
> **Organização:** o Logbook está dividido em **3 grupos de entrega**, cada um com seu prazo. Dentro de cada grupo, os **ciclos de entrega (01 a 12)** continuam os mesmos, com as orientações de preenchimento. Siga a ordem: **Grupo 1 → Grupo 2 → Grupo 3 → Defesa Técnica**.
>
> O `Diario.md` do checklist passa a ser **este arquivo**: o registro de cada ciclo está na seção do ciclo correspondente.

## 📍 Navegação rápida

| Seção | Prazo |
|---|---|
| [👨‍🎓 Identificação](#-identificação) | Hoje |
| [🟢 Grupo 1](#-grupo-1--prazo-segunda-1611-às-23h59) · Registros 01–04, Campos 01 e 02 | **Segunda 16/11, 23h59** |
| [🟠 Grupo 2](#-grupo-2--prazo-sábado-2111-às-23h59) · Registros 05–08, Checkpoint, Campos 03 e 04 | **Sábado 21/11, 23h59** |
| [🔵 Grupo 3](#-grupo-3--prazo-quinta-2611-às-23h59) · Registros 09–12, Campos 05, 06 e 07 | **Quinta 26/11, 23h59** |
| [🏁 Defesa Técnica](#-defesa-técnica--quarta-1811) | **Quarta 18/11** |
| [🆘 Estou atrasado](#-estou-atrasado-no-logbook-e-agora) | — |

---

## 👨‍🎓 Identificação

| Campo | Preencha |
|---|---|
| **Nome do estudante** | _Gustavo de Jesus Magalhães Farias_ |
| **Curso / Módulo** | _Engenharia de Software · 2º período_ |
| **Unidade curricular** | Algoritmos e Programação — UnDB 2026.2 |
| **Professor** | Rondineli Seba Salomão |
| **App-base do meu CRUD** | _HEVY - Gerenciamento de academia_ |
| **Link do meu repositório** | _[https://github.com/…](https://github.com/GustavojmFarias2/Algoritmos-e-programa-UNDB.git)_ |
| **Dupla de revisão (Campo 05)** | _Filipe Gabriel_ |
| **Função neste ciclo** | _Autor do meu CRUD · Revisor do CRUD de um colega_ |

---

## 🧭 Regras de ouro (leia antes de preencher)

1. **Processo, não resultado.** O Logbook mostra *como você pensou*, não só o que funcionou. Registre erros, desvios e dúvidas reais.
2. **Vocabulário técnico.** Use os termos da área (ex.: "laço de repetição", "validação de entrada", "estrutura de dados"). Respostas genéricas ("aprendi Python") não são aceitas.
3. **Todo registro relevante tem 3 âncoras:** o **objeto de conhecimento** mobilizado + a **justificativa técnica** + a **referência/fonte**. *Decisão sem objeto de conhecimento e sem referência é considerada não rastreável e não conta para a avaliação formativa.*
4. **Coerência entre campos.** O Campo 02 deve ser coerente com o Campo 01. *Incoerência é evidência de autoria externa.* O Campo 07 retoma o Campo 01.
5. **IA é permitida e avaliada (Campo 04).** *Print sem análise crítica = devolução imediata. Reproduzir a IA sem questionamento = reprovado.* Você precisa mostrar o que aceitou **e** o que questionou/descartou, com argumento técnico.
6. **O histórico do Git é a sua evidência.** Faça commits pequenos e frequentes. Nunca reescreva o histórico (`force push`) do arquivo do Logbook.
7. **Campo 01 e Checkpoint são "sem consulta".** Preencha em um bloco contínuo, sem internet, sem material e sem colegas, no tempo indicado (Campo 01: durante o laboratório; Checkpoint: 20 min). Depois **não edite** esses campos — se perceber um erro, corrija em um campo posterior (Campo 03 ou 07), explicando.
8. **Os prazos dos grupos (16/11, 21/11 e 26/11, às 23h59)** valem para o commit no GitHub. O horário do commit é o registro oficial.

### ✅ Padrão de commit do Logbook

```text
docs(logbook): campo 01 — ciclo 02
docs(logbook): registro do ciclo 05
docs(logbook): campo 05 — revisão do CRUD de <colega>
```

---

## 🗓️ Calendário de entregas e Defesa

Os grupos têm **5 dias entre um prazo e outro**. O horário do commit no GitHub é o registro oficial.

| Grupo | Janela de preenchimento | **Prazo** | O que entregar |
|:--:|---|---|---|
| **1** | Qua 11/11 → seg 16/11 | **Segunda 16/11, 23h59** | Identificação · Registros dos Ciclos 01 a 04 · Campo 01 · Campo 02 |
| **2** | Seg 16/11 → sáb 21/11 | **Sábado 21/11, 23h59** | Registros dos Ciclos 05 a 08 · Checkpoint Conceitual · Campo 03 · Campo 04 |
| **3** | Sáb 21/11 → qui 26/11 | **Quinta 26/11, 23h59** | Registros dos Ciclos 09 a 12 · Campo 05 (2 revisões) · Campo 06 · Campo 07 |
| 🏁 | — | **Quarta 18/11** | **Defesa Técnica individual** (Rubrica) |

### Linha do tempo

| Data | Evento |
|---|---|
| Qua 11/11 | **Hoje:** começa o Grupo 1 |
| Seg 16/11 | ✅ Prazo do **Grupo 1** |
| **Qua 18/11** | 🏁 **Defesa Técnica** |
| Sáb 21/11 | ✅ Prazo do **Grupo 2** |
| Qua 25/11 | Avaliação P2 |
| Qui 26/11 | ✅ Prazo do **Grupo 3** |
| Qua 02/12 | Avaliação Substitutiva |
| Qua 09/12 | Avaliação Final |

> ⚠️ **Atenção:** a Defesa Técnica (18/11) acontece **antes** dos prazos dos Grupos 2 e 3. Na defesa você será arguido sobre **o que já estiver registrado e commitado**. Veja a seção [Defesa Técnica](#-defesa-técnica--quarta-1811) para saber o que priorizar até 18/11.

### Ciclos de entrega por grupo

| Ciclo | Data da aula | Tema do ciclo | Grupo | O que preencher |
|:--:|:--:|---|:--:|---|
| 01 | 12/08 | Preparação do laboratório e escolha do projeto | **1** | Registro do Ciclo |
| 02 | 19/08 | Variáveis, tipos de dados, entrada/saída | **1** | Registro + **Campo 01** + **Campo 02** |
| 03 | 26/08 | Operadores, fluxogramas, paradigmas | **1** (registro) · **2** (campos) | Registro (G1) · **Checkpoint**, **Campo 03**, **Campo 04** (G2) |
| 04 | 02/09 | Condicionais: `if`, `elif`, `else` | **1** | Registro do Ciclo |
| 05 | 09/09 | Condicionais aninhadas e operadores lógicos | **2** | Registro do Ciclo |
| 06 | 30/09 | Repetição: `for`, `while`, `break`, `continue` | **2** | Registro do Ciclo (inclui devolutiva da P1) |
| 07 | 07/10 | Listas: armazenamento e iteração | **2** | Registro do Ciclo |
| 08 | 14/10 | Busca e introdução a dicionários/matrizes | **2** | Registro do Ciclo |
| 09 | 21/10 | Atualização e exclusão: CRUD completo | **3** | Registro + **Campo 05** (revisão nº 1) |
| 10 | 28/10 | Modularização: funções | **3** | Registro do Ciclo |
| 11 | 04/11 | Recursividade | **3** | Registro + **Campo 06** |
| 12 | 11/11 | Refatoração e qualidade de código | **3** | Registro + **Campo 05** (revisão nº 2) + **Campo 07** |

---

## 📊 Painel de acompanhamento

Atualize a cada commit (troque ⬜ por ✅).

| Grupo | Item | Prazo | Preenchido | Commit |
|:--:|---|---|:--:|:--:|
| 1 | Identificação | 16/11 | ✅ | ✅ |
| 1 | Registros dos Ciclos 01, 02, 03 e 04 | 16/11 | ✅ | ✅ |
| 1 | Campo 01 — Instrumento de entrada | 16/11 | ✅ | ✅ |
| 1 | Campo 02 — Aprofundamento | 16/11 | ✅ | ✅ |
| 2 | Registros dos Ciclos 05, 06, 07 e 08 | 21/11 | ✅ | ✅ |
| 2 | Checkpoint Conceitual | 21/11 | ✅ | ✅ |
| 2 | Campo 03 — Execução e desvios | 21/11 | ✅ | ✅ |
| 2 | Campo 04 — Interação com IA | 21/11 | ✅ | ✅ |
| 3 | Registros dos Ciclos 09, 10, 11 e 12 | 26/11 | ✅ | ✅ |
| 3 | Campo 05 — Revisão por pares nº 1 e nº 2 | 26/11 | ✅ | ✅ |
| 3 | Campo 06 — Próximos passos | 26/11 | ✅ | ✅ |
| 3 | Campo 07 — Evolução conceitual | 26/11 | ✅ | ✅ |
| 🏁 | Defesa Técnica | 18/11 | ✅ | — |

---

## ❓ A questão-problema da AFP

**Título:** *O sistema em produção: diagnosticando as falhas do CRUD que você mesmo construiu.*

> **Enunciado completo (Apêndice A):** _professor(a): cole aqui o enunciado e os anexos liberados conforme o cronograma._

A questão-problema é **a mesma durante todo o semestre**: ela se aplica ao **seu** CRUD, que cresce a cada ciclo. Os **dados com defeito** do seu app chegam em um **lote cumulativo único** e vão expondo problemas diferentes conforme sua estrutura evolui. Seu trabalho é diagnosticar, ajustar o CRUD para tratar cada falha e **registrar o raciocínio** neste Logbook.

---

# 🔁 REGISTRO DO CICLO — modelo (copie em cada ciclo)

Cada ciclo tem sua própria seção abaixo, já com o modelo. Se precisar de espaço extra, acrescente linhas.

```markdown
### Registro do Ciclo NN — DD/MM
1. **Desafio do ciclo (em 1 frase):**
2. **O que implementei (commits / arquivos / links):**
3. **Objeto(s) de conhecimento mobilizado(s) (vocabulário técnico):**
4. **Desvio ou erro encontrado + causa técnica:**
5. **Decisão de ajuste + fonte (livro, doc, vídeo, colega, IA):**
6. **Feedback recebido (professor/colega) e o que mudei por causa dele:**
7. **Próximo passo:**
```

**Como preencher bem:** escreva como se explicasse a um colega que não esteve na aula. O item 3 e o item 5 são os mais importantes: eles ligam o que você fez ao **conteúdo** e à **fonte**.

| ❌ Fraco | ✅ Forte |
|---|---|
| "Aprendi a usar `if`." | "Usei estrutura condicional aninhada para validar a idade antes de cadastrar. Meu erro foi comparar `str` com `int` (resultado de `input()`); corrigi com `int()` (Pense em Python, cap. 2)." |
| "Deu erro e consertei." | "O programa quebrou com `ZeroDivisionError` ao calcular a média de um item sem avaliações. Causa: divisão por `len(lista)` com lista vazia. Ajuste: testar `if len(lista) > 0`." |

---

# 🟢 GRUPO 1 — prazo segunda 16/11 às 23h59

> **Janela:** quarta 11/11 → segunda 16/11. **O que entregar:** Identificação · Registros dos Ciclos 01, 02, 03 e 04 · Campo 01 · Campo 02.
>
> **Sugestão de ordem:** (1) Identificação → (2) **Campo 01 primeiro, sem consulta** → (3) Registros dos Ciclos 01 a 04 → (4) Campo 02, com pesquisa.

**Checklist do Grupo 1**
| ❌ Fraco | ✅ Forte |
- [✅] Identificação preenchida (app-base, link do repositório, dupla de revisão)
- [✅] Campo 01: 3 objetos de conhecimento, 3 lacunas, hipótese de até 5 linhas
- [✅] Registros dos Ciclos 01, 02, 03 e 04 com os 7 itens
- [✅] Campo 02: 2 referências com contribuição, hipótese revisada, 3 recursos
- [✅] Commits no GitHub e painel atualizado

## 🟢 CICLO 01 — 12/08 — Preparação do laboratório e escolha do projeto

<details>
<summary>📘 Orientações do Ciclo 01</summary>

- **Hoje não há Campo do Protocolo.** O foco é preparar o ambiente: criar o repositório, configurar o VS Code e escolher o **app-base** do seu CRUD (e, portanto, o *schema* dos seus dados).
- Preencha a **Identificação** (no início deste arquivo) e o **Registro do Ciclo 01**.
- No item 3, registre **o que você já sabia** e o que era novo (Git, GitHub, VS Code). Isso será útil para o Campo 07.
- No item 4, registre qualquer problema de instalação ou configuração e como o resolveu — isso conta como desvio.
- Faça o primeiro commit: `docs(logbook): registro do ciclo 01`.
</details>

#### Registro do Ciclo 01 — 12/08
1. **Desafio do ciclo (em 1 frase):** _Preparar e definir um projeto que pudesse ser desenvolvido utilizando comhecimentos de lógica de programação._
2. **O que implementei (commits / arquivos / links):** _Iniciei a organização do projeto HEVY, voltado ao gerenciamento de exercícios físicos. Também trabalhei na organização de desenvolvimento e na preparação do repositório para armazenar os arquivos do projeto._
3. **Objeto(s) de conhecimento mobilizado(s):** _Lógica de programação e gerenciamento de repositórios no GitHub._
4. **Desvio ou erro encontrado + causa técnica:** _Uma das dificuldades foi compreender melhor a utilização do GitHub, e a organização dos arquivos de projeto, principalmente por ainda estar me adaptando com a plataforma._
5. **Decisão de ajuste + fonte:** _Busquei entender melhor o funcionamento do GitHub e organizar os arquivos de maneira mais adequada, utilizando as orientações apresentadas durante as aulas._
6. **Feedback recebido e o que mudei:** _As orientações das aulas ajudaram a compreender a importância de organizar o projeto desde o início e manter um registro do desenvolvimento._
7. **Próximo passo:** _Continuar o desenvolvimento do HEVY, utilizando Python e aplicando os conceitos de lógica de programação nas funcionalidades do sistema._

## 🟢 CICLO 02 — 19/08 — Variáveis, tipos de dados e entrada/saída

<details>
<summary>📘 Orientações do Ciclo 02 — Campo 01 (sem consulta) e Campo 02 (pesquisa)</summary>

**Campo 01 — Instrumento de entrada** · *sem consulta · faça primeiro*
- Preencha **antes de tudo**, em um bloco contínuo de cerca de 15 minutos, sem internet, sem material, sem IA e sem colegas, depois de conhecer a questão-problema e a primeira amostra de dados do seu app. Depois do Campo 01 você pode consultar o que quiser.
- **1a.** Liste pelo menos **3 objetos de conhecimento** que você acha que precisa dominar para resolver o problema. Use o vocabulário técnico da área. *Não precisa acertar tudo — o Campo 07 vai mostrar o quanto você evoluiu.*
- **1b.** Liste pelo menos **3 lacunas**: o que você **não sabe** e precisa descobrir, com precisão (ruim: "não sei programar"; bom: "não sei como validar a entrada para impedir que o usuário digite texto onde espero número").
- **1c.** Escreva sua **hipótese inicial** em até 5 linhas: o que você acha que está causando as falhas do CRUD e por quê.
- Faça o commit **logo ao terminar**. Depois, **não edite** o Campo 01.

**Campo 02 — Aprofundamento** · *AV Qualis · segunda 16/11, 23h59*
- Preencha **depois do Campo 01, com pesquisa real**, e seja coerente com ele.
- **2a.** Pelo menos **2 referências** (livro, documentação, vídeo, artigo), cada uma com a **contribuição** concreta para a sua solução. Não basta listar o título.
- **2b.** **Hipótese revisada:** o que mudou em relação ao Campo 01 e **por quê**. Se não mudou nada, explique por que a pesquisa confirmou a hipótese.
- **2c.** **Dimensionamento inicial de recursos** (mínimo 3 itens), com quantidade estimada e justificativa técnica. Exemplos de recursos no seu contexto: horas de estudo, número de casos de teste, módulos/arquivos do projeto, dados de teste, bibliotecas.
</details>

### 🧩 CAMPO 01 — Instrumento de entrada
*Grupo 1 | Prazo segunda 16/11, 23h59 | SEM CONSULTA*

**1a. Objetos de conhecimento identificados (mínimo 3, com vocabulário técnico):**
1. _As estruturas condicionais como o "if, elif e else" para controlar as opcões do GRUD da melhor forma._
2. _Também as estruturas de repetição utilizada no GRUD, como "while" para manter o menu funcionando até o usuário querer sair, sendo crucial pro funcionamento do meu GRUD de academia, que utilizo MENU._
3. _Os tipos de dados e variáveis, como os números inteiros, decimais, armazenamento de texto e valores booleanos, essencial para o meu GRUD de academia que requer esses números._

**1b. Lacunas — o que não sei e preciso descobrir (mínimo 3, com precisão técnica):**
1. _Quero saber, como armazenar e gerenciar vários exercícios, em vez de apenas um._
2. _Como localizar corretamente um exercício para atualizar ou excluir seus dados._
3. _Como organizar o código da melhor forma pra poder evitar repetições de comandos._

**1c. Hipótese inicial em até 5 linhas — com lógica da área de formação:**

> _O meu CRUD tem como foco, ajudar a gerenciar os exercícios do usuário, facilitanto na hora de treinar, contendo no GRUD dados como: Cadastrar, Listar, Atualizar, Excluir e Sair. Foi utilizado vários recursos até o momento, como Variáveis, tipos de dados, estruturas condicionais e de repetição, operadores relacionais entre outros recursos aprendidos em sala, meu objetivo no GRUD é criar um sistema que permita cadastrar exercícios, consultar as informações também, e aplicar os conhecimentos de lógica de programação e Python na construção de uma solução prática._

### 🧩 CAMPO 02 — Aprofundamento pós-aula
*AV Qualis — Grupo 1 | Segunda 16/11, 23h59*

> **Preenchido depois do Campo 01, com pesquisa real. Deve ser coerente com o Campo 01. Incoerência = evidência de autoria externa.**

**2a. Aprofundamento dos objetos de conhecimento (mínimo 2 referências com síntese da contribuição para a solução):**

- **Referência 1:** _https://youtu.be/K10u3XIf1-Q?is=ClqBLAJYNEjPBtFC_ — **Contribuição:** _Assisti alguns videos no Youtube sobre estruturas condicionais, laços de repetição etc... isso me ajudou a vizualizar melhor a aplicação dos conceitos na prática, principalmente na utilização das estruturas como "while, if, elif e else", que são importantes pra controlar o menu e as operações do HEVY._
- **Referência 2:** _Explicações do professor e anotações realizadas em sala de aula_ — **Contribuição:** _As aulas ajudaram a compreender a lógica de programação, a utilização de variáveis, os tipos de dados, os operadores e as estruturas condicionais. Esses conhecimentos me ajudaram a entender como organizar o meu CRUD._

**2b. Hipótese revisada — o que mudou em relação ao Campo 01 e por quê:**

> _Depois das pesquisas e dos conteúdos trabalhados em sala de aula, consegui compreender melhor os problemas em que um sistema CRUD pode ocorrer, como falhas na entrada de dados, na lógica de programação e na manipulação das informações. Minha visão inicial ficou mais clara, depois que vi videos e percebi a importância de utilizar corretamente as variáveis, tipos de dados e as estruturas condicionais pra poder evitar erros no sistema do meu CRUD. Em relação ao meu HEVY, entendi que é necessário garantir que as informações dos exercícios sejam armazenadas e manipuladas corretamente._

**2c. Dimensionamento inicial de recursos (recurso, quantidade estimada, justificativa técnica — mínimo 3 itens):**

| RECURSO / MATERIAL / INSUMO | QUANTIDADE ESTIMADA | JUSTIFICATIVA TÉCNICA |
|---|---|---|
| _Tempo de estudo de Python_ | _3 horas_ | _Revisar variáveis, tipos de dados, estruturas condicionais e laços de repetição para melhorar a lógica do CRUD HEVY._ |
| _Casos de teste do sistema_ | _10 testes_ | _Verificar o funcionamento das operações de cadastro, listagem, atualização e exclusão, identificando possíveis falhas._ |
| _Registros de exercícios para teste_ | _5 registros_ | _Utilizar diferentes exercícios e informações para verificar se o sistema consegue armazenar, consultar e manipular os dados corretamente._ |
| _…_ | _…_ | _…_ |

#### Registro do Ciclo 02 — 19/08
1. **Desafio do ciclo (em 1 frase):** _Compreender como armazenar, receber e apresentar informações utilizando variáveis e diferentes tipos de dados em Python._
2. **O que implementei (commits / arquivos / links):** _Comecei a estruturar o HEVY utilizando variáveis para representar as informações dos exercícios, como nome, grupo muscular, séries, repetições e carga. Também trabalhei com entradas e saídas de dados para permitir a interação do usuário com o sistema._
3. **Objeto(s) de conhecimento mobilizado(s):** _Variáveis, tipos de dados (str, int e float), atribuição de valores, entrada de dados com input() e saída de informações com print()._
4. **Desvio ou erro encontrado + causa técnica:** _Uma dificuldade foi compreender a diferença entre os tipos de dados e a necessidade de converter algumas entradas do usuário, já que o comando input() recebe os valores inicialmente como texto._
5. **Decisão de ajuste + fonte:** _Procurei compreender melhor os tipos de dados, utilizando as explicações das aulas e os materias de estudo para organizar corretamente as informações do sistema._
6. **Feedback recebido e o que mudei:** _Os conteúdos trabalhados em sala ajudaram a entender melhor como as variáveis armazenam informações e como os tipos de dados influenciam o funcionamento do programa._
7. **Próximo passo:** _Aplicar os conhecimentos de variáveis e tipos de dados junto às estruturas de repetição e condicionais pra poder desenvolver as funcionaliades do CRUD._

## 🟢 CICLO 03 — 26/08 — Operadores, fluxogramas e paradigmas

<details>
<summary>📘 Orientações do Ciclo 03 — Registro (Grupo 1)</summary>

- Neste grupo você preenche **apenas o Registro do Ciclo 03**. O **Checkpoint Conceitual** e os **Campos 03 e 04** deste ciclo estão no **Grupo 2**.
- Item 3: nomeie os **operadores** (aritméticos, relacionais, lógicos) e os **tipos** que usou. Se montou fluxogramas, cite o que o fluxograma ajudou a perceber.
- Item 4: registre erros de precedência de operadores, divisão por zero ou confusão entre `=` e `==`, com a causa técnica.
</details>

#### Registro do Ciclo 03 — 26/08
1. **Desafio do ciclo (em 1 frase):** _Aprender a utilizar os operadores e entender melhor como organizar a lógica de um programa, para conseguir desenvolver o HEVY de maneira mais organizada._
2. **O que implementei (commits / arquivos / links):** _Continuei trabalhando na lógica do HEVY, utilizando os conhecimentos de programação para organizar as opções do menu e entender como o sistema deve funcionar de acordo com cada escolha do usuário.
_
3. **Objeto(s) de conhecimento mobilizado(s):** _Operadores aritméticos, relacionais e lógicos, expressões booleanas, fluxogramas e lógica de programação._
4. **Desvio ou erro encontrado + causa técnica:** _Tive um pouco de dificuldade para entender como os operadores funcionam juntos dentro de uma condição._
5. **Decisão de ajuste + fonte:** _Procurei revisar os conteúdos apresentados em sala de aula e também ver videoaulas no YouTube pra entender melhor os exemplos práticos de operadores e fluxogramas. Isso me ajudou a visualizar melhor a lógica antes de aplicar no projeto._
6. **Feedback recebido e o que mudei:** _As explicações do professor e os exemplos apresentados durante as aulas ajudaram no meu aprendizado. Também as videoaulas do YouTube me ajudou a entender os assuntos e esclarecer algumas dúvidas._
7. **Próximo passo:** _Continuar desenvolvendo o HEVY e aplicar os conhecimentos de lógica e condições para fazer com que cada opção do menu funcione corretamente._

## 🟢 CICLO 04 — 02/09 — Estruturas condicionais: `if`, `elif`, `else`

<details>
<summary>📘 Orientações do Ciclo 04</summary>

- **Sem Campo do Protocolo hoje.** Preencha o Registro do Ciclo 04.
- Conecte **cada condicional** do seu CRUD a uma **regra de negócio** (ex.: "preço não pode ser negativo").
- Se já recebeu o lote de dados com defeito, procure **qual registro quebra qual condição** e registre o item 4 com a **causa técnica** (ex.: valor `None`, texto vazio, número negativo, divisão por zero).
- No item 5, cite a fonte da decisão: livro (*Pense em Python*), documentação ou exercício que você resolveu.
- Compare com o **Campo 02**: o desvio de hoje já estava previsto no seu dimensionamento?
</details>

#### Registro do Ciclo 04 — 02/09
1. **Desafio do ciclo (em 1 frase):** _Entender como utilizar as estruturas condicionais para fazer o programa tomar decisões e executar diferentes ações dependendo da opção escolhida pelo usuário.
_
2. **O que implementei (commits / arquivos / links):** _Trabalhei na organização do menu do HEVY, utilizando as condições para direcionar o funcionamento do sistema. A ideia é que, ao escolher uma opção, como cadastrar, listar, atualizar ou excluir, o programa execute a ação correspondente._
3. **Objeto(s) de conhecimento mobilizado(s):** _Estruturas condicionais if, elif e else, operadores relacionais, expressões booleanas e controle de fluxo._
4. **Desvio ou erro encontrado + causa técnica:** _
Minha principal dificuldade foi compreender melhor como organizar as condições para que cada opção do menu fosse reconhecida corretamente. Também precisei prestar atenção na lógica das comparações para evitar que o programa executasse uma ação diferente da escolhida._
5. **Decisão de ajuste + fonte:** _
Revisei os exemplos trabalhados em sala de aula e procurei assistir a videoaulas no YouTube sobre estruturas condicionais em Python._
6. **Feedback recebido e o que mudei:** _As explicações dadas em sala foram importantes para entender como as estruturas condicionais funcionam. Também utilizei videoaulas como material complementar.
_
7. **Próximo passo:** _Continuar aprimorando o HEVY, testar as opções do menu e verificar se as operações de cadastro, listagem, atualização e exclusão estão funcionando como esperado_

---

# 🟠 GRUPO 2 — prazo sábado 21/11 às 23h59

> **Janela:** segunda 16/11 → sábado 21/11. **O que entregar:** Registros dos Ciclos 05, 06, 07 e 08 · Checkpoint Conceitual · Campo 03 · Campo 04.
>
> ⚠️ O prazo cai num **sábado**: planeje terminar na sexta. Os campos do Ciclo 03 (Checkpoint, 03 e 04) aparecem **primeiro**, porque são a base da investigação.

**Checklist do Grupo 2**
- [ ] Checkpoint Conceitual feito conforme orientação do professor (20 min, sem consulta)
- [✅] Campo 03: 2 achados com objeto, 1 desvio com causa técnica, 1 decisão com fonte
- [✅] Campo 04: ferramenta, pergunta íntegra, resumo, o que aceitei e o que questionei
- [✅] Registros dos Ciclos 05, 06, 07 e 08 com os 7 itens (devolutiva da P1 no ciclo 06)
- [✅] Commits no GitHub e painel atualizado

## 🟠 CICLO 03 (campos) — 26/08 — Checkpoint, Campo 03 e Campo 04

<details>
<summary>📘 Orientações — Checkpoint, Campo 03 e Campo 04 (referentes ao Ciclo 03)</summary>

**Checkpoint Conceitual** · *20 min · sem consulta · conforme orientação do professor*
- Verifica o **seu domínio individual** do conteúdo — não avalia a sua solução. São **3 questões dissertativas**. Quem investiu por conta própria responde com segurança.
- Respostas **genéricas, sem ancoragem técnica, não são aceitas**. Defina o objeto **e** relacione-o ao problema do seu CRUD, explicitando as implicações.
- Critérios: *precisão conceitual*, *relação conteúdo-problema*, *qualidade do raciocínio*.
- Se for insatisfatório, você recebe **feedback escrito em até 48h** e deve ajustar a investigação antes da avaliação somativa.
- Se o professor aplicar o Checkpoint via GitHub, use o arquivo abaixo **só durante os 20 minutos**, com um único commit ao final.

**Campo 03 — Execução e desvios** · *sábado 21/11, 23h59*
- **3a.** Pelo menos **2 achados** que mudaram sua compreensão do problema, cada um com o **objeto de conhecimento** associado.
- **3b.** Pelo menos **1 desvio** em relação ao Campo 02 (o que você planejou e não aconteceu) e a **causa técnica** — não vale "falta de tempo".
- **3c.** Pelo menos **1 decisão de ajuste**, com justificativa e **fonte**, e o objeto de conhecimento mobilizado.

**Campo 04 — Interação com IA** · *sábado 21/11, 23h59 · obrigatório e avaliado*
- Registre **pelo menos uma** interação real com uma IA sobre o seu CRUD.
- **4b.** Transcreva a pergunta **na íntegra** (copie e cole).
- **4c.** Resuma a resposta em **um parágrafo** com as suas palavras.
- **4d.** O que você **aceitou**, ligando ao objeto de conhecimento.
- **4e.** O que você **questionou ou descartou**, com **argumento técnico ou fonte** (teste, documentação, livro). Dica: **rode o código** que a IA sugeriu antes de decidir.
- **Print sem análise crítica = devolução imediata.** Se você aceitou tudo, volte e procure o que verificar.
</details>

### 🧩 CHECKPOINT CONCEITUAL INDIVIDUAL
*20 minutos · sem consulta a qualquer fonte, material ou colega · conforme orientação do professor.*

| | |
|---|---|
| **Nome do estudante** | _…_ |
| **Data de realização** | _…_ |
| **Unidade curricular** | Algoritmos e Programação |
| **Professor(a)** | Rondineli Seba Salomão |

> **INSTRUÇÕES:** Responda individualmente, sem consulta. Você tem 20 minutos. As questões avaliam seu domínio dos objetos de conhecimento do componente — não sua solução para o problema. Respostas genéricas sem ancoragem técnica não são aceitas.

**QUESTÃO 1** — Objeto de conhecimento: _…_
> _(Questão elaborada pelo professor na Proposta — Apêndice A, item 6)_

**RESPOSTA:**

> _…_

**QUESTÃO 2** — Objeto de conhecimento: _…_
> _(Questão elaborada pelo professor na Proposta — Apêndice A, item 6)_

**RESPOSTA:**

> _…_

**QUESTÃO 3** — Objeto de conhecimento: _…_
> _(Questão elaborada pelo professor na Proposta — Apêndice A, item 6)_

**RESPOSTA:**

> _…_

<details>
<summary>🔒 Uso do professor — critérios de avaliação do Checkpoint</summary>

| CRITÉRIO | SATISFATÓRIO | INSATISFATÓRIO |
|---|---|---|
| **Precisão conceitual** | Domínio do objeto de conhecimento, com vocabulário técnico adequado e sem erros conceituais relevantes. | Resposta vaga, com erros conceituais ou sem ancoragem nos objetos de conhecimento do componente. |
| **Relação conteúdo-problema** | Conecta o objeto de conhecimento ao problema trabalhado na AFP. | Responde o objeto de forma isolada, sem relação com o problema do ciclo. |
| **Qualidade do raciocínio** | Raciocínio técnico articulado: relaciona o objeto ao problema e explicita implicações para a investigação. | Apenas define o objeto, sem articular raciocínio ou relação com o problema investigado. |

**RESULTADO:** ☐ Satisfatório ☐ Insatisfatório
**AÇÃO DO PROFESSOR:** Checkpoint insatisfatório gera feedback escrito individualizado até 48h — o aluno ajusta a investigação antes da avaliação somativa.
</details>

### 🧩 CAMPO 03 — Execução e desvios
*AV Qualis — Grupo 2 | Sábado 21/11, 23h59*

**3a. O que descobri que mudou minha compreensão do problema (mínimo 2 achados, com objeto de conhecimento associado):**
1.  — *Achado: Percebi que a validação dos dados é essencial para evitar que informações incorretas sejam armazenadas. Por exemplo, a quantidade de séries e repetições precisa ser um número inteiro positivo, enquanto a carga não pode ser negativa.
Objeto de conhecimento: Tipos de dados, validação de entrada e estruturas condicionais.--* _…_
2.  — *Achado: Compreendi que a escolha da estrutura de dados influencia diretamente a capacidade do sistema. Utilizar variáveis individuais permite armazenar um exercício, mas listas e dicionários seriam mais adequados para organizar vários exercícios.
Objeto de conhecimento: Estruturas de dados, listas e dicionários.* _…_
3. _…_ *(opcional)*

**3b. Desvio em relação ao Campo 02 (ao menos 1 — causa técnica):**
- **Desvio:** _Durante o desenvolvimento, percebi que a estrutura atual do HEVY não permite trabalhar com vários exercícios ao mesmo tempo, mesmo que essa seja uma possibilidade de evolução planejada._
- **Causa técnica:** _O sistema foi construído utilizando variáveis individuais para armazenar os dados de um único exercício. Para armazenar vários registros, seria necessário utilizar estruturas de dados, como listas e dicionários._

**3c. Decisão de ajuste (ao menos 1) com justificativa e fonte:**
- **Decisão:** _Manter a organização atual das operações de cadastro, listagem, atualização e exclusão, reforçando as validações das informações inseridas pelo usuário. Também identifiquei a utilização de listas e dicionários como uma melhoria futura para permitir o armazenamento de vários exercícios._
- **Fonte:** _Conteúdos trabalhados nas aulas de Algoritmos e Programação, exercícios práticos e alguns videos aula no Youtube._

**Objeto de conhecimento mobilizado nesta decisão:**  Variáveis, tipos de dados, estruturas condicionais, validação de entrada e estruturas de dados._

### 🧩 CAMPO 04 — Interação com IA
*AV Qualis — Grupo 2 | Sábado 21/11, 23h59 | OBRIGATÓRIO*

> **Obrigatório e avaliado. Print sem análise crítica = devolução imediata. Reproduzir a IA sem questionamento = reprovado.**

**4a. Ferramenta:** _…ChatGPT e Gemini_  **Data:** _20/11/2026_

**4b. Pergunta formulada (transcrita integralmente):**

> _Estou desenvolvendo um sistema chamado HEVY em Python para gerenciar exercícios físicos. O sistema possui as opções de cadastrar, listar, atualizar e excluir exercícios, utilizando variáveis para armazenar nome, grupo muscular, séries, repetições e carga. Também utilizo input(), print(), while, if, elif e else. Gostaria que você analisasse essa estrutura e explicasse quais possíveis limitações existem no meu código, principalmente em relação à validação dos dados, ao armazenamento das informações e à possibilidade de cadastrar vários exercícios. Quais melhorias seriam adequadas considerando os conteúdos de lógica de programação que estou estudando?_

**4c. Resposta da IA (resumida em parágrafo):**

> _A análise mostrou que o HEVY utiliza corretamente conceitos importantes de lógica de programação, como variáveis, tipos de dados, estruturas condicionais e laços de repetição. Entretanto, a utilização de variáveis individuais limita o sistema ao armazenamento de um exercício por vez. Para permitir vários cadastros, seria interessante utilizar listas e dicionários. Também foi destacada a importância da validação das entradas, evitando valores incorretos, como séries e repetições negativas ou carga abaixo de zero. Outra limitação é que os dados não ficam salvos permanentemente após o encerramento do programa._

**4d. O que aceitei — com referência ao objeto de conhecimento do componente:**

> _Aceitei a análise sobre a importância da validação das informações e sobre as limitações do armazenamento por meio de variáveis individuais. Compreendi que listas e dicionários poderiam melhorar a organização dos exercícios, permitindo vários registros. Essa orientação está relacionada aos objetos de conhecimento de estruturas de dados, tipos de dados, estruturas condicionais e validação de entrada. Considero essas melhorias importantes para uma futura evolução do HEVY._

**4e. O que questionei ou descartei — com argumento técnico ou fonte:**

> _Questionei a possibilidade de considerar listas e dicionários como recursos já implementados no meu sistema. Apesar de serem melhorias recomendadas, meu código atual ainda utiliza variáveis individuais e não possui essas estruturas. Por isso, não registrei esses recursos como funcionalidades existentes. Também considerei que implementar um banco de dados seria um avanço maior, que exigiria novos conhecimentos. Durante a apresentação do projeto, consegui explicar sua proposta e suas principais funcionalidades, mas senti um pouco de nervosismo, o que dificultou minha apresentação em alguns momentos. Considero a experiência positiva, pois consegui apresentar o que desenvolvi e identificar pontos que posso melhorar "como no erro do slide" e na minha comunicação._

## 🟠 CICLO 05 — 09/09 — Condicionais aninhadas e operadores lógicos

<details>
<summary>📘 Orientações do Ciclo 05</summary>

- **Sem Campo do Protocolo hoje.** Preencha o Registro do Ciclo 05.
- Registre **qual combinação de condições** (`and`, `or`, `not`) você precisou e **por que** uma condicional aninhada ou um operador lógico foi a melhor escolha.
- Descreva **pelo menos um caso de teste** que você usou para provar a lógica (entrada → resultado esperado → resultado obtido).
- **Atenção à P1 (23/09):** reveja o Logbook até aqui. Complete itens em branco e confirme se os commits estão em dia.
- Na semana de 16/09 (Nivelamento / Peer Instruction), reserve 10 minutos para atualizar este arquivo.
</details>

#### Registro do Ciclo 05 — 09/09
1. **Desafio do ciclo (em 1 frase):** _Compreender como utilizar condicionais aninhadas e operadores lógicos para validar informações e controlar as opções do sistema HEVY._
2. **O que implementei (commits / arquivos / links):** _Trabalhei na lógica do sistema, utilizando estruturas condicionais para verificar as informações digitadas pelo usuário e identificar a opção escolhida no menu._
3. **Objeto(s) de conhecimento mobilizado(s):** _Estruturas condicionais aninhadas, operadores lógicos (or), operadores relacionais e expressões booleanas._
4. **Desvio ou erro encontrado + causa técnica:** _Uma dificuldade foi compreender como combinar mais de uma condição sem deixar a lógica confusa. Isso exige atenção à ordem das verificações e aos resultados das expressões booleanas._
5. **Decisão de ajuste + fonte:** _Organizei as verificações por etapas, utilizando condições específicas para cada situação. Usei como apoio as explicações das aulas e exercícios de lógica de programação._
6. **Feedback recebido e o que mudei:** _As atividades ajudaram a compreender melhor a importância de organizar as condições antes de executar uma ação. Percebi que precisava ter mais atenção à lógica de cada verificação._
7. **Próximo passo:** _Aprofundar o uso de estruturas condicionais e começar a trabalhar com laços de repetição._

## 🟠 CICLO 06 — 30/09 — Devolutiva da P1 + repetição: `for`, `while`, `break`, `continue`

<details>
<summary>📘 Orientações do Ciclo 06</summary>

- **Sem Campo do Protocolo hoje.** Preencha o Registro do Ciclo 06.
- Use o item 6 para registrar a **devolutiva da P1**: o que errou e **qual conceito** estava faltando. Esses erros alimentam o **Campo 07c** (conceitos corrigidos). *Anote já, para não esquecer.*
- Registre **por que escolheu `for` ou `while`** em cada laço do seu CRUD (cadastro em lote, listagem, menu).
- Item 4: se um laço ficou infinito ou pulou itens, descreva a **causa técnica** (condição de parada, incremento, `break` fora de lugar).
</details>

#### Registro do Ciclo 06 — 30/09
1. **Desafio do ciclo (em 1 frase):** _Entender como os laços de repetição funcionam e como podem ser utilizados para manter o menu do HEVY em funcionamento._
2. **O que implementei (commits / arquivos / links):** _Utilizei o laço while para permitir que o menu principal continue aparecendo enquanto o usuário não escolher a opção de sair._
3. **Objeto(s) de conhecimento mobilizado(s):** _Laços de repetição, principalmente while, condições de parada, estruturas condicionais e controle de fluxo._
4. **Desvio ou erro encontrado + causa técnica:** _Uma dificuldade foi compreender a importância da condição de parada do laço. Caso ela não seja atualizada corretamente, o programa pode continuar repetindo o menu sem parar._
5. **Decisão de ajuste + fonte:** _Utilizei a opção escolhida pelo usuário como condição de controle do while, fazendo com que a repetição termine quando a opção de saída for selecionada. Usei como referência as explicações das aulas e os exercícios de programação._
6. **Feedback recebido (inclui devolutiva da P1) e o que mudei:** _devolutiva da P1 e os estudos do conteúdo reforçaram a importância de compreender a lógica por trás do código, e não apenas copiar comandos. Percebi que precisava revisar melhor as condições e a organização das estruturas de repetição._
7. **Próximo passo:** _Estudar listas e entender como armazenar mais de um registro no sistema._

## 🟠 CICLO 07 — 07/10 — Listas: armazenamento e iteração

<details>
<summary>📘 Orientações do Ciclo 07</summary>

- **Sem Campo do Protocolo hoje.** Preencha o Registro do Ciclo 07.
- Justifique **por que seus dados cabem em uma lista** e como você os percorre (iteração).
- Item 4: erros típicos — índice fora do intervalo, alterar a lista enquanto percorre, confundir cópia com referência. Registre qual deles aconteceu e a causa técnica.
- Item 3: nomeie as **operações de lista** que usou (adicionar, remover, ordenar, fatiar…).
</details>

#### Registro do Ciclo 07 — 07/10
1. **Desafio do ciclo (em 1 frase):** _Compreender como as listas podem ser utilizadas para armazenar vários registros e facilitar a organização das informações._
2. **O que implementei (commits / arquivos / links):** _Estudei o funcionamento das listas e suas possibilidades de utilização em sistemas que precisam armazenar vários dados. No HEVY atual, ainda utilizo variáveis individuais para guardar as informações de um exercício._
3. **Objeto(s) de conhecimento mobilizado(s):** _Listas, índices, elementos, armazenamento de dados, iteração e operações de inclusão e remoção._
4. **Desvio ou erro encontrado + causa técnica:** _Identifiquei que a estrutura atual do HEVY possui uma limitação: ela não permite armazenar vários exercícios simultaneamente. Isso acontece porque os dados são guardados em variáveis individuais, e não em uma estrutura de dados como uma lista._
5. **Decisão de ajuste + fonte:** _Considerei que a utilização de listas seria uma evolução adequada para o projeto, pois permitiria armazenar vários exercícios e percorrer seus registros. Utilizei como apoio o conteúdo apresentado em aula e os exercícios sobre listas._
6. **Feedback recebido e o que mudei:** _O conteúdo ajudou a perceber que a escolha da estrutura de dados influencia diretamente as possibilidades de um sistema. Passei a compreender melhor a diferença entre guardar apenas um registro e organizar vários registros._
7. **Próximo passo:** _Estudar como organizar os dados utilizando dicionários e como realizar buscas por informações específicas._

## 🟠 CICLO 08 — 14/10 — Busca/consulta e introdução a dicionários e matrizes

<details>
<summary>📘 Orientações do Ciclo 08</summary>

- **Sem Campo do Protocolo hoje.** Preencha o Registro do Ciclo 08.
- Explique **por que cada item do seu catálogo virou um dicionário** (chave → valor) em vez de uma lista de valores soltos.
- Item 4: registre **qual busca falhou** (item inexistente, tipo diferente — `"2"` ≠ `2`, chave com maiúscula errada) e a causa técnica.
- Se usou o lote de dados defeituoso, registre **qual registro** quebrou a busca.
- Item 5: cite a fonte (*Pense em Python*, cap. 11, ou outra).
</details>

#### Registro do Ciclo 08 — 14/10
1. **Desafio do ciclo (em 1 frase):** _Compreender como realizar buscas e organizar informações utilizando estruturas como dicionários e matrizes._
2. **O que implementei (commits / arquivos / links):** _Estudei como os dicionários organizam informações por meio de pares de chave e valor. No HEVY atual, os dados ainda são armazenados em variáveis individuais, mas compreendi como os dicionários poderiam organizar os dados de cada exercício._
3. **Objeto(s) de conhecimento mobilizado(s):** _Busca de dados, dicionários, pares chave-valor, estruturas de dados e matrizes._
4. **Desvio ou erro encontrado + causa técnica:** _Uma limitação identificada foi a ausência de uma estrutura que permita pesquisar diferentes exercícios pelo nome ou por outras informações. Isso ocorre porque o sistema ainda trabalha com apenas um conjunto de variáveis._
5. **Decisão de ajuste + fonte:** _Identifiquei que os dicionários poderiam representar cada exercício, associando informações como nome, grupo muscular, séries, repetições e carga. As listas poderiam armazenar vários desses registros. Usei como referência as explicações das aulas e os estudos sobre estruturas de dados._
6. **Feedback recebido e o que mudei:** _Consegui compreender melhor como diferentes estruturas de dados podem facilitar a organização e a consulta de informações. Também percebi que o projeto pode evoluir bastante com a utilização desses recursos._
7. **Próximo passo:** _Revisar os conteúdos de estruturas de dados e compreender como aplicá-los em uma futura evolução do HEVY._

---

# 🔵 GRUPO 3 — prazo quinta 26/11 às 23h59

> **Janela:** sábado 21/11 → quinta 26/11. **O que entregar:** Registros dos Ciclos 09, 10, 11 e 12 · Campo 05 (duas revisões por pares) · Campo 06 · Campo 07.
>
> ⚠️ O prazo vem **um dia depois da P2 (25/11)**. Os Campos 06 e 07 dependem de todo o Logbook: deixe-os para o final, mas **adiante o rascunho do 6c e do 7a/7b antes da Defesa (18/11)**.

**Checklist do Grupo 3**
- [✅] Registros dos Ciclos 09, 10, 11 e 12 com os 7 itens
- [✅] Campo 05: duas revisões (Ciclos 09 e 12), blocos 5a a 5e
- [✅] Campo 06: decisão autônoma, lacuna com plano, pergunta da banca com 5 linhas ou mais
- [✅] Campo 07: 7a a 7e, com 3 objetos, 2 equívocos corrigidos e transferência
- [✅] Coerência entre Campo 01 e Campo 07
- [✅] Painel de acompanhamento completo

## 🔵 CICLO 09 — 21/10 — Atualização e exclusão: CRUD completo

<details>
<summary>📘 Orientações do Ciclo 09 — Registro + Campo 05 (revisão por pares nº 1)</summary>

- Neste ciclo seu CRUD ficou **completo** (Create, Read, Update, Delete). Preencha o Registro do Ciclo 09.
- **Item 4:** *atualizar* ou *excluir* item inexistente, e excluir durante um laço (a lista muda de tamanho e itens são pulados) são erros comuns.
- **Campo 05 — Registro de Revisão por Pares.** Você passa a ser **revisor** do CRUD de um colega.
  - Cada revisão tem **um registro** (copie a seção do Campo 05) com o nome e o link do repositório revisado.
  - **Revise o processo, não só o código:** o que foi decidido, em que objeto de conhecimento se apoia, com que fonte.
  - **5a:** liste as etapas da revisão (ex.: rodar o CRUD, testar com o lote de dados com defeito, ler o código, registrar achados, devolver feedback).
  - **5b:** liste os insumos que usou (lote de dados, casos de teste, `requisitos.md`) com quantidade planejada, utilizada e variação.
  - **5c:** diga se a solução do colega atende ao critério (Sim/Parcialmente/Não) e **qual critério** usou (ex.: requisito do `requisitos.md`).
  - **5d:** riscos da revisão (ex.: não conseguir rodar o código do colega) e como mitigou.
  - **5e:** registre **cada decisão técnica** da revisão com **data, responsável, objeto de conhecimento e fundamentação/referência**. *Sem objeto e sem referência, não é rastreável.*
  - Feedback ao colega: **específico e respeitoso** (o que está bom, o que quebrou, como reproduzir, sugestão).
</details>

#### Registro do Ciclo 09 — 21/10
1. **Desafio do ciclo (em 1 frase):** _Compreender melhor como funcionam as operações de atualização e exclusão de dados e como elas se relacionam com as demais operações do CRUD._
2. **O que implementei (commits / arquivos / links):** _Trabalhei na lógica das operações do HEVY, principalmente na atualização das informações de um exercício já cadastrado e na exclusão dos dados. O sistema utiliza a variável cadastrado para verificar se existe um exercício registrado antes de permitir determinadas operações._
3. **Objeto(s) de conhecimento mobilizado(s):** _Operações CRUD (Create, Read, Update e Delete), estruturas condicionais, variáveis, tipos de dados e validação de informações._
4. **Desvio ou erro encontrado + causa técnica:** _Uma dificuldade foi compreender como impedir que o usuário tente atualizar ou excluir um exercício que ainda não foi cadastrado. Isso poderia causar inconsistências na lógica do programa caso não houvesse uma verificação anterior._
5. **Decisão de ajuste + fonte:** _Utilizei uma variável booleana chamada cadastrado para controlar a existência de um registro. Dessa forma, o programa consegue verificar se deve permitir a atualização ou exclusão. Como referência, utilizei as explicações das aulas e a documentação oficial do Python sobre estruturas condicionais._
6. **Feedback recebido e o que mudei:** _As atividades ajudaram a compreender que cada operação do CRUD precisa ter uma condição adequada para funcionar corretamente. Passei a prestar mais atenção na sequência das verificações e na situação dos dados antes de executar uma operação._
7. **Próximo passo:** _Estudar como organizar melhor o código utilizando funções e compreender como separar as responsabilidades de cada operação do sistema._

### 🧩 CAMPO 05 — Registro de Revisão por Pares
*Adaptação do **Logbook do Time** (Apêndice C) para o CRUD individual. Documento atualizado pelo **revisor**. Cada decisão técnica relevante deve ter associado o objeto de conhecimento correspondente.*

> ⚠️ **Nota de adaptação:** o Apêndice C original prevê Gestor, Responsável Técnico, Analista de Qualidade e Comunicador. Como o CRUD é **individual** e os alunos atuam como **revisores**, mantive os blocos 5a a 5e e troquei os papéis por **Autor** (dono do CRUD) e **Revisor** (você). *Pendente de validação do professor/NDE.*

> **O Logbook de revisão é um registro de conhecimento em ação.** Cada decisão técnica relevante deve estar associada ao objeto de conhecimento que a fundamenta, à justificativa técnica e à referência utilizada. Registros sem esse vínculo não são aceitos.

#### Revisão nº 1

| | |
|---|---|
| **Autor do CRUD revisado** | _Filipe Gabriel Silva Melo Pereira_ |
| **Repositório revisado** | _https://github.com/filipegabrielsilvamp/atividade-eng-software_ |
| **Revisor** | _Gustavo de Jesus Magalhães Farias_ |
| **Unidade curricular / Semestre** | Algoritmos e Programação · 2026.2 |
| **Ciclo / data** | _Ciclo 09 · 21/10_ |

**5a. AVANÇO DO PROCESSO DE REVISÃO — análise técnica de cada etapa:**

| ETAPA DO PROCESSO | RESPONSÁVEL | PRAZO | STATUS | DESVIO / JUSTIFICATIVA |
|---|---|---|---|---|
| 1. _Analisar o código-fonte_ | Revisor | _21/11_ | ☐ Concluída  | _Código analisado pelo GitHub_ |
| 2. _Verificar cadastro e listagem_ | Revisor | _21/11_ | ☐ Concluída  | _Identificadas lista e funções_ |
| 3. _Verificar atualização e exclusão_ | Revisor | _21/11_ | ☐ Concluída  | _Operações presentes no código_ |
| 4. _Conferir validações_ | Revisor | _21/11_ | ☐ Concluída  | _Regras de negócio identificadas_ |
| 5. _Registrar feedback_ | Revisor | _21/11_ | ☐ Concluída  | _Pontos positivos e melhoria identificados_ |

**5b. ANÁLISE DE INSUMOS E CRITÉRIOS DE QUALIDADE:**

| RECURSO | QTDE PLANEJADA | QTDE UTILIZADA | VARIAÇÃO | JUSTIFICATIVA TÉCNICA |
|---|---|---|---|---|
| _Código-fonte_ | _1_ | _1_ | _0_ | _Análise do programa_ |
| _Casos de teste_ | _5_ | _0_ | _-5_ | _Não foram executados_ |
| _Requisitos do projeto_ | _1_ | _1_ | _0_ | _Comparação das funcionalidades_ |

**5c. CONTROLE DE QUALIDADE:**
- **Critério ou norma técnica:** _funcionamento das quatro operações CRUD e validação dos dados._
- **A solução atende?** ☐ Parcialmente

**5d. GESTÃO DE RISCOS:**
- **Risco:** _entradas não numéricas em campos convertidos para int ou float podem gerar erros._
- **Estratégia de mitigação:** _recomendar tratamento de exceções e testes com entradas inválidas._

**5e. RASTREABILIDADE DAS DECISÕES TÉCNICAS — COM VÍNCULO AO CONTEÚDO:**

| DATA | DECISÃO TÉCNICA | RESP. | OBJETO DE CONHECIMENTO MOBILIZADO | FUNDAMENTAÇÃO / REFERÊNCIA |
|---|---|---|---|---|
| _21/11/26_ | _Verificar o uso de listas_ | _Revisor_ | _Listas_ | _Código tarefas_ |
| _21/11/26_ | _Analisar a organização dos registros_ | _Revisor_ | _Dicionarios_ | _Dados organizados por chaves_ |
| _21/11/26_ | _Conferir as operações_ | _Revisor_ | _CRUD e funções_ | _cadastrar, listar, atualizar, remover_ |
| _21/11/26_ | _Avaliar as validações_ | _Revisor_ | _Condicionais_ | _Regras de negócio_ |
| _21/11/26_ | _Identificar riscos nas entradas_ | _Revisor_ | _Tipos de dados_ | _Conversões int e float_ |

> **IMPORTANTE:** Decisão registrada sem objeto de conhecimento associado e sem referência é considerada **não rastreável** e não conta para a avaliação formativa. O vínculo entre processo e conteúdo é obrigatório em todas as decisões relevantes.

## 🔵 CICLO 10 — 28/10 — Modularização: funções

<details>
<summary>📘 Orientações do Ciclo 10</summary>

- **Sem Campo do Protocolo hoje.** Preencha o Registro do Ciclo 10.
- Explique **como dividiu** o CRUD em funções (`cadastrar()`, `buscar()`, `alterar()`, `excluir()`, `listar()`, `menu()`) e **por que** cada função tem aquela responsabilidade.
- Item 4: erros típicos — variável fora de escopo, função sem `return`, parâmetro na ordem errada.
- Compare o código **antes e depois** da refatoração: o que ficou mais claro? Registre no item 6 o feedback do colega que fez a *peer review*.
</details>

#### Registro do Ciclo 10 — 28/10
1. **Desafio do ciclo (em 1 frase):** _Compreender como a modularização pode facilitar a organização e a manutenção de um programa._
2. **O que implementei (commits / arquivos / links):** _Estudei como dividir um programa em funções menores, como cadastrar(), listar(), atualizar() e excluir(). No HEVY atual, as operações ainda estão organizadas diretamente no fluxo principal do programa, mas compreendi como a separação em funções poderia deixar o código mais organizado._
3. **Objeto(s) de conhecimento mobilizado(s):** _Funções, parâmetros, argumentos, retorno de valores (return) e escopo de variáveis._
4. **Desvio ou erro encontrado + causa técnica:** _Uma dificuldade foi compreender como as variáveis utilizadas dentro de uma função podem ter um escopo diferente das variáveis do programa principal. Também percebi que uma função precisa receber os dados necessários ou retornar um resultado quando isso for necessário._
5. **Decisão de ajuste + fonte:** _Identifiquei que separar as operações do HEVY em funções seria uma boa melhoria, pois cada função poderia ficar responsável por uma tarefa específica. Essa organização reduziria a repetição de código e facilitaria futuras alterações. Utilizei como referência as explicações das aulas e a documentação oficial do Python sobre definição de funções._
6. **Feedback recebido e o que mudei:** _O estudo desse conteúdo me ajudou a perceber que um código não precisa estar concentrado em um único bloco para funcionar. Passei a valorizar mais a organização e a divisão das responsabilidades, pensando também na facilidade de compreender o programa futuramente._
7. **Próximo passo:** _Aprofundar o uso de funções, principalmente parâmetros, retorno de valores e escopo de variáveis, para conseguir aplicar esses conceitos em uma futura melhoria do HEVY._

## 🔵 CICLO 11 — 04/11 — Recursividade

<details>
<summary>📘 Orientações do Ciclo 11 — Registro + Campo 06 (Grupo 3)</summary>

- Preencha o Registro do Ciclo 11 (caso base, chamada recursiva, pilha de execução).
- **Campo 06 — Próximos passos para a defesa** · *individual · quinta 26/11, 23h59*. Prepare-se para a **Defesa Técnica de quarta 18/11**: como o prazo é posterior à defesa, **adiante pelo menos o 6c** (pergunta da banca e resposta) e leve-o para a arguição.
  - **6a.** Uma **decisão técnica que você defende com plena autonomia**: algo que aprendeu e **é exclusivamente seu**, que nenhum colega consegue explicar por você.
  - **6b.** Uma **lacuna técnica real** e um **plano de ação** com passos e datas para saná-la antes da defesa.
  - **6c.** Uma **pergunta que a banca pode fazer** (nível de Avaliação ou Criação) e a sua **resposta fundamentada em, no mínimo, 5 linhas**, com o objeto de conhecimento e a fonte.
  - Dica: leia a **Rubrica de Defesa Técnica** (no Encerramento) e escolha uma pergunta que teste *aplicação*, *evolução* ou *transferência*.
</details>

#### Registro do Ciclo 11 — 04/11
1. **Desafio do ciclo (em 1 frase):** _Compreender como funciona a recursividade e identificar em quais situações ela pode ser utilizada na programação._
2. **O que implementei (commits / arquivos / links):** _Estudei a lógica da recursividade, observando como uma função pode chamar a si mesma para resolver um problema em etapas menores. Também compreendi a importância de definir uma condição de parada para evitar chamadas infinitas. Esse recurso não foi implementado no HEVY atual._
3. **Objeto(s) de conhecimento mobilizado(s):** _Recursividade, caso base, chamada recursiva e pilha de execução._
4. **Desvio ou erro encontrado + causa técnica:** _Minha principal dificuldade foi compreender como uma função consegue chamar a si mesma e como o programa controla essas chamadas. Sem um caso base adequado, a função pode continuar sendo executada até atingir o limite da pilha de execução._
5. **Decisão de ajuste + fonte:** _Passei a analisar a recursividade separando o problema em duas partes: o caso base, que determina quando a execução termina, e a chamada recursiva, que reduz o problema até alcançar essa condição. Utilizei como apoio as explicações das aulas e a documentação oficial do Python._
6. **Feedback recebido e o que mudei:** _O conteúdo me ajudou a perceber que existem diferentes maneiras de resolver um problema, e que nem toda solução depende apenas de laços de repetição. Também entendi que a recursividade precisa ser utilizada com cuidado, principalmente em relação à condição de parada._
7. **Próximo passo:** _Continuar praticando funções recursivas com exemplos simples e compreender melhor a relação entre chamadas de funções e pilha de execução._

### 🧩 CAMPO 06 — Próximos passos para a defesa
*AV Qualis — Grupo 3 | Individual | Quinta 26/11, 23h59*

**6a. Decisão técnica que defendo com plena autonomia — o que aprendi que é exclusivamente meu e não consigo transferir para nenhum colega:**

> _Uma decisão técnica é no meu projeto HEVY foi utilizar a variável booleana cadastrado para controlar se existe um exercício registrado. Escolhi essa lógica porque, antes de atualizar ou excluir um exercício, o programa precisa verificar se ele realmente foi cadastrado. Quando existe um registro, a variável recebe True; quando ele é excluído, recebe False. Assim, consigo utilizar as estruturas condicionais para controlar melhor as operações e evitar ações desnecessárias. Essa foi uma decisão que compreendi durante o desenvolvimento e consigo explicar utilizando meu próprio código._

**6b. Lacuna técnica e plano de ação para saná-la:**

- **Lacuna:** _Ainda tenho dificuldade em compreender e aplicar algumas estruturas de dados, principalmente listas e dicionários, além de precisar praticar mais a utilização de funções e a recursividade._
- **Plano de ação (passos e datas):** _Etapa	Atividade	Data
1	Revisar listas e dicionários com exemplos práticos	27/11
2	Praticar funções, parâmetros e retorno de valores	28/11
3	Resolver exercícios básicos de recursividade	30/11
4	Revisar os conteúdos e pensar em melhorias para o HEVY	02/12_

**6c. Pergunta que a banca pode fazer — com resposta fundamentada (mínimo 5 linhas):**

- **Pergunta:** _Se você tivesse que evoluir o HEVY para permitir o cadastro de vários exercícios, quais mudanças faria na estrutura atual do programa e por quê?_
- **Resposta:**

> _Atualmente, meu sistema utiliza variáveis individuais para armazenar as informações de um exercício. Para permitir vários cadastros, eu utilizaria uma lista para armazenar diferentes exercícios e dicionários para organizar as informações de cada um. Cada dicionário poderia conter o nome, grupo muscular, séries, repetições e carga. Também utilizaria funções para separar as operações de cadastro, listagem, atualização e exclusão. Dessa forma, o código ficaria mais organizado e seria possível trabalhar com vários registros sem precisar criar novas variáveis para cada exercício. Essa mudança está relacionada aos conteúdos de estruturas de dados e modularização que estudei durante a disciplina._

**Objeto de conhecimento mobilizado:** _Listas, dicionários, funções, modularização e operações CRUD._
**Fonte:** _estruturas de dados e definição de funções do Youtube e aulas em sala._

## 🔵 CICLO 12 — 11/11 — Refatoração e qualidade de código

<details>
<summary>📘 Orientações do Ciclo 12 — Registro + Campo 05 (revisão nº 2) + início do Campo 07</summary>

- Preencha o Registro do Ciclo 12. Registre o que revisou: código duplicado, nomes ruins, funções grandes, comentários desnecessários, lógica confusa.
- **Campo 05 — Revisão por pares nº 2.** Foque em **qualidade**: o CRUD do colega resiste aos casos de teste (mínimos, máximos, inválidos, entradas vazias) e ao **lote de dados com defeito**? Use a seção abaixo (copie o bloco *Revisão nº 1* do Ciclo 09 e preencha novamente).
- **Campo 07 — Evolução conceitual** · *individual · quinta 26/11, 23h59.* Comece agora, enquanto a memória do semestre está fresca; leve o rascunho de 7a e 7b para a Defesa de 18/11. Dicas por item:
  - **7a.** Releia o **Campo 01** e resuma o que você *pensava* e *achava que sabia*. Seja honesto, mesmo se o Campo 01 estiver "errado".
  - **7b.** Pelo menos **3 objetos de conhecimento** na tabela: o que você *não dominava*, o que *aprendeu e consegue demonstrar* e a **evidência** (em qual Campo ou ciclo do Logbook aparece).
  - **7c.** Pelo menos **2 equívocos corrigidos**, dizendo **o que os corrigiu** (Fechamento Teórico, pesquisa, *Peer Review*, arguição, devolutiva da P1).
  - **7d.** **Transferência:** um exemplo concreto de aplicar o que aprendeu em um **contexto diferente** do CRUD (outra área do seu curso ou outro tipo de sistema).
  - **7e.** Avaliação honesta do que **ainda não domina** e vai aprofundar.
</details>

#### Registro do Ciclo 12 — 11/11
1. **Desafio do ciclo (em 1 frase):** _Compreender como melhorar a qualidade do código por meio da refatoração, tornando sua estrutura mais clara, organizada e fácil de manter._
2. **O que implementei (commits / arquivos / links):** _Revisei os conceitos utilizados no HEVY e identifiquei pontos que poderiam ser melhor organizados, como a repetição de trechos de código, a separação das operações e a clareza das condições. Também reconheci que a utilização de funções poderia facilitar a manutenção do sistema._
3. **Objeto(s) de conhecimento mobilizado(s):** _Refatoração, legibilidade de código, modularização, boas práticas de programação e validação de dados._
4. **Desvio ou erro encontrado + causa técnica:** _Percebi que algumas partes do programa possuem estruturas semelhantes, principalmente nas operações de cadastro e atualização. Essa repetição pode dificultar futuras alterações, pois uma mudança em uma regra pode exigir ajustes em mais de um trecho do código._
5. **Decisão de ajuste + fonte:** _Identifiquei a necessidade de melhorar a organização do programa, utilizando nomes claros para as variáveis, condições bem definidas e, futuramente, funções para separar as operações. Considerei os conceitos apresentados nas aulas e as orientações da documentação oficial do Python sobre organização e estilo de código._
6. **Feedback recebido e o que mudei:** _Ao longo dos estudos, percebi que não basta fazer o programa funcionar: também é importante conseguir entender e manter o código. Passei a observar melhor a clareza das instruções, a organização das condições e a possibilidade de evitar repetições desnecessárias._
7. **Próximo passo:** _Continuar evoluindo o HEVY, estudando modularização e estruturas de dados para permitir o armazenamento de vários exercícios e melhorar a organização geral do sistema._

### 🧩 CAMPO 05 — Registro de Revisão por Pares (revisão nº 2)

| | |
|---|---|
| **Autor do CRUD revisado** | _Filipe Gabriel Silva Melo Pereira_ |
| **Repositório revisado** | _https://github.com/filipegabrielsilvamp/atividade-eng-software_ |
| **Revisor** | _	Gustavo de Jesus Magalhães Farias_ |
| **Ciclo / data** | _Ciclo 12 · 11/11_ |

**5a. AVANÇO DO PROCESSO DE REVISÃO:**

| ETAPA DO PROCESSO | RESPONSÁVEL | PRAZO | STATUS | DESVIO / JUSTIFICATIVA |
|---|---|---|---|---|
| 1. _Analisar organização do código_ | Revisor | _26/11_ | ☐ Concluída  | _Código separado em funções_ |
| 2. _Verificar nomes e legibilidade_ | Revisor | _26/11_ | ☐ Concluída  | _Nomes descritivos_ |
| 3. _Conferir validações_ | Revisor | _26/11_ | ☐ Concluída  | _Regras de entrada identificadas_ |
| 4. _Identificar possíveis melhorias_ | Revisor | _26/11_ | ☐ Concluída  | _Tratamento de entradas numéricas_ |
| 5. _Registrar feedback_ | Revisor | _26/11_ | ☐ Concluída  | _	Sugestões de melhoria registradas_ |

**5b. ANÁLISE DE INSUMOS E CRITÉRIOS DE QUALIDADE:**

| RECURSO | QTDE PLANEJADA | QTDE UTILIZADA | VARIAÇÃO | JUSTIFICATIVA TÉCNICA |
|---|---|---|---|---|
| _Código-fonte_ | _1_ | _1_ | _0_ | _Análise da organização_ |
| _Casos de teste_ | _8_ | _0_ | _-8_ | _Não foram executados_ |
| _Critérios de qualidade_ | _1_ | 1_ | _0_ | _Análise de legibilidade e validações_ |

**5c. CONTROLE DE QUALIDADE:**
- **Critério ou norma técnica:** _organização, legibilidade, validação e consistência das operações._
- **A solução atende?** ☐ Parcialmente

**5d. GESTÃO DE RISCOS:**
- **Risco:** _erros durante a conversão de dados digitados pelo usuário._
- **Estratégia de mitigação:** _utilizar tratamento de exceções e testar entradas vazias, inválidas e valores fora dos limites._

**5e. RASTREABILIDADE DAS DECISÕES TÉCNICAS — COM VÍNCULO AO CONTEÚDO:**

| DATA | DECISÃO TÉCNICA | RESP. | OBJETO DE CONHECIMENTO MOBILIZADO | FUNDAMENTAÇÃO / REFERÊNCIA |
|---|---|---|---|---|
| _26/11/26_ | _Avaliar divisão das funcionalidades_ | _Revisor_ | _Modularização_ | _Funções independentes_ |
| _26/11/26_ | _Verificar clareza dos nomes_ | _Revisor_ | _Legibilidade_ | _Boas práticas_ |
| _26/11/26_ | _Conferir validações de entrada_ | _Revisor_ | _Condicionais_ | _Regras de negócio_ |
| _26/11/26_ | _Identificar tratamento de erros_ | _Revisor_ | _Tipos de dados_ | _Conversões numéricas_ |
| _26/11/26_ | _Recomendar melhorias_ | _Revisor_ | _Refatoração_ | _Qualidade do código_ |

### 🧩 CAMPO 07 — Evolução conceitual
*AV Qualis — Grupo 3 | Individual | Quinta 26/11, 23h59*

*Evidência rastreável de aprendizagem entre o início e o encerramento do ciclo AFP.*

**7a. O que eu pensava no início do ciclo (com base no Campo 01 — registrar a hipótese inicial e os objetos de conhecimento que achava conhecer):**

> _No início da disciplina, eu já tinha uma noção básica de lógica de programação e acreditava que conseguiria desenvolver um sistema simples utilizando variáveis, entradas e saídas de dados e algumas condições. Porém, ainda não compreendia completamente como organizar um programa com várias operações e como utilizar estruturas de repetição e armazenamento de dados de forma mais eficiente. Durante o desenvolvimento do HEVY, fui percebendo que precisava aprofundar esses conhecimentos para conseguir construir um CRUD mais organizado e funcional._

**7b. O que aprendi — conceitos, princípios ou relações técnicas que não dominava no início e que agora consigo explicar com precisão (mínimo 3 objetos de conhecimento):**

| OBJETO DE CONHECIMENTO | O QUE EU NÃO DOMINAVA | O QUE APRENDI E CONSIGO DEMONSTRAR | EVIDÊNCIA (campo do Logbook onde aparece) |
|---|---|---|---|
| _Estruturas condicionais_ | _Tinha dificuldade em entender como utilizar condições para controlar diferentes situações._ | _Aprendi a utilizar if, elif e else para verificar condições e controlar as operações do HEVY._ | _Ciclos 04 e 05; Campo 03_ |
| _Estruturas de repetição_ | _Não compreendia totalmente como manter o programa funcionando sem repetir comandos manualmente._ | _Aprendi a utilizar while para manter o menu ativo até o usuário escolher sair._ | _Ciclo 06_ |
| _Operações CRUD_ | _Tinha dificuldade em entender como organizar as etapas de cadastro, listagem, atualização e exclusão._ | _Consegui desenvolver essas operações no HEVY utilizando variáveis e condições para controlar os registros._ | _Ciclos 09 e 12_ |

**7c. Conceitos que precisei corrigir ao longo do ciclo — onde eu estava equivocado e o que o corrigiu (Fechamento Teórico, pesquisa, Peer Review, arguição):**

1. **Equívoco:** _Achava que as estruturas condicionais e de repetição tinham praticamente a mesma finalidade.
2. _ — **Correção:** _Entendi que as condicionais permitem tomar decisões, enquanto as estruturas de repetição executam comandos várias vezes._
   **O que corrigiu:** _As atividades práticas e os conteúdos estudados durante as aulas._
3. **Equívoco:** _Pensava que utilizar variáveis individuais seria suficiente para armazenar vários registros em um sistema._
— **Correção:** __Aprendi que listas e dicionários são estruturas mais adequadas para organizar e armazenar vários dados._
   **O que corrigiu:** _As aulas sobre listas e dicionários e a análise do CRUD de um colega no Peer Review._

**7d. Transferência — como este aprendizado se aplica a um contexto diferente do problema trabalhado (ao menos 1 exemplo concreto da área de formação):**

> _Consigo aplicar esses conhecimentos em um sistema de controle financeiro pessoal. Seria possível cadastrar despesas, informar valores e categorias, listar os registros, atualizar informações e excluir lançamentos. Utilizaria variáveis, condicionais e estruturas de repetição para controlar o funcionamento do sistema. Com conhecimentos mais avançados, também poderia utilizar listas, dicionários e funções para organizar melhor os dados e as operações._

**7e. Avaliação honesta do próprio percurso — o que ainda não domino e preciso aprofundar após este ciclo:**

> _Considero que evoluí bastante durante a disciplina, principalmente na compreensão da lógica de programação e na capacidade de desenvolver um sistema utilizando os conteúdos estudados. Mesmo conseguindo construir o HEVY, ainda preciso praticar mais a utilização de listas, dicionários, funções e recursividade. Também quero melhorar a organização do código e ganhar mais segurança para explicar minhas decisões técnicas. Pretendo continuar praticando esses conteúdos para conseguir desenvolver projetos mais completos nos próximos módulos._

---

# 🏁 DEFESA TÉCNICA — quarta 18/11

<details>
<summary>📘 Orientações para a Defesa Técnica e preparação</summary>

**A Defesa é antes dos prazos dos Grupos 2 e 3.** Você será arguido sobre o que já estiver registrado e commitado. Priorize, até **terça 17/11**:
- ✅] **Grupo 1 entregue** (prazo 16/11): Identificação, Registros 01 a 04, Campos 01 e 02.
- [✅] **Campo 04 (IA)** e **Campo 03** ao menos em rascunho, para sustentar as perguntas sobre decisões (critérios 2 e 5).
- ✅] **Campo 06c** (pergunta da banca e resposta) e **rascunho de 7a e 7b**, para sustentar a evolução conceitual (critério 3).
- [✅] Registros dos Ciclos já feitos, mesmo que ainda não "entregues" no prazo do grupo.
- [✅] `README.md`, `docs/` e CRUD rodando.
- [ ] Você consegue explicar **cada linha** do seu código e **cada decisão** registrada.
- Os demais itens seguem com os prazos dos grupos (21/11 e 26/11). A banca pode consultar o histórico do Git.

**A Defesa Técnica é individual.** Você será arguido sobre o que registrou. Cada aluno recebe pelo menos **1 questão** nos níveis de **Avaliação** ou **Criação** (taxonomia de Bloom).

**Como a Rubrica se liga ao seu Logbook:**

| Critério da Rubrica | Onde você prepara a evidência |
|---|---|
| 1. Domínio dos objetos de conhecimento | Campos 01, 02 e 07b |
| 2. Aplicação do conteúdo à solução ⚠️ *inegociável* | Registros dos ciclos (itens 3 e 5), Campo 03c e Campo 05e |
| 3. Evolução conceitual ⚠️ *inegociável* | Campo 01 → Campo 07 (7a, 7b e 7c; leve o rascunho) |
| 4. Capacidade de transferência | Campo 07d |
| 5. Argumentação sob pressão | Campo 06c e Campo 04e |
| 6. Autonomia intelectual e coerência com o Logbook | Todo o Logbook (principalmente Campos 04 e 06a) |

**Treino:** peça a um colega que faça 3 perguntas "imprevistas" sobre o seu CRUD e responda **sem consultar** o Logbook. Se não conseguir, volte ao Campo 06b.
</details>

## 🧩 RUBRICA DE DEFESA TÉCNICA (revisada)
*Avaliação individual de cada membro na Semana 16. Cada membro recebe ao menos 1 questão nos níveis de Avaliação ou Criação da Taxonomia de Bloom. Critérios revisados para medir aprendizagem, aplicação, evolução e transferência do conteúdo.*

| | |
|---|---|
| **Nome** | _…_ |
| **Curso / Time / Função** | _…_ |

<details>
<summary>🔒 Uso do professor — rubrica completa</summary>

| CRITÉRIO | EXCELENTE (4,0) | SATISFATÓRIO (3,0) | INSATISFATÓRIO (2,0) | AUSENTE (0) |
|---|---|---|---|---|
| **1. DOMÍNIO DOS OBJETOS DE CONHECIMENTO** — Responde com precisão técnica, sem apoio dos colegas, demonstrando aprendizagem do conteúdo. | Responde com precisão e profundidade, nomeando os objetos de conhecimento mobilizados sem hesitação. | Responde com precisão, com imprecisões pontuais que não comprometem o raciocínio. | Responde de forma vaga, com erros conceituais relevantes ou dependendo dos colegas. | Não responde ou demonstra desconhecimento total. |
| **2. APLICAÇÃO DO CONTEÚDO À SOLUÇÃO** — Demonstra como os objetos de conhecimento fundamentaram as decisões do processo. | Explicita com precisão qual objeto de conhecimento fundamentou cada decisão relevante do processo investigativo, citando referência e demonstrando por que aquele conhecimento era o mais adequado. | Estabelece a relação conteúdo-decisão na maioria das perguntas, com alguma imprecisão pontual. | Não consegue explicitar a relação entre o conteúdo e as decisões do processo investigativo com clareza. | Não demonstra nenhuma relação entre os objetos de conhecimento e as decisões tomadas. |
| **3. EVOLUÇÃO CONCEITUAL** — Demonstra aprendizagem em relação ao que sabia no início do ciclo. | Identifica com precisão o que aprendeu, o que corrigiu e como o conhecimento evoluiu ao longo do ciclo. | Demonstra evolução em parte dos conceitos trabalhados, com alguma dificuldade de articular a trajetória. | Dificuldade em identificar diferenças entre o que sabia no início e o que domina agora. | Não demonstra nenhuma percepção de evolução conceitual ao longo do ciclo. |
| **4. CAPACIDADE DE TRANSFERÊNCIA** — Aplica o conhecimento a um contexto diferente do problema trabalhado. | Consegue transferir o aprendizado para um contexto novo com fundamentação técnica precisa. | Realiza a transferência com imprecisões que não comprometem a lógica do raciocínio. | Demonstra dificuldade em aplicar o conhecimento a contextos diferentes do problema original. | Não consegue realizar nenhuma transferência do conhecimento para contexto diferente. |
| **5. ARGUMENTAÇÃO SOB PRESSÃO** — Mantém coerência técnica diante de questionamentos imprevistos. | Mantém raciocínio coerente, reconhece limites com honestidade e reformula com fundamentação. | Mantém coerência na maior parte, com hesitações pontuais sem perda do fio técnico. | Fragilidade técnica diante de questionamentos imprevistos. | Não sustenta argumentação técnica diante de nenhum questionamento. |
| **6. AUTONOMIA INTELECTUAL E COERÊNCIA COM O LOGBOOK** — Defende o que registrou com consciência e sem depender do grupo. | Defende com precisão as decisões do Logbook, demonstrando autoria plena e independência intelectual. | Defende a maioria das decisões com coerência, com alguma imprecisão ou apoio pontual. | Depende dos colegas ou demonstra desconhecimento de parte do que registrou no próprio Logbook. | Não reconhece o que registrou ou não demonstra autonomia intelectual durante a arguição. |

**PONTUAÇÃO:** _____ / 24,0 **CONCEITO:** _____________

**Conversão:** 20–24 = Excelente (4,0) | 14–19 = Satisfatório (3,0) | 8–13 = Insatisfatório (2,0) | < 8 = Ausente (0)

> ⚠️ **Critérios 2 (Aplicação) e 3 (Evolução Conceitual) são inegociáveis — AUSENTE em qualquer um deles implica nota máxima de 2,0 na Defesa, independentemente do desempenho nos demais.**

**OBSERVAÇÕES:** _…_

**Professor(a):** _________________  **Data:** ___________
</details>

### Registro do Encerramento — 18/11
1. **O que apresentei/defendi (em 1 frase):** _…_
2. **Objeto(s) de conhecimento que a banca mais explorou:** _…_
3. **Pergunta que mais me desafiou e como respondi:** _…_
4. **O que levo deste semestre para o próximo módulo:** _…_

---

# 🆘 Estou atrasado no Logbook. E agora?

1. **Não apague nem "retroescreva" o passado.** Preencha agora e **escreva a data real** do preenchimento (ex.: *"preenchido com atraso em 12/11"*).
2. **Campo 01 e Checkpoint (sem consulta):** se perdeu a janela, registre **o que sabe hoje, sem consultar nada**, marcando-o como *preenchimento tardio*. Combine o tratamento com o professor.
3. **Priorize a ordem dos grupos:** Grupo 1 (16/11) → Defesa (18/11) → Grupo 2 (21/11) → Grupo 3 (26/11). Dentro de cada grupo, os Campos vêm antes dos Registros.
4. **Use o histórico do Git** (`git log --oneline`) para reconstruir o que fez em cada ciclo — ele é uma evidência melhor que a memória.
5. **Fale com o professor** antes do prazo, não depois.

