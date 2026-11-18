# 📦 Gel Pack Supply Chain Optimization | Linear Programming & Operations Analytics

### 🚀 Turning Complex Supply Chain Challenges into Data-Driven Decisions

How can a company efficiently manage **1,700 weekly shipments of temperature-sensitive products** while guaranteeing product availability, preventing stockouts, and minimizing operational costs?
This is the challenge behind the **Gel Pack Operational Planning Case Study**, inspired by a real-world logistics scenario. In this project, I developed a **four-month supply and demand optimization model** designed to balance inventory availability, procurement planning, transportation efficiency, and operational costs.

The challenge involved several critical constraints, including:

- ⏳ **Four-week freezing lead time** before gel packs become available for use.
- 📦 **Minimum two-week frozen safety stock** to prevent stockouts.
- 🚚 **Transportation capacity limitations** affecting procurement decisions.
- 💰 **Multiple operational cost components**, including procurement, transportation, handling, storage, and freezing.

---

## 🧠 My Approach: Linear Programming with Python

To solve this problem, I implemented a **Linear Programming (LP) model using Python and the PuLP library**. Linear Programming is a mathematical optimization technique that identifies the best possible solution by minimizing or maximizing an objective function while satisfying a set of constraints.

In this case, the objective was to:

> **Minimize total supply chain costs while ensuring operational feasibility, sufficient inventory availability, and uninterrupted order fulfillment.**

Using **PuLP**, I translated the business requirements into mathematical decision variables, an objective function, and operational constraints, allowing the model to determine an efficient procurement and inventory planning strategy.

The optimization framework focuses on:

1. **Procurement Planning:** Determining appropriate purchasing quantities and timing.
2. **Inventory Management:** Maintaining sufficient stock while accounting for freezing lead times.
3. **Transportation Optimization:** Incorporating shipping capacity and transportation costs.
4. **Cost Minimization:** Balancing procurement, handling, freezing, transportation, and storage expenses.

---

## 📊 Beyond Optimization: Turning Results into Business Insights

However, building an optimization model was only part of the project.

I wanted to go beyond finding a mathematically optimal solution and understand **what the results actually mean from an operational and business perspective**.

To achieve this, I extended the analysis by calculating KPIs like Work in Progress (WIP). 

WIP provides visibility into the gel packs moving through the freezing process before becoming available for shipment.

By combining optimization results with operational performance metrics, this analysis provides additional insights into:

- 📦 **Inventory Behavior:** Understanding how inventory evolves throughout the planning horizon.
- ❄️ **Work in Progress (WIP):** Monitoring gel packs undergoing the freezing process.
- 📈 **Operational Efficiency:** Evaluating how effectively resources support demand fulfillment.
- 🎯 **Decision-Making:** Translating mathematical outputs into actionable supply chain insights.

This analytical layer helps bridge the gap between **mathematical optimization and real-world operational decision-making**.

---

## 🎯 Project Vision

As an **Industrial Engineer pursuing a Master's in Applied Statistics with a focus on Data Science**, my goal was to combine **operations research, mathematical optimization, and data analytics** to approach a realistic business challenge.

This project represents something I strongly believe in:

> **Data analytics is not just about building models or generating numbers. It's about transforming complex business problems into actionable insights that drive smarter decisions and measurable value.**
