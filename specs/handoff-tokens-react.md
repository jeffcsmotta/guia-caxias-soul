# Especificação de Handoff Técnico: Figma → React

**Destinatário Técnico:** Diogo (Líder de TI / Front-End React do Cliente)  
**Autor UI/UX:** Jefferson Motta  
**Objetivo:** Garantir alinhamento semântico 1:1 entre os componentes desenhados no Figma e o código React a ser desenvolvido.

---

## 1. Arquitetura de Design Tokens

O Bloco B (Design System) fornecerá tokens padronizados em JSON/CSS Variables que podem ser injetados diretamente em **Tailwind CSS v4**, **CSS Modules** ou qualquer biblioteca de estilização que o Diogo escolher:

```json
{
  "color": {
    "brand": {
      "primary": "#8B1E2D",
      "primary-hover": "#6E1420",
      "secondary": "#C59B27",
      "accent": "#2B4C7E"
    },
    "surface": {
      "default": "#FFFFFF",
      "subtle": "#F8F9FA",
      "muted": "#EDF0F2",
      "inverse": "#1A1D20"
    },
    "text": {
      "primary": "#1A1D20",
      "secondary": "#596066",
      "muted": "#8C959E",
      "inverse": "#FFFFFF"
    }
  },
  "spacing": {
    "1": "4px",
    "2": "8px",
    "3": "12px",
    "4": "16px",
    "6": "24px",
    "8": "32px",
    "12": "48px",
    "16": "64px"
  },
  "radius": {
    "sm": "4px",
    "md": "8px",
    "lg": "16px",
    "pill": "9999px"
  }
}
```

---

## 2. Padrão de Nomenclatura e Componentização React

Todos os componentes no Figma serão construídos com propriedades equivalentes às `props` de um componente React moderno:

### Exemplo: `<CardAtrativo />`
* `variant`: `'comercial'` | `'patrimonio'` | `'distrito'`
* `size`: `'default'` | `'compact'` (usado em listas densas e no mapa)
* `hasBadge`: `boolean` (indica selo Rouanet ou categoria)
* `state`: `'default'` | `'hover'` | `'loading'` (Skeleton) | `'disabled'`
* `onClick`: Handler de navegação

---

## 3. Conformidade WCAG 2.1 AA (Acessibilidade)

Para tranquilidade do Diogo e do proponente na prestação de contas da Lei Rouanet:
1. **Razão de Contraste:** Mínimo de 4.5:1 para texto normal e 3:1 para textos grandes (acima de 18pt ou 14pt negrito) em relação ao fundo.
2. **Estados de Foco:** Cada componente interativo terá um anel de foco visível (`:focus-visible`) mapeado para navegação via teclado.
3. **Áreas de Toque Mobile:** Mínimo de 44x44px em todos os botões e seletores da versão mobile.
4. **Semântica Estrutural:** Indicação clara de hierarquia de títulos (`h1`, `h2`, `h3`) para que o Diogo utilize as tags HTML5 corretas para leitores de tela.
