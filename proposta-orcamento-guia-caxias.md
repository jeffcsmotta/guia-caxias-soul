# Proposta Comercial e Posicionamento Estratégico
**Projeto:** UI/UX & Design System — Patrimônios, Marcos e Lendas (Guia de Caxias do Sul)  
**Solicitante:** Soul Branding (A/C Mateus Loreto)  
**Executor:** Jefferson Motta — Especialista em Produto Digital, UI/UX & Design Systems  
**Data:** Setembro / 2026  

---

## 1. Carta de Alinhamento e Resposta ao Mateus Loreto

> **Contexto de envio:** Esta mensagem pode ser enviada por e-mail ou no corpo da mensagem de apresentação, servindo como abertura do arquivo formal.

---

**Fala, Mateus. Tudo bem?**

Recebi e analisei minuciosamente o briefing de orçamento para a nova área e modernização do **Guia de Caxias do Sul**. 

Antes de abrir números, quero pontuar: a maturidade e a lucidez do documento de vocês são raras no mercado. Vocês mapearam exatamente as dores e os pontos nevrálgicos de um projeto que envolve a responsabilidade de uma chancela cultural (Lei Rouanet) e a transição tecnológica em paralelo conduzida pela TI (migração para React com o Diogo).

Compartilho integralmente da régua de vocês: **raciocínio antes de tela, visão de sistema e nada de refação desenfreada de páginas legadas.** O sucesso desta entrega não é apenas criar uma área cultural visualmente impactante, mas entregar um **Design System com tokens e componentes reutilizáveis** que o Diogo consiga traduzir diretamente em código, assegurando a escala sustentável do portal pelos próximos anos.

Para viabilizar a negociação da Soul com o cliente sem travar o processo, estruturei a proposta comercial exatamente como solicitado: **modular (Blocos A, B, C e D independentes)**, com prazos por etapa, governança de alinhamento com a TI e uma **tabela de variáveis claras** para pacificar os pontos do item 6 (como a distinção do 8º template e a complexidade do mapa).

Além disso, como você verá nas notas do Bloco A, já contemplei uma visão de **Design de Serviço e Arquitetura de Ecossistema**: estruturaremos os componentes para que, além do dever cultural da Rouanet, o Guia ganhe musculatura para futuras frentes de monetização, conexão com o trade turístico e parcerias locais, sem exigir retrabalho estrutural posterior.

Abaixo apresento o detalhamento completo para validação.

---

## 2. Escopo Orçado por Blocos

```
┌────────────────────────────────────────────────────────────────────────┐
│                        ESTRUTURA MODULAR DO PROJETO                    │
├─────────────────┬─────────────────┬──────────────────┬─────────────────┤
│  BLOCO A        │  BLOCO B        │  BLOCO C         │  BLOCO D        │
│  Diagnóstico &  │  Design System  │  7 Templates     │  Adaptação      │
│  Direção UX/IA  │  & Tokens React │  Mestres (Desk)  │  Mobile-First   │
└─────────────────┴─────────────────┴──────────────────┴─────────────────┘
```

### Bloco A — Estudo, Diagnóstico UX/IA & Direção de Arte
* **Objetivo:** Compreender as fricções de navegação do site atual, benchmark de portais culturais e turísticos contemporâneos, racionalização da arquitetura da informação e definição da direção estética.
* **Escopo:**
  * Diagnóstico crítico de usabilidade e fluxos do portal legado.
  * Benchmark referencial focado em critérios de experiência, navegação e acervo histórico.
  * Revisão da Arquitetura da Informação para a inserção harmoniosa da área Rouanet (Patrimônios, Marcos e Lendas) e do Mapa, sem romper o legado.
  * Mapeamento de oportunidades de **Design de Serviço**: estrutura de cards e pontos de contato preparados para ecossistema de parceiros e monetização.
* **Entregável:** Documento executivo de Diagnóstico, Arquitetura e Racional de Design (PDF/Notion).
* **Investimento:** **R$ 4.200,00**
* **Prazo de Execução:** 6 dias úteis.

---

### Bloco B — Sistema de Operação / Design System Digital (Figma → React)
* **Objetivo:** Construir o alicerce visual e técnico do Guia, permitindo que o Diogo (TI) implemente componentes consistentes em React sem adivinhação.
* **Escopo:**
  * **Design Tokens:** Escala tipográfica, paleta de cores (semântica e contraste), sistema de espaçamentos (Grid 8pt) e raios de borda.
  * **Componentes Fundamentais:** Botões, inputs, cards de listagem, tags/badges, ícones, seletores de filtros, breadcrumbs e cabeçalhos.
  * **Matriz de Estados:** Padrões para estados `Default`, `Hover`, `Active`, `Focus` (navegação por teclado), `Disabled`, `Loading` (Skeleton screen) e `Empty State`.
  * **Conformidade de Acessibilidade:** Critérios de contraste e legibilidade alinhados às diretrizes **WCAG 2.1 nível AA** (essencial para prestação de contas da Lei Rouanet).
* **Entregável:** Biblioteca componentizada no Figma utilizando Auto Layout nativo, variáveis organizadas e documentação de propriedades pronta para handoff.
* **Investimento:** **R$ 6.800,00**
* **Prazo de Execução:** 8 dias úteis (trabalhado em transição direta com o Bloco A).

---

### Bloco C — Layouts de Templates Mestres (Base: 7 Templates em Desktop)
* **Conceito Norteador:** Criação de fôrmas estruturais dinâmicas (templates) que recebem conteúdo do banco de dados existente, sem criação de páginas individuais avulsas.
* **Templates Inclusos:**
  1. **Home:** Estrutura de banner nobre, destaques editoriais, atalhos para áreas urbanas/rurais e vitrine de entrada para o projeto Rouanet.
  2. **Listagem de Subcategorias:** Template unificado com barra de filtros dinâmicos (para compras, gastronomia, vida noturna, etc.).
  3. **Página Individual Padrão (Comercial / Serviços):** Template enxuto e orientado a conversão/informação para gastronomia, hotelaria e serviços.
  4. **Página de Distrito / Região:** Template replicável para os 12 distritos de Caxias do Sul.
  5. **Hub Patrimônios, Marcos e Lendas:** O epicentro cultural do projeto Rouanet, destacando o acervo histórico, lendas e contextualização temporal.
  6. **Página Mapa Interativo (Nível Base):** Interface com base cartográfica (Google Maps / Mapbox), sistema de pins categorizados e card/sheet lateral para visualização rápida do atrativo.
  7. **Página de Notícias / Artigos:** Listagem editorial com categorização e paginação.
* **Entregável:** Telas em alta fidelidade no Figma organizadas em fluxo lógico de navegação.
* **Investimento:** **R$ 8.900,00** *(equivalente a ~R$ 1.270,00 por template mestre)*
* **Prazo de Execução:** 12 a 14 dias úteis.

---

### Bloco D — Adaptação Responsiva (Mobile-First)
* **Objetivo:** Garantir que a experiência de uso em dispositivos móveis seja prioridade de usabilidade, considerando o perfil de uso turístico em trânsito.
* **Escopo:**
  * Adaptação dedicada dos 7 templates mestres para viewport Mobile (390px).
  * Otimização de toque (touch targets mínimos de 44px), navegação por gavetas/sheets inferiores e simplificação de menus densos.
  * Regras de fluidez de grid que garantem a adaptação natural para resoluções intermediárias (tablets) via comportamento responsivo dos componentes.
* **Entregável:** Telas mobile integradas aos fluxos de entrega de cada template no Figma.
* **Investimento:** **R$ 4.500,00**
* **Prazo de Execução:** Desenvolvido de forma integrada ao Bloco C (+3 dias úteis ao cronograma final).

---

## 3. Resumo Financeiro e Condições

| Bloco | Descrição | Investimento | Prazo Estimado |
| :--- | :--- | :--- | :--- |
| **Bloco A** | Estudo, Diagnóstico UX/IA & Direção de Arte | R$ 4.200,00 | 6 dias úteis |
| **Bloco B** | Design System & Tokens (Figma → React) | R$ 6.800,00 | 8 dias úteis |
| **Bloco C** | 7 Templates Mestres (Desktop) | R$ 8.900,00 | 12 a 14 dias úteis |
| **Bloco D** | Adaptação Responsiva (Mobile-First) | R$ 4.500,00 | Integrado (+3 dias) |
| **TOTAL** | **Pacote Completo (Blocos A + B + C + D)** | **R$ 24.400,00** | **~25 a 28 dias úteis** |

> **Condição Especial de Contratação Integrada (A+B+C+D):**  
> Para fechamento do pacote completo dos 4 blocos em contrato único: **R$ 22.800,00** *(desconto de alinhamento e eficiência de fluxo contínuo).*

---

## 4. Tabela de Variáveis e Aditivos (Tratamento dos Pontos do Item 6)

Para que o orçamento da Soul junto ao cliente final seja flexível e seguro, definem-se as seguintes condições prévias:

| Item de Atenção | Premissa Adotada no Cenário Base | Custo Unitário de Aditivo / Expansão |
| :--- | :--- | :--- |
| **6.1 - 8º Template (Patrimônio Histórico Individual)** | O Cenário Base contempla 1 template de detalhe geral. Caso se confirme a separação entre o detalhe comercial e o detalhe histórico/Rouanet (altamente recomendado). | **+ R$ 1.600,00** *(Desktop + Mobile inclusos)* |
| **6.2 - Mapa Interativo Avançado** | O Cenário Base contempla mapa base com pins e card lateral. Se demandar roteirização dinâmica, rotas com múltiplos pontos ou cálculo de trajeto interativo no design. | **+ R$ 2.400,00** |
| **Breakpoint Tablet Dedicado** | O Cenário Base resolve tablet via regras de fluidez do Auto Layout. Se o cliente exigir formalmente pranchas gráficas estáticas adicionais para Tablet (768px/834px). | **+ R$ 2.800,00** *(para o conjunto dos layouts)* |
| **Template Adicional Avulso** | Qualquer novo template mestre que venha a ser solicitado fora dos 7 listados. | **+ R$ 1.600,00 / template** *(Desk + Mob)* |
| **Rodadas de Revisão** | Estão inclusas **2 rodadas consolidadas de ajustes** por bloco entregue. | **R$ 180,00/hora** ou **R$ 1.100,00** por rodada excedente |

---

## 5. Premissas Técnicas e Governança de Projeto

1. **Acessibilidade e Conformidade Rouanet (Item 6.6):**  
   Os componentes já serão desenhados observando o padrão de contraste e tipografia **WCAG 2.1 AA**, mitigando qualquer risco de apontamento em auditorias ou prestações de contas públicas.
2. **Sincronia com TI / React (Item 6.4):**  
   Prevemos uma reunião inicial de 45 minutos com o Diogo antes do início do Bloco B para validar a arquitetura de tokens (nomenclatura de variáveis, padrões do Tailwind ou CSS Modules que ele planeja utilizar no React).
3. **Acervo de Imagens e Fotografias (Item 6.5):**  
   Os cards e headers serão concebidos com tratamento dinâmico de sobreposição (overlays, máscaras e proporções flexíveis com `aspect-ratio`), garantindo harmonia visual mesmo que o acervo fotográfico legado tenha variações de resolução e iluminação.
4. **Fora de Escopo Confirmado:**  
   Não inclui codificação/desenvolvimento front-end, redação de textos ou pesquisa histórica, tratamento individualizado de banco de fotos, redesenho do painel administrativo (CMS) e criação de logotipo/branding institucional.
5. **Ferramenta de Entrega:**  
   Figma com permissões de visualização e inspeção de código para a equipe da Soul e da TI, organizado por páginas, fluxos e design tokens.
6. **Disponibilidade:**  
   Início imediato em até 5 dias úteis após aprovação e formalização.
