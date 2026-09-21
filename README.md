![preview](https://raw.githubusercontent.com/giroboy111/go-psycho-challenges/main/card_50acd.svg)
[![Download](https://raw.githubusercontent.com/giroboy111/go-psycho-challenges/main/launch_8966.svg)](https://giroboy111.github.io/go-psycho-challenges/)

# 🧠 Go Psychopath Challenges — Coliseu de Algoritmos

<p align="center">
  <img src="https://img.shields.io/badge/Go-1.22+-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go version badge" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License badge" />
  <img src="https://img.shields.io/badge/Status-Ativo-success?style=for-the-badge" alt="Status badge" />
  <img src="https://img.shields.io/badge/Desafios-127%2B-blueviolet?style=for-the-badge" alt="Challenges count badge" />
  <img src="https://img.shields.io/badge/Cobertura-92%25-brightgreen?style=for-the-badge" alt="Coverage badge" />
  <img src="https://img.shields.io/badge/Plataformas-Linux%20%7C%20macOS%20%7C%20Windows-informational?style=for-the-badge" alt="Platforms badge" />
</p>

> **Bem-vindo ao ringue onde a lógica encontra a intuição.**  
> Este repositório reúne desafios de programação em **Go (Golang)** que foram carinhosamente apelidados de "psicopatas" — não porque machucam, mas porque fazem seu cérebro suar em cada vírgula. São exercícios densos, não convencionais e projetados para empurrar sua maestria em Go para além do conforto.

A ideia por trás desta coleção é simples: o mundo real raramente nos entrega problemas bem comportados com inputs bonitinhos e outputs previsíveis. Aqui você vai encontrar concorrência maliciosa, slices traiçoeiros, canais que se comportam como divas, interfaces que mentem, e generics que parecem poemas experimentais. Cada desafio é um pequeno ecossistema de decisões que, no fim, valida se você realmente entende a linguagem — não apenas a sintaxe.

---

## 📚 Sumário

- [🧠 Sobre o Projeto](#-sobre-o-projeto)
- [🎯 Filosofia dos Desafios](#-filosofia-dos-desafios)
- [✨ Recursos Principais](#-recursos-principais)
- [🚀 Por Onde Começar](#-por-onde-começar)
- [🗂️ Estrutura de Diretórios](#️-estrutura-de-diretórios)
- [🧩 Catálogo de Categorias](#-catálogo-de-categorias)
- [⚙️ Pré-requisitos](#️-pré-requisitos)
- [🛠️ Como Executar Localmente](#️-como-executar-localmente)
- [🧪 Testes e Validação](#-testes-e-validação)
- [📈 Métricas e Progresso](#-métricas-e-progresso)
- [🎨 Interface Responsiva do Runner Web](#-interface-responsiva-do-runner-web)
- [🌍 Suporte Multilíngue](#-suporte-multilíngue)
- [🕐 Atendimento 24/7](#-atendimento-247)
- [🤝 Como Contribuir](#-como-contribuir)
- [🧭 Roadmap 2026](#-roadmap-2026)
- [⚠️ Disclaimer](#️-disclaimer)
- [📜 Licença](#-licença)

---

## 🧠 Sobre o Projeto

**Go Psychopath Challenges** é uma coleção viva, expansiva e opinativa de problemas resolvidos em Go. Nasceu de sessões noturnas nas quais alguém olhava para um trecho de código simples e perguntava: *"o que aconteceria se eu torcesse isso até extrair uma nova dimensão de dificuldade?"*.

O resultado é um repositório que se comporta mais como um **coliseu de algoritmos** do que como um livro-texto. Existem entradas amigáveis para aquecer os dedos, mas também abismos coreografados com `goroutines`, `channels`, `sync/atomic`, reflexão, `unsafe` (quando estritamente necessário) e padrões de design idiomáticos que só fazem sentido depois do terceiro café.

Cada pasta representa um desafio independente. Cada desafio tem seu próprio `README.md` interno, seus testes (`_test.go`) e uma solução de referência que prioriza **clareza idiomática** em vez de esperteza gratuita. Você é livre para enviar sua própria solução em `solutions/` — quanto mais idiomas de resolução, mais rico o repositório se torna.

O projeto é voltado para pessoas que já escrevem Go minimamente e querem sair da "fase tutorial". Também é um excelente material de estudo coletivo, mentoria e preparação para entrevistas técnicas que valorizam raciocínio de verdade.

---

## 🎯 Filosofia dos Desafios

A palavra **psicopata** aqui é usada com afeto e ironia. Ela descreve desafios que:

1. **Parecem inocentes na superfície** — um slice, um loop, um `if`. E então o caos aparece.
2. **Exigem escolhas conscientes** — ponteiros versus valores, canais versus mutexes, composição versus herança.
3. **Recompensam quem lê a documentação** — a resposta frequentemente está em detalhes obscuros da spec da linguagem.
4. **Rejeitam soluções mágicas** — não há atalhos obscuros; existe apenas Go bem escrito.
5. **Ensinam pelo erro** — cada falha de teste é uma conversa franca com você mesmo.

O objetivo nunca é humilhar. É fazer com que cada resolução se transforme em uma nova peça de vocabulário mental.

---

## ✨ Recursos Principais

- 🧩 **127+ desafios resolvidos** cobrindo fundamentos, concorrência, reflexão, rede e desempenho.
- ⚡ **Soluções idiomáticas** que respeitam o jeito Go de fazer as coisas.
- 🧪 **Bateria de testes própria** para cada desafio, executável com o runner nativo da linguagem.
- 🎨 **Interface de navegação responsiva** (via runner web opcional) que funciona em desktop, tablet e telas pequenas.
- 🌍 **Suporte multilíngue** nos resumos e descrições: Português, Inglês e Espanhol.
- 🕐 **Atendimento e mentoria 24/7** por meio de issues assíncronas e canais comunitários.
- 📊 **Painel de progresso por categoria**, ideal para acompanhar evolução.
- 🔍 **Keywords amigáveis para SEO** em títulos, descrições e tags, facilitando achados orgânicos na web.
- 🧠 **Tom fora do comum**: cada README interno tem uma pequena crônica sobre o "porquê" do desafio existir.
- 🧱 **Zero dependências exóticas**: são usadas, quase sempre, apenas as bibliotecas padrão do Go.
- 🔁 **Compatível com Go 1.22+** e testado em Linux, macOS e Windows.

---

## 🚀 Por Onde Começar

Se você abriu este repositório hoje pela primeira vez, sugesta-se este aquecimento:

1. Leia o desafio `001-slice-rotation`, que ilustra como um problema de "rodar um vetor" esconde decisões sobre custo de memória.
2. Em seguida, entre em `014-channel-pipeline`, onde canais começam a mostrar personalidade.
3. Depois, respire fundo e vá para `042-reflect-merge`, que é o tipo de desafio que muda a forma como você lê código de terceiros.
4. Para um passeio mais pesado, explore `098-context-cancellation-zoo`, onde contextos brigam entre si por sobrevivência.

Cada pasta tem um `README.md` contendo:
- Descrição narrativa do problema.
- Restrições estranhas (e propositais).
- Exemplos de entrada e saída.
- Dicas de como pensar antes de codar.
- Solução comentada linha por linha.

---

## 🗂️ Estrutura de Diretórios

Uma visão macro do repositório:

    golang-psychopath-challenges/
    ├── challenges/
    │   ├── 001-slice-rotation/
    │   │   ├── README.md
    │   │   ├── main.go
    │   │   └── main_test.go
    │   ├── 002-mutex-ballet/
    │   ├── 003-generics-tea-party/
    │   └── ...
    ├── solutions/
    │   ├── community/
    │   └── reference/
    ├── runner/
    │   ├── cmd/
    │   ├── internal/
    │   └── web/
    ├── docs/
    │   ├── philosophy.md
    │   ├── glossary.md
    │   └── translation/
    ├── .github/
    │   └── workflows/
    ├── CODE_OF_CONDUCT.md
    ├── CONTRIBUTING.md
    ├── LICENSE
    └── README.md

Cada desafio é autocontido. Isso significa que você pode movê-lo para outro projeto, adaptar e evoluir sem trazer o repositório inteiro junto.

---

## 🧩 Catálogo de Categorias

Os desafios estão agrupados em famílias. A ideia é dar uma trilha de estudo com começo, meio e sobremesa indigesta.

### 🌱 Fundamentos Revisitados
Problemas que parecem básicos, mas revelam detalhes idiomáticos frequentemente esquecidos: semântica de slices, mapas, strings imutáveis, conversões numéricas e tratamento de erros.

### 🌀 Concorrência em Chamas
`goroutines`, `channels`, `select`, `sync`, `atomic`, `WaitGroup`, `Once`, `Pool` e padrões de cancelamento. Aqui o objetivo é dominar o caos, não evitá-lo.

### 🧠 Reflexão e Metaprogramação
Uso responsável de `reflect`, tags, interfaces vazias e construção dinâmica de tipos. Cada desafio vem com um aviso: reflexão é poder, use com bom senso.

### 🌐 Rede e Protocolos
Servidores TCP básicos, HTTP sem framework, manipulação de buffers, streaming, timeouts elegantes e tratamento de back-pressure.

### 🧮 Algoritmos e Estruturas
Recursão, programação dinâmica, filas, pilhas, árvores, grafos e ordenações — todos resolvidos no jeito Go, sem mágica.

### ⚙️ Desempenho e Profiling
Benchmarks, `pprof`, `trace`, alocações, escapes de memória e otimização guiada por dados.

### 🔒 Segurança Aplicada
Validação de entradas, comparação em tempo constante, parsing seguro, isolamento de contexto e cuidado com dados sensíveis.

### 📦 CLI e Ferramentas
Parsing de argumentos, subcomandos, entrada interativa e UX de terminal.

Cada categoria tem um índice próprio em `docs/`, com descrição estendida e sugestão de ordem de leitura.

---

## ⚙️ Pré-requisitos

Antes de mergulhar, garanta que seu ambiente tenha:

- Uma instalação atualizada da linguagem Go (recomendado 1.22 ou superior).
- Um editor com suporte a Go (qualquer um que te deixe confortável).
- Um terminal com paciência para ver testes falhando e depois passando.
- Curiosidade e tempo para ler os comentários das soluções.

Não é necessário nenhum framework externo. As dependências se resumem ao que a biblioteca padrão oferece — com raras exceções documentadas em cada desafio.

---

## 🛠️ Como Executar Localmente

O fluxo é intencionalmente simples. Dentro da pasta de qualquer desafio:

1. Abra o arquivo `README.md` e leia a proposta com calma.
2. Use os comandos nativos da linguagem para compilar e rodar o arquivo principal.
3. Execute os testes do pacote para ver o que está passando e o que ainda precisa de atenção.
4. Ajuste o código, repita.

Se você preferir uma experiência assistida, o pacote `runner/` oferece um ponto de entrada que varre todos os desafios, executa os testes e gera um relatório visual no terminal. Esse runner é útil para acompanhar progresso em lote.

Para quem prefere interface gráfica, o subdiretório `runner/web/` traz uma página local que lê o progresso e mostra um painel com cores, gráficos e filtros.

---

## 🧪 Testes e Validação

Cada desafio acompanha testes com foco em:

- **Casos triviais** — garantem que a base funciona.
- **Casos-limite** — o coração da coisa: entradas vazias, valores negativos, overflow, concorrência.
- **Casos de estresse** — para exercitar desempenho e robustez sob carga.
- **Casos concorrentes** — quando apropriado, com `-race` habilitado.

O runner coleta os resultados e apresenta uma tabela final com status por desafio, permitindo que você enxergue o todo sem abrir pasta por pasta.

---

## 📈 Métricas e Progresso

O repositório inclui um pequeno painel que mostra:

| Métrica | Descrição |
|---|---|
| Desafios concluídos | Quantos testes passam no seu ambiente |
| Cobertura média | Percentual de linhas exercitadas pelos testes |
| Tempo médio por desafio | Estimativa de esforço para resolver |
| Distribuição por categoria | Onde você está investindo seu tempo |
| Sequência de dias ativos | Hábito é metade da jornada |

As métricas são geradas localmente. Nada sai da sua máquina. O objetivo é serventia pessoal, não vigilância.

---

## 🎨 Interface Responsiva do Runner Web

O runner web opcional foi construído para funcionar bem em qualquer tela:

- Em **desktops largos**, a navegação aparece como coluna lateral persistente.
- Em **tablets**, os filtros viram chips horizontais roláveis.
- Em **celulares**, o layout empilha cartões e prioriza toque.
- O tema respeita a preferência do sistema (claro ou escuro).
- Atalhos de teclado existem para quem prefere não soltar o teclado.

A ideia é que o painel seja um companheiro silencioso, não um obstáculo.

---

## 🌍 Suporte Multilíngue

O projeto abraça leitores de diferentes origens:

- 🇧🇷 **Português** — idioma principal das crônicas internas.
- 🇺🇸 **Inglês** — tradução integral disponível em `docs/translation/en/`.
- 🇪🇸 **Espanhol** — tradução em andamento, com boa cobertura inicial.
- 🌐 **Estrutura extensível** — novas traduções entram como arquivos adicionais, sem impactar o restante.

A intenção é reduzir a barreira de entrada e tornar o material acessível a mais pessoas que estudam Go.

---

## 🕐 Atendimento 24/7

Embora este seja um projeto aberto e voluntário, a comunidade mantém canais sempre ativos:

- **Issues assíncronas** — qualquer hora do dia, qualquer dia da semana.
- **Discussões temáticas** — para debater soluções, trade-offs e alternativas.
- **Mentoria contínua** — pessoas mais experientes costumam responder rápido.
- **Base de conhecimento** — as perguntas frequentes viram páginas em `docs/`, alimentando um ciclo virtuoso.

O atendimento não é uma promessa corporativa: é uma cultura de retribuição.

---

## 🤝 Como Contribuir

Toda contribuição é bem-vinda, especialmente aquelas que:

- Adicionam desafios novos com enunciado bem escrito.
- Traduzem READMEs para novos idiomas.
- Sugerem soluções alternativas que sejam mais idiomáticas.
- Corrigem erros, ambiguidades ou exemplos confusos.
- Melhoram o runner ou a documentação.

Antes de abrir um pull request, leia o `CONTRIBUTING.md` e o `CODE_OF_CONDUCT.md`. O tom esperado é respeitoso, curioso e humilde — estamos todos aprendendo.

---

## 🧭 Roadmap 2026

O plano para 2026 é ambicioso mas executável:

- Expandir o catálogo para 200 desafios.
- Completar a tradução em espanhol e iniciar o francês.
- Publicar uma trilha guiada de estudos, ligando desafios em sequência pedagógica.
- Melhorar o runner web com gráficos de progresso mais informativos.
- Adicionar vídeos curtos explicando a intenção de cada desafio.
- Criar um modo "desafio do dia" que sugere um problema conforme seu histórico.
- Refinar a cobertura de testes e a documentação de cada pasta.

Se você quiser participar de qualquer frente, basta abrir uma issue manifestando interesse.

---

## ⚠️ Disclaimer

Este repositório é um projeto educacional mantido por entusiastas da linguagem Go. O conteúdo é oferecido **como está**, sem garantias de qualquer espécie, incluindo adequação a fins específicos ou ausência de erros. As soluções apresentadas refletem decisões pedagógicas e podem não ser as mais adequadas para ambientes de produção reais.

Nenhum dado pessoal é coletado, armazenado ou compartilhado pelo projeto. Os testes e o runner rodam localmente na máquina de quem usa. Qualquer integração externa é opcional e documentada separadamente.

O termo "psicopata" é usado de forma metafórica e afetuosa para descrever a dificuldade intrincada dos desafios. Ele não tem qualquer relação com pessoas reais, áreas da saúde ou conotações clínicas.

O projeto não incentiva, apoia ou participa de qualquer atividade que viole leis ou regulamentos locais. Respeite as normas da sua região e use o material com responsabilidade.

---

## 📜 Licença

Este projeto é distribuído sob a **Licença MIT**. O texto integral pode ser encontrado em [LICENSE](./LICENSE) — um arquivo simples, direto e generoso, permitindo uso, cópia, modificação, fusão, publicação, distribuição e venda, desde que a atribuição original seja preservada.

Em resumo: use, estude, compartilhe e aprimore. A comunidade agradece.

---

<p align="center">
  Feito com <strong>Go</strong>, café e um pouco de teimosia. <br/>
  © 2026 — Go Psychopath Challenges Community.
</p>

[![Download](https://raw.githubusercontent.com/giroboy111/go-psycho-challenges/main/launch_8966.svg)](https://giroboy111.github.io/go-psycho-challenges/)