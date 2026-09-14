# Monorepo: Guia de Caxias do Sul — Nova Área Cultural (Lei Rouanet)

Repositório estruturado de documentação, especificações de design, alinhamento técnico e proposta comercial para o projeto **Patrimônios, Marcos e Lendas — Guia de Caxias do Sul**.

---

## 👥 Stakeholders & Atores do Projeto

| Papel | Nome / Entidade | Atribuição Principal |
| :--- | :--- | :--- |
| **Executor UI/UX & Design System** | **Jefferson Motta (Onira Labs)** | Arquitetura de IA/UX, Design System com Tokens para React, 7 Templates Mestres e Governança Visual. |
| **Agência Solicitante** | **Soul Branding (Mateus Loreto)** | Gestão da conta, planejamento estratégico e interlocução com o proponente. |
| **Engenharia de Front-End** | **Diogo / TI do Cliente** | Migração do portal para React, consumo dos tokens do Figma e integração com o banco de dados. |
| **Cliente Final / Fomento** | **Guia de Caxias do Sul** | Projeto aprovado sob a chancela da **Lei Rouanet** (Pesquisa e Valorização Histórica). |

---

## 📁 Estrutura do Monorepo

```
clientes/guia-caxias-soul/
├── README.md                                 # Este documento (visão geral e governança)
├── docs/
│   ├── briefing-soul-branding-original.md    # Briefing original na íntegra enviado pela Soul
│   ├── proposta-orcamento-guia-caxias.md     # Documento formal com a proposta comercial e prazos
│   └── design-service-vision.md              # Análise estratégica de Design de Serviço e Monetização
├── specs/
│   ├── matriz-templates.md                   # Detalhamento funcional dos 7 (+1) templates mestres
│   └── handoff-tokens-react.md               # Especificação de Design Tokens e convenções para o Diogo (React)
└── proposta/
    └── index.html                            # Visualizador interativo e proposta executiva web (App / Dashboard)
```

---

## 🎯 Princípios Norteadores do Escopo

1. **Régua de Ouro:** *"O que estende padrão, entra. O que vira refação, fica fora."*
2. **Templates em vez de Páginas:** Entrega de 7 moldes dinâmicos reutilizáveis, alimentados pelo banco de dados existente. Nenhuma página individual é desenhada de forma avulsa.
3. **Ponte Direta com Engenharia:** Design Tokens e Auto Layout no Figma estruturados para tradução direta em componentes React.
4. **Conformidade Legal:** Padrões de contraste e legibilidade atendendo **WCAG 2.1 nível AA** para segurança jurídica da prestação de contas da Lei Rouanet.
