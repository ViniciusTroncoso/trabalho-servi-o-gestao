# Personas & Papéis de Compra — Parques da Disney

Página visual interativa desenvolvida para o trabalho de **Gestão de Serviços** (pós-graduação). Mapeia os públicos envolvidos no processo de compra de uma viagem aos Parques da Disney, suas motivações e ações estratégicas para ampliar o interesse de cada público.

🔗 **Deploy:** _(adicione a URL da Vercel aqui após o deploy)_

---

## 📌 Sobre o trabalho

A premissa central é a **dissociação dos papéis de compra**: numa decisão de serviço como a viagem à Disney, quem *deseja* raramente é quem *paga*, e quem *paga* nem sempre é quem mais *usa*. O material analisa essa fragmentação através de personas reais-ísticas, com recorte para o público **brasileiro** (top-5 mercado emissor internacional).

### Conteúdo da página

| Seção | O que mostra |
|-------|--------------|
| **01 · Demografia** | 4 gráficos (Chart.js): idade, % com crianças, renda e origem internacional |
| **02 · Perfil subjetivo** | Lado psicográfico do público — valores, desejos, medos e identidade |
| **03 · Matriz de papéis** | Quem inicia / influencia / decide / compra / usa entre as 6 personas |
| **04 · Personas** | 6 fichas detalhadas (família Andrade + Disney Adult) |
| **05 · Cenários** | Contraste Skip-Gen (papéis em 4 pessoas) vs Disney Adult (todos em 1) |
| **06 · Motivações** | O que move cada público a escolher a Disney (intimidade de marca) |
| **07 · Tangibilização** | 10 evidências físicas/sensoriais + 7 propostas de melhoria |
| **08 · Hiatos de serviço** | Modelo de gaps: conhecimento, padrão, entrega e comunicação |
| **09 · Ações** | 6 propostas estratégicas para ampliar o interesse por público |

---

## 🎭 Os 5 papéis de compra

1. **Iniciador** — quem planta a semente do desejo (a criança / o fã)
2. **Influenciador** — interno (criança, cônjuge) e externo (creators, agentes, comunidade)
3. **Decisor** — quem bate o martelo (pais 25–49 ou avós)
4. **Comprador** — quem efetivamente paga (pais ou avós financiadores)
5. **Utilizador** — quem consome a experiência (todas as faixas etárias)

---

## 🛠️ Tecnologia

- HTML + CSS puro (sem build) — pronto para deploy estático
- [Chart.js 4.4](https://www.chartjs.org/) via CDN para as visualizações de dados
- Tipografia: Fraunces + Inter (Google Fonts)
- Responsivo e com suporte a `prefers-reduced-motion`

## 🚀 Como rodar localmente

Basta abrir o `index.html` no navegador — não há etapa de build.

```bash
open index.html
```

## ☁️ Deploy na Vercel

Projeto estático. Na Vercel:
1. **Add New → Project** → importe este repositório
2. Framework Preset: **Other**
3. Deixe build/output em branco → **Deploy**

---

## 📚 Fontes dos dados

Personas ilustrativas construídas sobre estatísticas reais de público (dados de mercado 2025):

- [MapZot — Walt Disney World Travel Behavior Demographics 2025](https://www.mapzot.ai/news/walt-disney-world-travel-behavior-demographics-2025/)
- [Springer — Who influences family tourism decisions](https://link.springer.com/article/10.1007/s11628-025-00579-1)
- [TravelAge West — The Kidfluence Effect on Travel](https://www.travelagewest.com/Travel/Family-Travel/the-kidfluence-effect-on-travel)
- [Travel Market Report — Grandparents driving multi-gen & skip-gen travel](https://www.travelmarketreport.com/retail-strategies/articles/multi-generation-skip-generation-grandparents-paying-family-travel-trend)
- [Pirates & Princesses — 'Disney Adult' numbers surge](https://piratesandprincesses.net/disney-adult-numbers-surge-as-families-face-higher-costs-at-disney-parks/)
- [MBLM — Making sense of the magic of Disney Parks (Brand Intimacy)](https://mblm.com/library/making-sense-of-the-magic-of-disney-parks/)
- [Rivo — Disney's Loyalty & Retention Strategy](https://www.rivo.io/blog/disney-loyalty-retention-strategy-complete-breakdown)
- [SurveySensum — Disney NPS & brand loyalty](https://www.surveysensum.com/blog/disney-nps)

> ⚠️ As personas (nomes, idades, cidades) são **ilustrativas/fictícias**, ancoradas nos dados estatísticos acima. Material acadêmico, sem vínculo oficial com The Walt Disney Company.
