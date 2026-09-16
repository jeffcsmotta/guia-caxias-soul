# Auditoria Cara-Crachá: Briefing Soul Branding vs. Resposta Técnica Onira Labs
**Projeto:** Patrimônios, Marcos e Lendas — Guia de Caxias do Sul (Lei Rouanet)  
**Solicitante:** Soul Branding (Mateus Loreto)  
**Proponente / Fomento:** Guia de Caxias do Sul (Marivânia / Lei Rouanet)  
**Executor UI/UX & Produto:** Jefferson Motta — Onira Labs  
**Engenharia de Front-End:** Diogo / TI do Cliente (Migração React)  
**Data da Auditoria:** Setembro / 2026 | **Status:** 100% de Conformidade e Alinhamento Técnico

---

> 🎯 **Objetivo Deste Documento:**  
> Confrontar, linha por linha, cada premissa, solicitação de escopo, delimitação de fronteira e ponto de atenção demandado no **Briefing Original da Soul Branding** com a **Solução Técnica & Comercial da Onira Labs**, demonstrando aderência total, eliminação de riscos de retrabalho e blindagem jurídica/técnica.

---

## 📋 MATRIZ DE CONFORMIDADE "CARA-CRACHÁ" (PONTO A PONTO)

```
┌───────────────────────────────────────────────┬───────────────────────────────────────────────┐
│     DEMANDA ORIGINAL (SOUL BRANDING)          │        RESPOSTA & SOLUÇÃO (ONIRA LABS)        │
└───────────────────────────────────────────────┴───────────────────────────────────────────────┘
```

---

### ITEM 1 — CONTEXTO & RÉGUA DE OURO DO ESCOPO

| # | Item do Briefing Soul Branding | Resposta Técnica & Comercial Onira Labs | Status |
|---|---|---|:---:|
| **1.1** | *"O cliente está estruturando um projeto pela Lei Rouanet voltado a Patrimônios, Marcos e Lendas de Caxias do Sul... O design entra para criar uma área nova à altura."* | **Aderência Plena:** A Onira Labs desenha a nova área cultural com padrão editorial de alta imersão, tipografia humanista e conformidade legal com os padrões de prestação de contas do MinC. | ✅ **Atendido** |
| **1.2** | *"TI do cliente (Diogo) está propondo migrar o front-end para React, mantendo banco de dados, CMS e conteúdos existentes."* | **Aderência Plena:** Todo o design é concebido como **Design System com Tokens exportáveis para React**, permitindo ao Diogo consumir variáveis e componentes prontos sem reinventar código. | ✅ **Atendido** |
| **1.3** | *"Três coisas que este projeto NÃO é: Não é site novo. Não é reformulação completa. Não é redesenho de todas as páginas."* | **Aderência Plena:** Zero desenho de páginas avulsas. Criamos **7 (+1) Templates Mestres Dinâmicos** que cobrem 100% das 561+ páginas atuais e futuras. | ✅ **Atendido** |
| **1.4** | **A Régua de Ouro:** *"O que estende padrão, entra. O que vira refação, fica fora."* | **Princípio Norteador:** Adotado como regra absoluta de arquitetura. Cada componente criado no Figma possui variante correspondente para estender o legado sem refazer o back-end. | ✅ **Atendido** |

---

### ITEM 2 — ESTRUTURA ATUAL DO SITE & MAPEAMENTO DE TEMPLATES

| Estrutura Mapeada no Briefing | Template Mestre Correspondente Onira Labs | Racional de Engenharia & Reuso no Banco |
|---|---|---|
| **Home (Banner + Destaques + Atalhos)** | `TPL_01_HOME` | Banner nobre, atalhos para Urbana/Rural/Distritos e vitrine de entrada do projeto Rouanet. |
| **Área Urbana & Rural (Categorias e Subcategorias)** | `TPL_02_SUBCATEGORIAS` | Molde dinâmico de listagem com barra facetada de filtros (bairro, preço, tags, ordenação). |
| **Páginas Individuais do Comércio Geral** | `TPL_03_DETALHE_COMERCIAL` | Ficha focada em conversão rápida: galeria, horários, mapa estático e botão WhatsApp contextualizado. |
| **Conheça os Distritos e Regiões (12 Distritos)** | `TPL_04_DISTRITO` | Molde unificado para os 12 distritos com história, mapa regional e atrativos locais. |
| **Patrimônios, Marcos e Lendas (Área Nova Rouanet)** | `TPL_05_HUB_ROUANET` | Centralizador cultural com linhas do tempo, eixos temáticos e chamada nobre para o Mapa. |
| **Página Mapa Interativo** | `TPL_06_MAPA_INTERATIVO` | Interface cartográfica com sistema de pins categorizados e drawer retrátil de preview. |
| **Notícias (Listagem e Editorial)** | `TPL_07_NOTICIAS` | Grade editorial com categorização e paginação padronizada. |
| **Detalhamento Patrimonial Dedicado** | `TPL_08_DETALHE_PATRIMONIO` *(Opcional / Integrado)* | Ficha profunda para monumentos e lendas: cronologia histórica, tombamento e citações Rouanet. |

---

### ITEM 3 — ESCOPO ORÇADO POR BLOCOS (A, B, C e D)

| Bloco | Demanda Soul Branding | Entregável Onira Labs | Prazo Base | Investimento Fracionado |
|---|---|---|:---:|:---:|
| **Bloco A** | **Estudo:** Diagnóstico de usabilidade + benchmarking + revisão da Arquitetura da Informação (sem reconstruir tudo). | Documento executivo de Diagnóstico UX/IA, mapa de navegação revisado e Racional de Design. | 6 dias úteis | **R$ 4.200,00** |
| **Bloco B** | **Sistema de Operação:** Tipografia, botões, cards, ícones, filtros, grid, espaçamentos e matriz de estados (hover, active, disabled, loading, empty) em tokens para React. | Biblioteca componentizada no Figma (Dev Mode) com Auto Layout nativo, Design Tokens (cores, tipografia, grid 8pt) e validação de acessibilidade WCAG AA. | 8 dias úteis | **R$ 6.800,00** |
| **Bloco C** | **Layouts Mestres:** 7 templates Desktop (Home, Subcategorias, Detalhe Comercial, Distrito, Hub Rouanet, Mapa, Notícias). | 7 Telas Mestres em alta fidelidade no Figma, estruturadas em fluxos de navegação e guias de auto-população de dados. | 14 dias úteis | **R$ 8.900,00** |
| **Bloco D** | **Adaptação Responsiva:** Desktop + Mobile para os 7 layouts (390px / touch / bottom sheets). | 7 Pranchas Mobile dedicadas (390px) com touch targets mínimos de 44px e gavetas inferiores de navegação rápida. | +3 dias úteis | **R$ 4.500,00** |
| **TOTAL** | **Contratação Fracionada / Por Bloco** | **Entrega Sequencial por Etapas Independentes** | **28 dias úteis** | **R$ 24.400,00** |
| **PACOTE** | **CONTRATAÇÃO BASE INTEGRADA (A + B + C + D)** | **Fluxo Contínuo com Desconto de Pacote** | **~25 dias úteis** | **R$ 22.800,00** |

---

### ITEM 4 — DELIMITAÇÃO CLARA DE FRONTEIRAS (FORA DE ESCOPO)

| # | Item Declarado Fora de Escopo | Confirmação Onira Labs |
|---|---|---|
| **4.1** | Programação e implementação de código front-end React | ✅ **Confirmado Fora:** A cargo estrito do Diogo / TI do cliente. A Onira entrega tokens e Figma Dev Mode. |
| **4.2** | Desenvolvimento e programação de APIs cartográficas do mapa | ✅ **Confirmado Fora:** A Onira entrega o design de UI/UX do mapa e dos pins; a integração de Leaflet/Mapbox/Google Maps é da TI. |
| **4.3** | Redação, pesquisa histórica, textos e curadoria patrimonial | ✅ **Confirmado Fora:** A cargo da equipe do projeto cultural / Lei Rouanet. |
| **4.4** | Produção fotográfica ou tratamento individual de imagens | ✅ **Confirmado Fora:** Design contempla containers com `aspect-ratio` fixo para absorver fotos legadas. |
| **4.5** | Redesenho do painel de gerenciamento / CMS | ✅ **Confirmado Fora:** A engenharia apenas consome os campos do CMS existente. |
| **4.6** | Redesenho das páginas de Agenda e notícia individual legado | ✅ **Confirmado Fora:** Preserva-se o padrão existente ou reutiliza-se o template de notícias. |
| **4.7** | Criação de marca, logotipo ou manual institucional do Guia | ✅ **Confirmado Fora:** Foco 100% digital e de produto. |

---

### ITEM 5 — FORMATO DE RECEBIMENTO DO ORÇAMENTO

| Requisito do Briefing | Definição na Proposta Onira Labs |
|---|---|
| **Valor por bloco e valor unitário de layout extra** | Blocos detalhados (A: R$ 4,2k, B: R$ 6,8k, C: R$ 8,9k, D: R$ 4,5k). **Layout Extra: R$ 1.600,00** (Desktop + Mobile inclusos). |
| **Prazos por bloco e total** | Cronograma transparente: 6 dias (A) + 8 dias (B) + 14 dias (C) + 3 dias (D) = **25 a 28 dias úteis** no fluxo base. |
| **Rodadas de ajuste incluídas** | **2 rodadas estruturadas de revisão** inclusas por bloco. Rodada excedente: **R$ 1.100,00** ou **R$ 180,00/hora técnica**. |
| **Ferramenta de trabalho e entrega** | **Figma Oficial** com acesso total de edição para a Soul Branding e Figma Dev Mode habilitado para o Diogo (TI). |
| **Documentação de handoff para React** | Especificação técnica de Design Tokens (cores, espaçamentos, tipografia, breakpoints) documentada em [`handoff-tokens-react.md`](file:///c:/Users/ADM/onira-labs/clientes/guia-caxias-soul/specs/handoff-tokens-react.md). |
| **Declaração de premissas e disponibilidade** | Início em até **5 dias úteis** após aprovação formal da proposta. |

---

### ITEM 6 — AUDITORIA DOS 6 PONTOS DE ATENÇÃO CRÍTICOS

#### 🔴 Ponto 6.1: A página individual pode não ser um layout só
* **O Risco Apontado pela Soul:** Patrimônio histórico exige linha do tempo, tombamento e acervo cultural, enquanto o restaurante comercial exige telefone, horários e fotos de pratos.
* **A Resolução Técnica da Onira:**
  * **Solução Base:** O `TPL_03` atende 95% do comércio com foco em conversão rápida.
  * **Extensão Recomendada:** Criação do `TPL_08 (Detalhe Patrimonial Rouanet)` dedicado exclusivamente à área cultural, orçado como layout adicional por **+ R$ 1.600,00** (ou já incluso no Pacote Integrado). Isso evita criar uma "interface Frankenstein".

#### 🔴 Ponto 6.2: Complexidade do Mapa Interativo
* **O Risco Apontado pela Soul:** Interface de mapa é o item mais complexo; pode variar de um mapa simples com pins até sistemas com camadas, filtros e rotas.
* **A Resolução Técnica da Onira:**
  * **Nível Base (Incluso no Bloco C):** Canvas de mapa base + pins categorizados com cores dos nichos + Drawer/Card retrátil com preview do atrativo e botão "Ver Mais".
  * **Nível Avançado (Roteirização Sequencial):** Se o cliente exigir montagem de roteiros turísticos multi-pontos passo a passo no mapa, orçado como aditivo de **+ R$ 2.400,00** (ou incluso no Pacote Integrado).

#### 🔴 Ponto 6.3: Herança Visual do Guia
* **O Risco Apontado pela Soul:** Não perder a identidade visual do Guia, mas garantir sofisticação contemporânea.
* **A Resolução Técnica da Onira:**
  * Preservação da paleta histórica com ajuste cromático de saturação e contraste para garantir conformidade estrita no teste **WCAG 2.1 AA** exigido pela Lei Rouanet.

#### 🔴 Ponto 6.4: Dependência e Integração com o Diogo (TI / React)
* **O Risco Apontado pela Soul:** O design ser desenhado de forma desconectada da arquitetura React do desenvolvedor.
* **A Resolução Técnica da Onira:**
  * Realização de uma **reunião de alinhamento prévio de 45 minutos** antes do Bloco B para alinhar convenções de classes (Tailwind CSS, Styled Components ou CSS Modules) e hierarquia de tokens.

#### 🔴 Ponto 6.5: Acervo Heterogêneo de Imagens
* **O Risco Apontado pela Soul:** Fotos antigas de patrimônios de baixa resolução convivendo com fotos profissionais de restaurantes.
* **A Resolução Técnica da Onira:**
  * O Design System utiliza containers com proporção travada (`aspect-ratio: 16/9` e `4/3`), filtros sutis de tratamento CSS e estados de placeholder elegantes para que nenhuma foto quebre o grid.

#### 🔴 Ponto 6.6: Acessibilidade Legal (Lei Rouanet)
* **O Risco Apontado pela Soul:** O projeto cultural ser reprovado ou sofrer glosa na prestação de contas do MinC por falta de acessibilidade.
* **A Resolução Técnica da Onira:**
  * Aplicação rigorosa das diretrizes **WCAG 2.1 nível AA**: contraste mínimo de 4.5:1 para texto normal, touch targets de 44x44px no mobile, suporte nativo a leitores de tela e hierarquia semântica de headings (`h1` a `h4`).

---

## 💰 QUADRO COMPARATIVO DOS 2 CENÁRIOS COMERCIAIS

```
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│ CENÁRIO 1 — PACOTE BASE ROUANET: R$ 22.800,00 (Prazo: 25 a 28 dias úteis)                        │
│ Atende estritamente o briefing original: Bloco A (IA/UX) + Bloco B (Tokens React) +             │
│ Bloco C (7 Templates Mestres) + Bloco D (Mobile 390px).                                          │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│ CENÁRIO 2 — PROJETO INTEGRADO & ATIVAÇÃO TERRITORIAL: R$ 40.000,00 (Prazo: 45 a 50 dias úteis)   │
│ Inclui tudo do Cenário 1 + 8º Template Dedicado Rouanet + Mapa com Camadas de Roteirização +     │
│ Estudo de Modelagem Econômica do Ecossistema (Split Pix / SEGH / Monetização Rural) + Margem     │
│ operacional realista para direção técnica e contratações de apoio.                              │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
```
