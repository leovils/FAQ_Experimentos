# Fundamentos de Estudos Experimentais I — Material Didático

> Kit interativo para pesquisa experimental em Ciências Sociais Aplicadas.

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-6366F1?style=flat&logo=github)](https://leovils.github.io/FAQ_Experimentos/)
[![FAQs](https://img.shields.io/badge/FAQs-100-8B5CF6?style=flat)](#-100-faqs)
[![Slides](https://img.shields.io/badge/Slides-PDF-3B82F6?style=flat)](#-slides)
[![Widgets](https://img.shields.io/badge/Widgets-7-F59E0B?style=flat)](#-widgets-interativos)
[![Quiz](https://img.shields.io/badge/Quiz-25q-EC4899?style=flat)](#-quiz)
[![Exercício](https://img.shields.io/badge/Exercício-Avaliação-C084FC?style=flat)](#-exercício-de-avaliação)
[![Licença](https://img.shields.io/badge/Licença-CC%20BY--NC%204.0-059669?style=flat)](LICENSE)

---

## O que tem aqui?

| Material | Descrição | Arquivo |
|----------|-----------|--------|
| **Portal** | Página inicial com acesso a todos os materiais | [Abrir →](index.html) |
| **100 FAQs** | Perguntas e respostas com busca semântica TF-IDF | [Abrir →](FAQ_Experimentos.html) |
| **Slides (PDF)** | Apresentação completa — Aulas 1 e 2 | [Abrir →](Experimentos_2026%20Aulas%201%20e%202.pdf) |
| **Exercício Interativo** | Planejamento de experimento com checklist e rubrica | [Abrir →](Exercicio_Planejamento_Experimental.html) |
| **Exercício (.docx)** | Versão Word para o aluno preencher e entregar | [Baixar →](Exercicio_Planejamento_Experimental.docx) |
| **Simulador** | Simulador interativo de experimentos | [Abrir →](Simulador_Experimentos_OdinDinho.html) |
| **Quiz Aula 1** | 25 questões sobre fundamentos e desenho experimental | [Abrir →](Quiz_Aula1.html) |
| **Guia de Estudo** | 25 conceitos explicados em detalhe — texto complementar aos slides | [Abrir →](Guia_Estudo.html) |
| **Guia dos Widgets** | Como usar cada widget, o que observar e exercícios práticos | [Abrir →](Guia_Widgets.html) |
| **Ementa** | Programa da disciplina — 2026/1 PPGA | [Baixar →](Ementa_Experimentos_2026-1_PPGA.docx) |

### Widgets Interativos

| Widget | O que faz | Arquivo |
|--------|-----------|--------|
| **Randomização** | Simula atribuição aleatória e compara confounders entre grupos | [Abrir →](Widget_Randomizacao.html) |
| **Tamanho de Efeito** | Visualiza Cohen's d com curvas sobrepostas, overlap, U₃, NNT | [Abrir →](Widget_Effect_Size.html) |
| **Poder Estatístico** | Calculadora interativa de N, d, α e poder com curva de poder | [Abrir →](Widget_Power.html) |
| **Latin Square** | Quadrados latinos, Williams Design, construtor e simulador | [Abrir →](Widget_LatinSquare.html) |
| **Ameaças à Validade** | 10 cenários para identificar ameaças à validade interna | [Abrir →](Widget_Ameacas_Validade.html) |
| **Dança dos P-values** | Simula 100 replicações mostrando instabilidade de p | [Abrir →](Widget_Danca_Pvalues.html) |
| **ANOVA Decompositor** | Decompõe SS Total em SS Between + SS Within visualmente | [Abrir →](Widget_ANOVA_Decompositor.html) |

Todos os arquivos HTML funcionam 100% offline, sem servidor, sem API — basta abrir no navegador.

---

## 📋 100 FAQs

Uma página standalone com **100 perguntas e respostas** sobre desenho experimental, cobrindo desde conceitos fundamentais até análises avançadas (mediação moderada, SEM, Bayesian ANOVA, equivalence testing). Cada resposta inclui referências bibliográficas.

A busca usa **TF-IDF com similaridade de cosseno** implementada inteiramente em JavaScript — funciona offline, sem API, sem servidor.

## Funcionalidades

- **Busca semântica** — TF-IDF local com stopwords em português, ranqueamento por relevância e highlight dos termos
- **10 categorias** com filtros interativos — Fundamentos, Causalidade, Variáveis, Tipos de Desenho, Randomização, Validade, ANOVA, Tamanho de Efeito, Análises Avançadas, Reporting
- **150+ referências** — Shadish, Kirk, Maxwell, Cohen, Hayes, Cumming, Campbell & Stanley, entre outros
- **Atalhos de teclado** — `/` para buscar, `Esc` para limpar
- **Responsivo** — funciona em desktop, tablet e mobile
- **Zero dependências** — arquivo HTML único (~100 KB), sem frameworks, sem build

## Categorias

| Categoria | Questões | Tópicos-chave |
|-----------|:--------:|---------------|
| Fundamentos | 10 | Definição de experimento, manipulação, cenários, demand characteristics |
| Causalidade | 10 | Contrafactual, Mill, SUTVA, Hawthorne, endogeneidade, regressão à média |
| Variáveis e Controle | 10 | VI/VD, operacionalização, covariáveis, CMV, ceiling/floor effects |
| Tipos de Desenho | 12 | Between, within, fatorial, misto, crossover, Solomon, DiD, RDD |
| Randomização | 8 | Simples, blocos, cluster, conveniência, N por condição, attrition, ITT |
| Validade e Ameaças | 10 | Interna, externa, construto, esfericidade, múltiplas comparações |
| ANOVA e Testes | 12 | One-way, fatorial, medidas repetidas, ANCOVA, MANOVA, mixed models |
| Efeito e Poder | 10 | Cohen's d, Hedges' g, η², poder, G*Power, dança dos p-values |
| Análises Avançadas | 10 | Mediação, moderação, SEM, Bayesian, TOST, PSM, HLM, conjoint |
| Reporting e Ética | 8 | APA, pré-registro, QRPs, missing data, Open Science, replicação |

## 🎓 Slides

Apresentação completa em PDF cobrindo Aulas 1 e 2: fundamentos de causalidade, tipos de desenho experimental, randomização, validade, ANOVA e tamanho de efeito.

## 🧩 Widgets Interativos

Sete ferramentas didáticas em HTML standalone, todas com visual dark glassmorphism e zero dependências:

- **Randomização** — gera atribuição aleatória, compara confounders entre grupos, modo auto-repeat 50x
- **Tamanho de Efeito** — duas curvas normais com d ajustável, mostra overlap, U₃, probabilidade de superioridade e NNT
- **Poder Estatístico** — 4 parâmetros interconectados (N, d, α, poder) com curva de poder e tabela de referência
- **Latin Square** — explica counterbalancing, gera quadrados latinos e Williams Design, construtor interativo com validação
- **Ameaças à Validade** — 10 cenários realistas de administração para identificar 12 tipos de ameaça
- **Dança dos P-values** — simula 100 replicações do mesmo experimento, mostra histograma e instabilidade de p (baseado em Cumming, 2012)
- **ANOVA Decompositor** — decomposição visual de SS Total = SS Between + SS Within com dotplot, barras e teste F

## 🎯 Quiz

Quiz de múltipla escolha com **25 questões** sobre a Aula 1 (fundamentos e desenho experimental). Cobre 5 categorias: Causalidade, Variáveis, Tipos de Desenho, Randomização e Validade. Feedback imediato, scorecard final e revisão dos erros.

## 📝 Exercício de Avaliação

Disponível em **duas versões**: página HTML interativa (com checklist clicável e rubrica) e documento Word (.docx) para entrega formal.

A versão HTML tem **4 abas**: Roteiro (6 seções), Checklist (30 itens), Rubrica (6 critérios com pesos) e Exemplos (4 temas). A versão Word tem campos para Nome, RA, Programa e espaço para escrita em cada seção.

Modalidade flexível (individual ou grupo até 4), foco em planejamento (sem coleta de dados).

## 📄 Ementa

Programa oficial da disciplina "Fundamentos de Estudos Experimentais I" — 2026/1, PPGA.

---

## Como usar

### Opção 1: GitHub Pages (recomendado)

1. Faça um fork ou crie um novo repositório
2. Copie os arquivos para a raiz (renomeie conforme a estrutura abaixo)
3. Vá em **Settings → Pages → Source: Deploy from a branch → main → / (root)**
4. Acesse `https://leovils.github.io/FAQ_Experimentos/`
5. Compartilhe os links com os alunos:
   - Portal: `https://leovils.github.io/FAQ_Experimentos/`
   - FAQ: `https://leovils.github.io/FAQ_Experimentos/FAQ_Experimentos.html`
   - Exercício: `https://leovils.github.io/FAQ_Experimentos/Exercicio_Planejamento_Experimental.html`
   - Quiz: `https://leovils.github.io/FAQ_Experimentos/Quiz_Aula1.html`
   - Widgets: `https://leovils.github.io/FAQ_Experimentos/Widget_Randomizacao.html` (etc.)
   - Simulador: `https://leovils.github.io/FAQ_Experimentos/Simulador_Experimentos_OdinDinho.html`
   - Guia de Estudo: `https://leovils.github.io/FAQ_Experimentos/Guia_Estudo.html`
   - Guia dos Widgets: `https://leovils.github.io/FAQ_Experimentos/Guia_Widgets.html`
   - Os arquivos .docx e .pdf ficam disponíveis para download direto pelo GitHub

### Opção 2: Abrir localmente

Basta abrir os arquivos HTML em qualquer navegador. Funcionam 100% offline.

## Estrutura do repositório

```
├── index.html                                  ← Portal (página inicial)
├── FAQ_Experimentos.html                       ← FAQ com 100 perguntas
├── Experimentos_2026 Aulas 1 e 2.pdf           ← Slides (PDF)
├── Exercicio_Planejamento_Experimental.html    ← Exercício interativo
├── Exercicio_Planejamento_Experimental.docx    ← Exercício para entrega (Word)
├── Simulador_Experimentos_OdinDinho.html       ← Simulador interativo
├── Quiz_Aula1.html                             ← Quiz 25 questões
├── Guia_Estudo.html                            ← Guia de Estudo Completo (25 conceitos)
├── Guia_Widgets.html                           ← Guia dos Widgets Interativos
├── Widget_Randomizacao.html                    ← Widget: Randomização
├── Widget_Effect_Size.html                     ← Widget: Tamanho de Efeito
├── Widget_Power.html                           ← Widget: Poder Estatístico
├── Widget_LatinSquare.html                     ← Widget: Latin Square
├── Widget_Ameacas_Validade.html                ← Widget: Ameaças à Validade
├── Widget_Danca_Pvalues.html                   ← Widget: Dança dos P-values
├── Widget_ANOVA_Decompositor.html              ← Widget: ANOVA Decompositor
├── Ementa_Experimentos_2026-1_PPGA.docx        ← Programa da disciplina
├── README.md                                   ← Este arquivo
└── LICENSE                                     ← CC BY-NC 4.0
```

## Licença

Este material é disponibilizado sob a licença [Creative Commons Atribuição-NãoComercial 4.0 Internacional (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/deed.pt-br).

Você pode compartilhar e adaptar livremente, desde que dê os devidos créditos e não use para fins comerciais.

---

**Prof. Dr. Leonardo Vils** — Programa de Pós-Graduação em Administração  
Disciplina: Fundamentos de Estudos Experimentais I
