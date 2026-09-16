# 🏛️ Notion Workspace Master: Guia de Caxias do Sul (Lei Rouanet & Design System)
**Projeto:** Patrimônios, Marcos e Lendas — Guia de Caxias do Sul  
**Solicitante:** Soul Branding (Mateus Loreto)  
**Proponente / Fomento:** Guia de Caxias do Sul (Marivânia / Lei Rouanet)  
**Executor UI/UX & Produto:** Jefferson Motta — Onira Labs  
**Engenharia de Front-End:** Diogo / TI do Cliente (Migração React)  
**Data:** Setembro / 2026 | **Status:** 100% Consolidado  

---

> 📌 **Visão Geral do Projeto:**  
> Modernização da apresentação visual da nova área cultural (Lei Rouanet) do Guia de Caxias do Sul através de um **Design System com Tokens para React** e **8 Templates Mestres Replicáveis**, transformando o acervo histórico na infraestrutura de ativação econômica de toda a Serra Gaúcha.

---

## 🧭 Índice do Workspace

1. [🔍 1. Auditoria Cara-Crachá (Briefing Soul vs. Solução Onira)](#1-auditoria-cara-crachá-briefing-soul-vs-solução-onira)
2. [📊 2. Base de Inteligência & Diagnóstico Territorial](#2-base-de-inteligência--diagnóstico-territorial)
3. [💰 3. Devolutiva Orçamentária por Blocos (A, B, C, D)](#3-devolutiva-orçamentária-por-blocos-a-b-c-d)
4. [🗺️ 4. Análise de Modelos de Negócio & Split Pix](#4-análise-de-modelos-de-negócio--split-pix)
5. [🛡️ 5. Plano de Sustentação & Pitch Soul Branding](#5-plano-de-sustentação--pitch-soul-branding)
6. [📐 6. Matriz de 8 Templates Mestres & Handoff React](#6-matriz-de-8-templates-mestres--handoff-react)

---

## 🔍 1. Auditoria Cara-Crachá (Briefing Soul vs. Solução Onira)

### Confronto Direto dos Requisitos do Briefing Original:

| Requisito do Briefing Soul | Solução Técnica & Comercial Onira Labs | Conformidade |
|---|---|:---:|
| **Item 1: Régua de Ouro** (*"O que estende padrão, entra. O que vira refação, fica fora"*) | 100% adotado. Criamos **7 (+1) Templates Mestres Dinâmicos** alimentados pelo banco existente. Zero refação página a página. | ✅ **100% OK** |
| **Item 2: Estrutura do Site (12 Distritos / Urbana / Rural)** | Mapeamento exato de cada nível hierárquico para componentes React reutilizáveis. | ✅ **100% OK** |
| **Item 3: Escopo por Blocos (A, B, C, D)** | Orçamento modular e transparente por etapas (A: R$ 4,2k, B: R$ 6,8k, C: R$ 8,9k, D: R$ 4,5k). | ✅ **100% OK** |
| **Item 4: Fora de Escopo (Fronteira Clara)** | Confirmação estrita: código front-end (Diogo), APIs de mapa, textos/pesquisa e fotos estão excluídos. | ✅ **100% OK** |
| **Item 5: Prazos, Rodadas de Ajuste e Figma** | 25 a 28 dias úteis (Base) ou 45 a 50 dias (Integrado); 2 rodadas inclusas; Figma Dev Mode. | ✅ **100% OK** |
| **Ponto 6.1: Página Individual (Comércio vs Patrimônio)** | **Solução:** `TPL_03` comercial + `TPL_08` cultural dedicado (+ R$ 1.600 ou incluso no pacote). | ✅ **100% OK** |
| **Ponto 6.2: Complexidade do Mapa** | **Solução:** Mapa base com pins categorizados e drawer lateral retrátil. | ✅ **100% OK** |
| **Ponto 6.3 & 6.5: Herança Visual e Fotos Legadas** | Preservação de marca com ajuste WCAG AA; containers com `aspect-ratio` fixo. | ✅ **100% OK** |
| **Ponto 6.4: Handoff React com Diogo** | Reunião prévia de 45 min + Design Tokens exportáveis via Figma Dev Mode. | ✅ **100% OK** |
| **Ponto 6.6: Acessibilidade Lei Rouanet** | Padrão **WCAG 2.1 nível AA** obrigatório para aprovação sem glosa no MinC. | ✅ **100% OK** |

---

## 📊 2. Base de Inteligência & Diagnóstico Territorial

### O Apagão Digital do Interior de Caxias do Sul (Auditoria 100% dos 150 Rurais):
* **86,7% (130 de 150)** NÃO POSSUEM canal próprio funcional no interior.
* **118 empresas (78,7%)** não têm site (dependência 100% do Guia, WhatsApp e Instagram).
* **12 empresas (8,0%)** possuem sites mortos, fora do ar, com erro 404, DNS expirado ou SSL inválido.
* **Apenas 19 empresas (12,7%)** possuem site ativo respondendo HTTP 200.

> 📁 **Arquivos da Base Completa:**
> - CSV Consolidado (208 empresas com GMB, Insta e Localidade): [`database-completa-guia-caxias.csv`](file:///c:/Users/ADM/onira-labs/clientes/guia-caxias-soul/planilhas/database-completa-guia-caxias.csv)
> - JSON Estruturado para Engenharia: [`database-completa-guia-caxias.json`](file:///c:/Users/ADM/onira-labs/clientes/guia-caxias-soul/planilhas/database-completa-guia-caxias.json)

---

## 💰 3. Devolutiva Orçamentária por Blocos (A, B, C, D)

### Estrutura Modular dos Blocos:

| Bloco | Escopo Principal | Prazo | Investimento Fracionado |
|---|---|:---:|:---:|
| **Bloco A** | Estudo, Diagnóstico UX/IA, Benchmarking & Arquitetura de Navegação | 6 dias úteis | R$ 4.200,00 |
| **Bloco B** | Design System & Tokens (Figma Dev Mode → React + WCAG 2.1 AA) | 8 dias úteis | R$ 6.800,00 |
| **Bloco C** | 7 Templates Mestres Desktop (Home, Subcategorias, Detalhe, Distritos, Rouanet, Mapa, News) | 14 dias úteis | R$ 8.900,00 |
| **Bloco D** | Adaptação Responsiva Mobile-First (390px / Touch targets 44px) | +3 dias úteis | R$ 4.500,00 |
| **SUBTOTAL** | **Contratação Fracionada / Por Etapas** | **28 dias úteis** | **R$ 24.400,00** |
| **PACOTE BASE**| **CONTRATAÇÃO BASE INTEGRADA (A + B + C + D)** | **~25 dias úteis** | **R$ 22.800,00** |

### Cenário Recomendado: Projeto Integrado & Ativação Territorial
* **Investimento:** **R$ 40.000,00** | **Prazo Realista:** **~45 a 50 dias úteis**
* **Inclusões Nativas:**
  1. Todos os Blocos A, B, C e D do escopo base.
  2. **8º Template Dedicado Rouanet** (Patrimônio Cultural & Linha do Tempo).
  3. **Mapa Interativo com Camadas de Roteirização Turística**.
  4. **Estudo de Modelagem Econômica do Ecossistema** (Split Pix / SEGH / Monetização de Vouchers).
  5. Margem de segurança operacional para direção técnica sênior e contratações de apoio.

---

## 🗺️ 4. Análise de Modelos de Negócio & Split Pix

* **A Desconstrução do "Tiro no Pé" do WhatsApp:** Troca da contagem fria de cliques (CPC) pelo **WhatsApp Contextualizado com Benefício** (ex: *"Vi no Guia e gostaria de resgatar a sobremesa cortesia"*). O dono do restaurante sente o cliente entrando na loja.
* **Monetização de Experiências (Split Pix 10% / 90%):** Vouchers de degustação e almoço colonial com split direto no gateway (R$ 108 para vinícola / R$ 12 para o Guia) sem bitributação.
* **Tráfego Compartilhado de Influenciadores:** Coleções e roteiros assinados que trazem tráfego qualificado de fora sem custo fixo.

---

## 🛡️ 5. Plano de Sustentação & Pitch Soul Branding

* **Ato 1 (Dever de Casa):** Apresentar a conformidade estrita da Rouanet (WCAG AA), a ponte limpa com o Diogo (Tokens) e a modularidade de templates.
* **Ato 2 (O Gancho de Futuro):** A Onira Labs como braço de tecnologia e IA da Soul Branding para ativar o interior de Caxias do Sul.
* **Ato 3 (A Semente do Hub & SEGH):** Criar o "Kit de Presença Digital" para os associados do sindicato hoteleiro/gastronômico.

---

## 📐 6. Matriz de 8 Templates Mestres & Handoff React

1. `TPL_01_HOME`: Portal de entrada, vitrines, atalhos urbana/rural e chamada Rouanet.
2. `TPL_02_SUBCATEGORIAS`: Listagem dinâmica com filtros facetados (bairro, preço, ordenação).
3. `TPL_03_DETALHE_COMERCIAL`: Ficha comercial focada em conversão rápida e WhatsApp.
4. `TPL_04_DISTRITO`: Molde unificado para os 12 distritos de Caxias do Sul.
5. `TPL_05_HUB_ROUANET`: Centro histórico cultural com linhas do tempo e eixos temáticos.
6. `TPL_06_MAPA_INTERATIVO`: Interface cartográfica com pins categorizados e drawer lateral.
7. `TPL_07_NOTICIAS`: Grade editorial de matérias e comunicados.
8. `TPL_08_DETALHE_PATRIMONIO`: Ficha profunda para tombamentos, memórias e acervo histórico.
