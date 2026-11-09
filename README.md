# Dashboard Demos

Three business dashboards you can click through, built with plain HTML, CSS and JavaScript.

**Try it now:** https://ebr042-git.github.io/Dashboard-Demos/

All data is made up. The names, products and numbers are invented, and no real company data is used.

---

## What is this?

I build reports and dashboards that help people at work make decisions. These three demos show that kind of work: what each screen shows, how people use it, and the rules behind it.

You can open them in any browser. There is nothing to install.

---

## 1. Supplier Comparison
**For:** the buying team.
**The problem:** a buyer gets quotes from several suppliers and must pick one for each item, fast and fairly.

![Supplier Comparison](screenshots/demo-supplier-comparison.png)

**What you can do**
- See every supplier's price for each item, cheapest first.
- Click a supplier to choose them.
- If you choose someone who is not the cheapest, the screen asks you to write why. The order cannot be created until you do.
- See how much you save compared to the most expensive quote.
- Create a purchase order for the suppliers you chose.

## 2. Sales Overview
**For:** managers who want the sales picture in one look.
**The problem:** sales numbers are spread over people, regions and months, and are hard to compare.

![Sales Overview](screenshots/demo-sales-overview.png)

**What you can do**
- See revenue, purchases and profit margin for the last 2 or 6 months.
- Compare salespeople, regions and top customers with simple bars.
- See each month's sales split by salesperson. Hover for exact numbers, and click a name in the key to hide or show it.

## 3. Trading Statistics
**For:** the sales and trading team.
**The problem:** they need to know which customers and products make money, for any period.

![Trading Statistics](screenshots/demo-trading-statistics.png)

**What you can do**
- Choose a date range, or a quick option like "This month" or "Last 12 months".
- Turn divisions on and off. All the totals update at once.
- Open a customer to see the products they bought, then open a product to see each vehicle sold, with its profit.
- Download the customer table as a CSV file.

---

## How it is built
- One HTML file. No libraries and no internet needed.
- The sample data is created inside the page, so it looks the same every time.
- Charts are drawn by hand as SVG images.
- Works on phones, and with the keyboard.

## About me
I'm a data analyst who turns business data into reports people can use. See also my Power BI project: [BOQ Budget vs Actual](https://github.com/YOUR-USERNAME/BOQ-Budget-vs-Actual)
