<<<<<<< HEAD
=======
# CompoundMind

**This project is designed to teach financial literacy and the psychological joy of saving.**

Most personal finance apps assume users have a stable, fixed 9-to-5 salary and function as passive ledgers that simply record past expenses. CompoundMind challenges this assumption. Financial literacy is not about logging receipts—it is about understanding how daily habits, time, and interest shape future wealth.

Designed for individuals with irregular cash flows (such as students receiving daily allowances or users without fixed income schedules), this full-stack web application acts as an active financial educator. Instead of displaying a static balance, CompoundMind models future financial outcomes using explicit, rule-based savings mechanics to show exactly when dynamic financial goals can be reached under different behavioral choices.

## Features

### Timeline-Based Financial Modeling
A rule-driven engine that models daily balance changes based on irregular income events, expenses, savings rules, and user-defined goals. All projections, charts, and feedback are derived from this single source of truth.

### High-Yield Savings Modeling
Users select predefined savings vehicles (e.g., digital banks or structured savings programs) with encoded APR, compounding frequency, and configurable tax assumptions. The system computes realistic net growth over time rather than optimistic, untaxed projections.

### The “Cost of Wants” Engine
Teaches opportunity cost by evaluating impulse purchases and showing:
* **Delay Tracking:** How many days a financial goal is delayed.
* **Interest Loss:** How much future interest is forfeited.
* **Recovery Rate:** How much additional daily saving is required to recover.

### Goal-Based Financial Planning
Users define precise financial goals—ranging from small discretionary purchases to emergency fund targets. Completion dates and progress milestones dynamically adjust as habits or scenarios change.

### Savings Rate & Timeline Visualization
Interactive charts display balance trajectories, goal markers, and monthly savings consistency, allowing users to visually observe compounding and long-term stabilization.

### Irregular Cash-Flow Modeling
Built specifically for users without fixed salaries, the system demonstrates how disciplined daily habits—despite income uncertainty—can still generate meaningful financial outcomes through time and compounding.

## Tech Stack

* **Backend:** Go (Golang) with the Gin framework for deterministic financial modeling, scenario evaluation, and goal computation.
* **Frontend:** React.js (via Vite) for an intuitive, component-based user interface.
* **Data Visualization:** `react-chartjs-2` for rendering balance timelines and goal progress charts.
* **Data Storage:** Lightweight local or JSON-based persistence for the MVP (database-agnostic design).

## Scope

CompoundMind is an educational financial modeling tool, not a financial advisory system. It does not provide investment recommendations or predict real-world market behavior. Its purpose is to make the relationship between behavior, time, and money visible, measurable, and intuitively understandable.
>>>>>>> 4c01345e2654d3ebb89230ca26244820babdea9d
