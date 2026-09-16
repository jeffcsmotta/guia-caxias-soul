# Resposta ao Briefing — Orçamento de UI/UX & Design System
**Projeto:** Patrimônios, Marcos e Lendas — Guia de Caxias do Sul  
**Executor:** Jefferson Motta (Onira Labs) — UI/UX & Produto Digital  
**Solicitante:** Soul Branding (A/C Mateus Loreto)  
**Cliente Final:** Guia de Caxias do Sul (Projeto via Lei Rouanet)  
**Data:** Setembro / 2026  

---

> *Documento espelho da estrutura de solicitação da Soul Branding (Itens 1 a 6).*

---

### 1. Alinhamento de Premissa & Régua de Escopo

Compartilho e adoto integralmente a régua de corte estabelecida pela Soul Branding:
* **"O que estende padrão, entra. O que vira refação, fica fora."**
* **Não é site novo nem redesenho página a página:** O projeto consiste em modernizar a apresentação visual da **nova área cultural/histórica (Lei Rouanet)** e, nessa esteira, criar um **Design System dinâmico (Figma → React)** que o Diogo (TI) consiga replicar gradativamente para o restante do portal sem retrabalho.

---

### 2. Arquitetura e Estrutura Contemplada

O orçamento foi calculado considerando **7 Templates Mestres Replicáveis**, alimentados dinamicamente pelo banco de dados e gerenciador existente, cobrindo todo o ecossistema urbano, rural, distritos e o novo acervo cultural.

---

### 3. Escopo Orçado por Blocos (A, B, C e D)

#### Bloco A — Estudo, Diagnóstico & Direção UX/IA
* **Escopo:**
  * Diagnóstico crítico de usabilidade do site legado e benchmarking com portais contemporâneos de turismo e acervo patrimonial.
  * Revisão da Arquitetura da Informação para a inserção natural e fluida da nova área Rouanet e do Mapa Interativo.
  * Mapeamento de hierarquia visual e experiência de navegação do usuário.
* **Entregável:** Documento executivo de Diagnóstico, Arquitetura e Racional de Design (PDF/Notion).
* **Investimento:** **R$ 4.200,00**
* **Prazo:** **6 dias úteis**

#### Bloco B — Sistema de Operação / Design System Digital (Figma → React)
* **Escopo:**
  * **Design Tokens:** Tipografia, paleta semântica e de contraste, grid de 8pt, raios de borda e espaçamentos.
  * **Componentes Fundamentais:** Botões, inputs, cards de listagem, tags/badges, ícones, seletores de filtros, breadcrumbs e cabeçalhos.
  * **Matriz de Estados:** Estados estruturados para `Default`, `Hover`, `Active`, `Focus`, `Disabled`, `Loading (Skeleton)` e `Empty State`.
  * **Acessibilidade Legal:** Critérios de contraste e legibilidade alinhados ao padrão **WCAG 2.1 nível AA** (obrigatório para prestação de contas da Lei Rouanet).
* **Entregável:** Biblioteca componentizada no Figma com Auto Layout nativo, variáveis organizadas e documentação pronta para o Diogo (TI).
* **Investimento:** **R$ 6.800,00**
* **Prazo:** **8 dias úteis**

#### Bloco C — Layouts de Templates Mestres (7 Modelos Desktop)
* **Escopo dos 7 Moldes Estruturais:**
  1. **Home:** Banner de entrada nobre, destaques editoriais, atalhos de áreas urbana/rural e vitrine de entrada do projeto Rouanet.
  2. **Página de Subcategorias:** Listagem geral com barra de filtros dinâmicos unificados (gastronomia, hotelaria, compras, etc.).
  3. **Página Individual Padrão (Comercial / Serviços):** Ficha de estabelecimento com galeria, mapa estático, dados de contato e horários.
  4. **Página de Distrito / Região:** Molde dinâmico para os 12 distritos de Caxias do Sul.
  5. **Hub Patrimônios, Marcos e Lendas (Área Nova Rouanet):** Centro da pesquisa cultural com linha do tempo, galeria histórica e contextualização territorial.
  6. **Página Mapa Interativo (Nível Base):** Interface cartográfica com sistema de pins categorizados e card/sheet lateral para visualização rápida.
  7. **Página de Notícias / Artigos:** Layout editorial com categorização e paginação.
* **Entregável:** Telas em alta fidelidade no Figma organizadas em fluxos de navegação.
* **Investimento:** **R$ 8.900,00** *(equivalente a R$ 1.271,43 por template mestre)*
* **Prazo:** **14 dias úteis**

#### Bloco D — Adaptação Responsiva (Mobile-First)
* **Escopo:**
  * Adaptação dedicada dos 7 templates mestres para viewport mobile (390px).
  * Otimização de toque (touch targets mínimos de 44px), gavetas inferiores (bottom sheets) e menus simplificados para turismo em trânsito.
  * Comportamento fluído de grid que resolve naturalmente resoluções intermediárias (tablets).
* **Entregável:** Pranchas mobile integradas a cada fluxo correspondente no Figma.
* **Investimento:** **R$ 4.500,00**
* **Prazo:** **Integrado ao Bloco C (+3 dias úteis)**

---

### 4. Resumo Financeiro & Condições Comerciais

| Bloco | Descrição do Bloco | Investimento | Prazo Estimado |
| :--- | :--- | :--- | :--- |
| **Bloco A** | Estudo, Diagnóstico UX/IA & Direção de Arte | R$ 4.200,00 | 6 dias úteis |
| **Bloco B** | Design System & Tokens (Figma → React) | R$ 6.800,00 | 8 dias úteis |
| **Bloco C** | 7 Templates Mestres (Desktop) | R$ 8.900,00 | 14 dias úteis |
| **Bloco D** | Adaptação Responsiva Mobile (7 Templates) | R$ 4.500,00 | +3 dias úteis |
| **SUBTOTAL** | **Contratação Fracionada / Por Bloco** | **R$ 24.400,00** | **28 dias úteis** |
| **PACOTE** | **CONTRATAÇÃO INTEGRADA (A + B + C + D)** | **R$ 22.800,00** | **~25 dias úteis** |

* **Layout Adicional Avulso:** **R$ 1.600,00** por novo template mestre (Desktop + Mobile inclusos).
* **Rodadas de Ajustes:** Estão inclusas **2 rodadas consolidadas de revisão** por bloco. Rodadas adicionais ou excedentes: **R$ 1.100,00** por rodada ou **R$ 180,00/hora técnica**.

---

### 5. Delimitação Clara de Responsabilidades (Fora de Escopo)

Para segurança das partes e conformidade do orçamento:
* **Não inclui:** Desenvolvimento de código front-end (a cargo do Diogo / TI do cliente).
* **Não inclui:** Programação lógica de APIs do mapa (Leaflet/Mapbox/Google Maps) — apenas o design de UI/UX do mapa está incluso.
* **Não inclui:** Redação de textos, pesquisa histórica ou curadoria patrimonial (a cargo do projeto cultural/proponente).
* **Não inclui:** Produção fotográfica ou tratamento manual individual do acervo legado.
* **Não inclui:** Redesenho do painel de administração (CMS).
* **Não inclui:** Redesenho das páginas de Agenda e do fluxo de notícia individual legado.
* **Não inclui:** Criação de logotipo, identidade institucional ou manual de marca do Guia.

---

### 6. Definição dos Pontos de Atenção (Item 6 do Briefing da Soul)

* **6.1 A página individual pode não ser um layout só:**  
  * *Solução Base:* O escopo prevê 1 molde flexível que atende o comércio geral.  
  * *Opcional Recomendado:* Caso a curadoria cultural exija uma ficha técnica patrimonial profunda (com linha do tempo e tombamento), a inclusão do **8º Template Dedicado (Detalhe Rouanet)** é orçada como aditivo por **+ R$ 1.600,00** (Desk + Mob).
* **6.2 Complexidade do Mapa Interativo:**  
  * *Solução Base:* Interface com mapa base, pins categorizados e card/sheet de detalhe rápido lateral.  
  * *Variação Avançada:* Se for exigido no design a roteirização interativa com múltiplos pontos sequenciais (roteiro turístico passo a passo), aditivo de **+ R$ 2.400,00**.
* **6.3 Herança Visual do Guia:**  
  * Respeitaremos a essência cromática do Guia atual, ajustando apenas o contraste para atingir aprovação no teste WCAG 2.1 AA da Rouanet.
* **6.4 Sincronização com o Diogo (TI / React):**  
  * Realizaremos uma reunião prévia de alinhamento de 45 minutos antes do Bloco B para validar convenções de classes (Tailwind, CSS Modules ou Styled Components) e tokens no Figma Dev Mode.
* **6.5 Acervo Heterogêneo de Imagens:**  
  * O design utilizará containers com proporções travadas (`aspect-ratio`), máscaras e overlays semitransparentes para que fotos antigas ou de resoluções distintas não quebrem o alinhamento das grades.
* **6.6 Acessibilidade e Segurança na Prestação de Contas:**  
  * Entrega orientada às diretrizes de acessibilidade pública para evitar qualquer glosa ou questionamento técnico pelo Ministério da Cultura.

---

### 7. Ferramentas, Formato e Disponibilidade

* **Ambiente de Trabalho:** Figma (com acesso completo para Soul Branding e para o Diogo no Figma Dev Mode).
* **Disponibilidade:** Início em até **5 dias úteis** após a aprovação formal.
