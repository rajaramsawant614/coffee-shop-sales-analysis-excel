# Coffee Shop Sales — Business Insights

**Analysis period:** January–June 2023  
**Dataset:** 149,116 transactions  
**Currency:** USD

## Project overview

This report summarises the main patterns found in the coffee shop sales dataset. The analysis focuses on revenue, transaction activity, product categories, store performance, and trading hours. The goal is to turn the results into practical questions and actions for a store manager.

## Key performance indicators

| Metric | Result |
|---|---:|
| Total revenue | $698,812.33 |
| Units sold | 214,470 |
| Transactions | 149,116 |
| Average revenue per transaction | $4.69 |

## 1. Revenue trend

Revenue increased from **$81,677.74 in January** to **$166,485.88 in June**, a rise of approximately **104%**. June was the strongest month, while February was the only month with a month-over-month decline.

| Month | Revenue |
|---|---:|
| January | $81,677.74 |
| February | $76,145.19 |
| March | $98,834.68 |
| April | $118,941.08 |
| May | $156,727.76 |
| June | $166,485.88 |

**Business takeaway:** The business should check whether this growth came from more transactions, a higher average transaction value, price changes, product mix, or seasonal demand. Revenue growth alone does not explain the cause.

## 2. Store performance

Revenue was distributed fairly evenly across the three locations.

| Store | Revenue | Share |
|---|---:|---:|
| Hell's Kitchen | $236,511.17 | 33.8% |
| Astoria | $232,243.91 | 33.2% |
| Lower Manhattan | $230,057.25 | 32.9% |

The difference between the highest- and lowest-revenue stores was only **$6,453.92**. No location dominates overall sales.

**Business takeaway:** Compare store-level transaction counts, average transaction value, and hourly sales before changing staffing or inventory levels. Revenue alone does not show which store is more profitable.

## 3. Product category mix

Coffee and tea together contributed approximately **66.7% of total revenue**.

| Category | Revenue | Share |
|---|---:|---:|
| Coffee | $269,952.45 | 38.6% |
| Tea | $196,405.95 | 28.1% |
| Bakery | $82,315.64 | 11.8% |
| Drinking Chocolate | $72,416.00 | 10.4% |
| Coffee beans | $40,085.25 | 5.7% |

**Business takeaway:** Keep coffee and tea availability reliable, then review category-level units sold and average selling price. Lower-revenue categories may still be valuable if their margins are stronger, but cost data is needed to assess that.

## 4. Peak trading hours

The morning period was the strongest sales window. **10 AM** recorded the highest hourly revenue at **$88,673.39**. The 7 AM–11 AM period accounted for approximately **52.4% of total revenue**.

| Hour | Revenue |
|---|---:|
| 7 AM | $63,526.47 |
| 8 AM | $82,699.87 |
| 9 AM | $85,169.53 |
| 10 AM | $88,673.39 |
| 11 AM | $46,319.14 |

**Business takeaway:** Review staffing, preparation, and replenishment around the morning peak. Use store-specific hourly patterns before applying the same staffing plan to every location.

## 5. Day-of-week pattern

Monday recorded the highest daily revenue at **$101,677.28**, narrowly ahead of Friday at **$101,373.00**. Saturday was lowest at **$96,894.48**. The gap is relatively small, suggesting that revenue is broadly consistent across the week.

| Day | Revenue | Transactions |
|---|---:|---:|
| Monday | $101,677.28 | 21,643 |
| Friday | $101,373.00 | 21,701 |
| Thursday | $100,767.78 | 21,654 |
| Wednesday | $100,313.54 | 21,310 |
| Tuesday | $99,455.94 | 21,202 |
| Sunday | $98,330.31 | 21,096 |
| Saturday | $96,894.48 | 20,510 |

## 6. Top-selling products

By revenue, the leading products were:

1. Sustainably Grown Organic Large — $21,151.75
2. Dark chocolate Large — $21,006.00
3. Latte Regular — $19,112.25
4. Cappuccino Large — $17,641.75
5. Morning Sunrise Chai Large — $17,384.00

By quantity, Earl Grey Regular led with **4,708 units**, followed by Dark chocolate Large (4,668) and Morning Sunrise Chai Regular (4,643).

**Business takeaway:** Review availability and menu placement for high-performing items. Use both revenue and quantity when planning stock; the highest-revenue product is not necessarily the most frequently ordered.

## 7. Recommendations

1. Investigate the drivers of monthly growth by comparing transaction count and average transaction value.
2. Use hourly sales by store to plan staffing and product preparation around the morning peak.
3. Maintain availability of core coffee and tea products while reviewing the performance of smaller categories.
4. Track both revenue and units sold when deciding which products need more shelf or menu visibility.
5. Add cost, waste, discount, and operating-expense data in a future analysis to assess profitability.

## 8. Data limitations

The dataset contains sales information but does not include product costs, store operating expenses, customer identifiers, discounts, refunds, inventory levels, or staffing information.

As a result, this analysis measures **revenue and sales activity**, not profit, customer retention, promotion effectiveness, stockout rates, or staff productivity. The recommendations should be treated as areas to investigate, not proof of cause and effect.

---

*Prepared as part of an Excel data analysis portfolio project. Figures are based on the supplied dataset and may vary if the source data or calculation definitions are changed.*
