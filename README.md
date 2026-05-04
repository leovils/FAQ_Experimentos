# 100 FAQs — Desenho e Análise de Experimentos

> Guia interativo com busca semântica para pesquisa experimental em Ciências Sociais Aplicadas.

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-6366F1?style=flat&logo=github)](https://SEU-USUARIO.github.io/faq-experimentos/)
[![Questões](https://img.shields.io/badge/FAQs-100-8B5CF6?style=flat)](#categorias)
[![Referências](https://img.shields.io/badge/Referências-150+-C084FC?style=flat)](#)
[![Licença](https://img.shields.io/badge/Licença-CC%20BY--NC%204.0-059669?style=flat)](LICENSE)

---

## O que é?

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

## Como usar

### Opção 1: GitHub Pages (recomendado)

1. Faça um fork ou crie um novo repositório
2. Copie `FAQ_Experimentos_100.html` para a raiz como `index.html`
3. Vá em **Settings → Pages → Source: Deploy from a branch → main → / (root)**
4. Acesse `https://seu-usuario.github.io/nome-do-repo/`

### Opção 2: Abrir localmente

Basta abrir `FAQ_Experimentos_100.html` em qualquer navegador. Funciona 100% offline.

## Estrutura do repositório

```
├── index.html              ← FAQ (renomeie de FAQ_Experimentos_100.html)
├── README.md               ← Este arquivo
└── LICENSE                 ← CC BY-NC 4.0
```

## Licença

Este material é disponibilizado sob a licença [Creative Commons Atribuição-NãoComercial 4.0 Internacional (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/deed.pt-br).

Você pode compartilhar e adaptar livremente, desde que dê os devidos créditos e não use para fins comerciais.

---

**Prof. Dr. Leonardo Vils** — Programa de Pós-Graduação em Administração  
Disciplina: Desenho e Análise de Experimentos I e II
