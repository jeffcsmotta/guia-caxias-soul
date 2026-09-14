# Briefing Original — Soul Branding (Setembro / 2026)

**Projeto:** Patrimônios, Marcos e Lendas — Guia de Caxias do Sul  
**Executor:** Jefferson — freelancer de UI/UX  
**Solicitante:** Soul Branding  
**Contato:** Mateus — Soul Branding  
**Cliente final:** Guia de Caxias do Sul — projeto via Lei Rouanet  
**Objetivo:** Dar contexto suficiente para o orçamento  

---

> *Jefferson, este documento não é o briefing de execução. Ele existe para você conseguir orçar com segurança. O briefing de execução vem depois, com o escopo fechado e os pontos do item 6 resolvidos.*

### 1. O contexto antes do escopo
O cliente está estruturando um projeto pela Lei Rouanet voltado a Patrimônios, Marcos e Lendas de Caxias do Sul. O centro do projeto — e do orçamento do cliente — é a pesquisa, atualização e ampliação desse conteúdo histórico e cultural.
O design entra por um motivo específico: esse conteúdo precisa de um lugar à altura dentro do Guia. Hoje não existe. Vai existir uma área nova, com mapa interativo, e ela não pode nascer dentro de uma apresentação visual defasada.
Em paralelo, a equipe de TI do cliente (Diogo) está propondo migrar o front-end do site para React, mantendo banco de dados, painel de gerenciamento e conteúdos existentes. A migração é a janela: se o front vai ser reescrito de qualquer forma, é o momento de definir a linguagem visual que ele vai carregar.

**Três coisas que este projeto NÃO é:**
Não é site novo. Não é reformulação completa do Guia. Não é redesenho de todas as páginas existentes.
O que ele é: modernizar a apresentação da nova área de história e cultura e, no mesmo movimento, criar padrões visuais replicáveis que possam ser aplicados gradualmente ao restante do Guia — sem que isso vire um projeto de refação total.

*Essa é a régua para qualquer decisão de escopo. O que estende padrão, entra. O que vira refação, fica fora.*

---

### 2. Estrutura atual do site
Arquitetura de hoje, conforme mapa enviado pelo cliente:
```
HOME
├── Banner
├── Destaques
├── Área Urbana
│    └── Categorias → Subcategorias → Páginas individuais
├── Área Rural
│    └── Categorias → Subcategorias → Páginas individuais
├── Conheça os Distritos e Regiões   (12 distritos/regiões)
│    └── Detalhamento do distrito → Página individual
├── Patrimônios, Marcos e Lendas          ← ÁREA NOVA
│    ├── Página geral
│    └── Página individual / detalhamento
├── Notícias → Página individual da notícia
└── Agenda → Página individual / detalhamento
```
*Atenção ao volume. São 12 distritos/regiões, duas grandes áreas (urbana e rural), múltiplas categorias e subcategorias, e um número indefinido de páginas individuais. Nenhuma dessas páginas é desenhada uma a uma. Todo layout deste escopo é template replicável, alimentado pelo painel de gerenciamento existente. O orçamento é por template, não por página.*

---

### 3. Escopo a orçar
Estrutura proposta pelo cliente: 1 estudo + 1 sistema de operação + 7 layouts + adaptação responsiva.

* **Bloco A — Estudo (1):** Diagnóstico do site atual + pesquisa de referências e benchmarking de interface, experiência de usuário e tendências de navegação. Inclui revisão da arquitetura da informação e da experiência de navegação, sem reconstruir tudo.
* **Bloco B — Sistema de operação / identidade visual digital (1):** Tipografia, botões, cards, ícones, filtros, padrões de imagem, grid, espaçamentos e estados (hover, ativo, desabilitado, carregando, vazio). Formato biblioteca de componentes/tokens para React.
* **Bloco C — Layouts (7):**
  1. Home
  2. Página de subcategorias
  3. Página individual / detalhamento
  4. Página de distrito / região
  5. Patrimônios, Marcos e Lendas (Área nova Rouanet)
  6. Página mapa
  7. Página de notícias
* **Bloco D — Adaptação responsiva:** Desktop + mobile para os 7 layouts.

---

### 4. Fora do escopo
* Programação e implementação front-end (responsabilidade do Diogo / TI do cliente)
* Desenvolvimento do mapa interativo — o design da interface entra, a implementação não
* Produção de conteúdo, textos, pesquisa histórica e curadoria (responsabilidade do projeto Rouanet)
* Produção fotográfica
* Redesenho do painel de gerenciamento / CMS
* Redesenho das páginas de Agenda e do fluxo de notícia individual
* Marca, logotipo ou identidade institucional do Guia

---

### 5. Como queremos receber o orçamento
* Valor por bloco (A, B, C e D separados) e valor unitário por layout adicional
* Prazo por bloco e prazo total
* Rodadas de ajuste incluídas por entrega, e valor da rodada excedente
* Ferramenta de trabalho e entrega — Figma
* Nível de documentação de handoff para a equipe de React
* Declaração de premissas e disponibilidade

---

### 6. Pontos de atenção que precisam de definição
* **6.1 A página individual pode não ser um layout só:** Patrimônio histórico vs comércio gastronômico/hospedagem.
* **6.2 O mapa interativo é o item de maior risco:** Base, pins, camadas ou filtros.
* **6.3 Herança visual:** Brandbook existente vs redefinição digital.
* **6.4 Dependência do cronograma do React:** Sincronização prévia com Diogo.
* **6.5 Acervo de imagens:** Qualidade e tratamento de proporção.
* **6.6 Acessibilidade:** Exigência WCAG para prestação de contas Rouanet.
