# Year-End Sales Strategy Dashboard

**A Tableau dashboard and data-storytelling deck that turn a marketplace's sales history into a year-end commercial strategy.**

The company is a marketplace specialized in collectibles. November and December bring in the highest revenue of the year, the season is short, and the marketing budget is limited. The question is not *whether* to invest, but *where*.

📄 **[View the deck (PDF, in Spanish)](year-end-sales-strategy.pdf)**

> The company name and product identifiers are anonymized.

---

## Business questions

The dashboard was built to answer four questions from the Marketing director:

1. Which days concentrate the highest revenue?
2. Which products sell the most? (Top 10)
3. Where are sales located, by state?
4. How fast do we deliver?

## The dashboard

One Tableau dashboard, four views:

| View | What it shows |
|---|---|
| Daily sales by month | Revenue per day across November and December 2021 |
| Top 10 products by sales | Revenue ranking by product |
| Sales by state / region | Map of sales density across Mexico |
| Delivery time | Number of orders by days to delivery |

## Key findings

- **Sales are spiky, not uniform.** The best day (December 20) reached MXN $5,593, and peak days outsell the slowest days by more than 15x. The peaks cluster in the second half of December.
- **A few products carry the catalog.** The top product generated MXN $128,005, more than double the second place (MXN $62,137).
- **Demand is concentrated in central Mexico.** Estado de México, CDMX, and Jalisco have the highest sales density; the north and south are under-penetrated.
- **Most sales happen without advertising.** Organic demand is strong, which leaves paid promotion as an untapped lever.
- **Delivery is fast.** Most orders arrive in 1–2 days.

## Recommendations

| Strategy | Action |
|---|---|
| **Timing** | Sync campaigns, budget, and inventory with the peak days, anticipating the second half of December |
| **Portfolio** | Guarantee stock of the top products; build bundles and use them as campaign hooks |
| **Coverage** | Reinforce the central core; run targeted campaigns in Nuevo León, Chihuahua, and other low-penetration states |
| **Advertising** | Advertise on the right days, products, and regions instead of evenly, and measure the incremental lift |

Proposed rollout: activate the dashboard as a live monitoring tool → run a December pilot on peak days → measure the advertising lift → scale what works.

## Tools

- **Tableau** for the dashboard and visual analysis
- **Data storytelling** for the executive presentation (context → question → evidence → strategy → roadmap)

## Repository contents

```
├── README.md
└── year-end-sales-strategy.pdf   <- executive deck (Spanish)
```

The Tableau workbook is not included because it embeds the raw sales data.

## Context and credits

- Academic team project (4 members), completed during the M.Sc. in Applied Artificial Intelligence at Tecnológico de Monterrey.
- I led the dashboard design and the visual storytelling of the deck.
- Data was provided by tutors for academic purposes. No original data is shared here
