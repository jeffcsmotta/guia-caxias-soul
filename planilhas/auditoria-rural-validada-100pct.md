# Auditoria Científica Rigorosa 100% — Nichos Rurais (Guia de Caxias do Sul)
**Data da Varredura:** 15/09/2026 | **Critério:** Inspeção HTTP direta + Ping de Domínio com descarte de Mapas/Emails  
**Universo Auditado:** 100% dos estabelecimentos mapeados nas 4 categorias rurais (150 empresas únicas)  
**Responsável:** Jefferson Motta — Onira Labs | **Objetivo:** Sustentação Técnica & Comercial com a Soul Branding  

> 🔴 **DADO CHAVE IRREFUTÁVEL:** **130 de 150 estabelecimentos (86.7%) NÃO POSSUEM canal web próprio funcional** no interior de Caxias do Sul.  
> - **118 empresas (78.7%)** não têm absolutamente nenhum site cadastrado (apenas ficha no Guia, WhatsApp e Instagram).  
> - **12 empresas (8.0%)** cadastraram um site no passado, mas o domínio expirou, caiu ou dá erro 404/SSL.  
> - **Apenas 19 empresas (12.7%)** possuem um site próprio funcional no ar respondendo HTTP 200.  

---

## 1. Resumo Executivo dos Dados Validados

| Classificação Técnica | Quantidade | % do Total | Conclusão Executiva |
|---|:---:|:---:|---|
| 🟢 **Confirmado com Site Ativo** | **19** | **12.7%** | Possuem site próprio no ar respondendo status HTTP 200. |
| 🔴 **Confirmado SEM Site** | **118** | **78.7%** | Ficha completa no Guia, dependência 100% do portal e WhatsApp. |
| ⚠️ **Site Cadastrado Fora do Ar / 404** | **12** | **8.0%** | URL cadastrada no Guia dá erro de DNS, 404, timeout ou SSL inválido. |
| 🟡 **Incerto (Cloudflare / Timeout)** | **1** | **0.7%** | Bloqueio de bot (403) ou timeout de rede (> 6s). |
| **TOTAL AUDITADO** | **150** | **100.0%** | **Varredura exaustiva sem amostragem.** |

---

## 2. ⚠️ Sites Cadastrados que Estão Mortos / Fora do Ar (12)
> Estabelecimentos que investiram em site no passado, mas a agência sumiu, o domínio expirou ou a hospedagem caiu.

| Estabelecimento | Categoria | URL Cadastrada | Diagnóstico Técnico | Distrito / Local | Link Guia |
|---|---|---|---|---|:---:|
| **Cantina Tonet Vinícola** | Gastronomia Rural / Vinhos | `cantinatonet.com.br` | `UNABLE_TO_VERIFY_LEAF_SIGNATURE` | Linha 40 | [Ficha](https://www.guiadecaxiasdosul.com/empresa/vinhos-sucos-e-espumantes/cantina-tonet-vinicola-449) |
| **Los Manos Grill** | Gastronomia Rural | `losmanosgrill.com` | `TIMEOUT` | Santa Lúcia | [Ficha](https://www.guiadecaxiasdosul.com/empresa/onde-comer/los-manos-grill-3144) |
| **Divina Lavanda** | Turismo Rural & Direto Produtor | `divinalavanda.com` | `ENOTFOUND` | Fazenda Souza | [Ficha](https://www.guiadecaxiasdosul.com/empresa/turismo-rural-e-compras-direto-do-produtor/divina-lavanda-3251) |
| **Hidrofert Produtos Mini Processados** | Turismo Rural & Direto Produtor | `hidrofert.com.br` | `ENOTFOUND` | Forqueta | [Ficha](https://www.guiadecaxiasdosul.com/empresa/turismo-rural-e-compras-direto-do-produtor/hidrofert-produtos-hidroponicos-e-mini-processados-3068) |
| **Orquidário e Pitayas Pebi** | Turismo Rural & Direto Produtor | `orquidario-pebi.negocio.site` | `404 Not Found` | Vila Seca | [Ficha](https://www.guiadecaxiasdosul.com/empresa/turismo-rural-e-compras-direto-do-produtor/orquidario-e-pitayas-pebi-2963) |
| **Casa Motter** | Vinhos, Sucos e Espumantes | `casamotter.com.br` | `404 Not Found` | Ana Rech | [Ficha](https://www.guiadecaxiasdosul.com/empresa/vinhos-sucos-e-espumantes/casa-motter-1016) |
| **Granja do Vale Vinhos e Uvas** | Vinhos, Sucos e Espumantes | `vinicolazanrosso.com.br` | `ERR_TLS_CERT_ALTNAME_INVALID` | Linha 40 | [Ficha](https://www.guiadecaxiasdosul.com/empresa/vinhos-sucos-e-espumantes/granja-do-vale-vinhos-espumantes-sucos-e-uvas-1777) |
| **Vinícola Arbugeri** | Vinhos, Sucos e Espumantes | `espumantesdosul.com.br` | `404 Not Found` | Forqueta | [Ficha](https://www.guiadecaxiasdosul.com/empresa/vinhos-sucos-e-espumantes/vinicola-arbugeri-2982) |
| **Vinícola Casa Onzi** | Vinhos, Sucos e Espumantes | `casaonzi.com.br` | `404 Not Found` | Galópolis | [Ficha](https://www.guiadecaxiasdosul.com/empresa/vinhos-sucos-e-espumantes/vinicola-casa-onzi-1717) |
| **Da Maria Produtos Coloniais** | Queijarias & Agroindústria | Google Maps redirect | `ENOTFOUND` | Fazenda Souza | [Ficha](https://www.guiadecaxiasdosul.com/empresa/agroindustrias-e-queijarias/da-maria-produtos-coloniais-2811) |
| **Granberg Alimentos** | Queijarias & Agroindústria | `granberg.com.br` | `503 Service Unavailable` | Vila Cristina | [Ficha](https://www.guiadecaxiasdosul.com/empresa/agroindustrias-e-queijarias/granberg-alimentos-3009) |
| **Queijaria Bolson & Camêlo** | Queijarias & Agroindústria | `queijaria-bolson-e-camelo.negocio.site` | `404 Not Found` | Criúva | [Ficha](https://www.guiadecaxiasdosul.com/empresa/agroindustrias-e-queijarias/queijaria-bolson-camelo-2739) |

---

## 3. Base de Dados Integral & Inteligência Territorial

> A base completa de 208 estabelecimentos (150 rurais + 58 urbanos) com status de site, WhatsApp, Instagram e Google Meu Negócio está estruturada nos arquivos:
> * 📄 **CSV para Google Sheets / Excel:** [`database-completa-guia-caxias.csv`](file:///c:/Users/ADM/onira-labs/clientes/guia-caxias-soul/planilhas/database-completa-guia-caxias.csv)
> * 📄 **JSON Canônico para Engenharia:** [`database-completa-guia-caxias.json`](file:///c:/Users/ADM/onira-labs/clientes/guia-caxias-soul/planilhas/database-completa-guia-caxias.json)
> * 🌐 **Painel Interativo de Visualização:** [`index.html`](file:///c:/Users/ADM/onira-labs/clientes/guia-caxias-soul/index.html)
