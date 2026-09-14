# Matriz Funcional de Templates Mestres

**Projeto:** Patrimônios, Marcos e Lendas — Guia de Caxias do Sul  
**Escopo Base:** 7 Templates Mestres (Desktop + Mobile)  
**Extensão Opcional:** 8º Template dedicado (Patrimônio Histórico Individual)

---

## Tabela Comparativa de Templates

| # | Identificador do Template | Função no Portal | Componentes Críticos do Layout | Reutilização no Legado |
| :-: | :--- | :--- | :--- | :--- |
| **01** | `TPL_HOME` | Portal de entrada principal | Hero Banner, Vitrine de Destaques, Atalho Áreas Urbana/Rural, Chamada Nobre Rouanet, Carrossel de Distritos, Bloco Notícias Recentes. | Exclusivo da raiz do portal |
| **02** | `TPL_SUBCATEGORIAS` | Listagem categorizada com filtros | Barra lateral/gaveta de filtros facetados (bairro, faixa de preço, tags), Grid de Cards modulares, Barra de ordenação e Paginação. | Replicado em todas as subcategorias (ex: Compras, Gastronomia, Hospedagem) |
| **03** | `TPL_DETALHE_PADRAO` | Página individual de atrativo comercial | Galeria de fotos com lightbox, ficha de contatos (WhatsApp, site, tel), mapa de localização, horários, comodidades e cards de "Veja Também". | Replicado em centenas de empresas cadastradas |
| **04** | `TPL_DISTRITO` | Página individual de cada um dos 12 distritos | Hero institucional com história e mapa do distrito, carrossel de atrativos locais, gastronomia típica, rotas e lista de patrimônios da região. | Replicado identicamente nos 12 distritos |
| **05** | `TPL_HUB_PATRIMONIOS` | O epicentro cultural do projeto Rouanet | Cabeçalho editorial histórico, navegação por eixos temáticos (Marcos, Lendas, Patrimônios Tombados), chamada para o Mapa e acervo em destaque. | Centralizador de todo o conteúdo cultural novo |
| **06** | `TPL_MAPA_INTERATIVO` | Interface cartográfica de exploração | Canvas de mapa (Google Maps / Mapbox), seletor de categorias/filtros no topo, pins customizados e Sheet/Drawer lateral retrátil com preview do atrativo. | Espaço novo de navegação geoespacial |
| **07** | `TPL_NOTICIAS` | Listagem editorial do portal | Grade de cards de notícias, destaque principal da semana, filtro por editorias e paginação. | Área de notícias do site |
| **08\*** | `TPL_DETALHE_PATRIMONIO` *(Opcional / Aditivo)* | Detalhamento dedicado de Patrimônios e Lendas | Bloco narrativo editorial de alta imersão, linha do tempo histórica, acervo de fotos históricas vs atuais, créditos de pesquisa e citação Rouanet. | Exclusivo da área cultural Rouanet (não polui o comércio) |

---

## 💡 Racional da Separação do Template 03 vs 08 (Ponto 6.1 do Briefing)

* **O Template 03 (Comercial/Serviço)** tem como métrica de sucesso a **rapidez de contato e conversão**: quem procura um restaurante precisa de endereço rápido, cardápio, horário de pico e botão de WhatsApp.
* **O Template 08 (Patrimônio Histórico)** tem como métrica de sucesso a **profundidade cultural e prestação de contas Rouanet**: o visitante quer ler a lenda, entender o contexto do início do século XX, ver fotos de arquivo e compreender o valor arquitetônico.

*Tratar os dois no mesmo template gera uma interface Frankenstein: ou o restaurante fica com blocos vazios e pesados, ou o patrimônio cultural perde seu espaço nobre.*
