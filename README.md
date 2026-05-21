# EV Fleet Optimizer

Optimization project comparing electric, gas, and hybrid taxi fleet strategies under budget, fleet size, regional operating cost, and EV feasibility constraints.

## Project Overview

This project evaluates whether a taxi or rideshare-style fleet should invest in gas vehicles, electric vehicles, or a hybrid mix. The model compares vehicle options across Arkansas regions using assumptions for purchase cost, fuel cost, maintenance cost, insurance, operating mileage, EV feasibility, and expected revenue.

The goal is to recommend a fleet mix that maximizes projected profit while respecting business constraints.

## Business Problem

Fleet operators must balance upfront vehicle cost, operating expenses, regional demand, EV charging feasibility, and long-term profitability. EVs may reduce fuel and maintenance costs, but they can also have higher upfront costs and charging-related limitations.

This project uses optimization and scenario analysis to compare practical fleet strategies.

## Methods

- Cleaned and prepared vehicle and regional operating data.
- Estimated five-year ownership and operating costs.
- Compared EV, gas, and hybrid fleet strategies.
- Built an optimization model with budget, fleet size, and EV cap constraints.
- Evaluated results using projected profit, ROI, and fleet composition.

## Optimization Setup

**Decision Variable:**  
Number of each vehicle type assigned to each region.

**Objective:**  
Maximize projected five-year profit.

**Constraints:**

- Total fleet size limit
- Budget limit
- EV cap or EV feasibility limit
- Vehicle-region feasibility rules
- Minimum/maximum strategy requirements for scenario testing

## Tools

Python · pandas · NumPy · Jupyter Notebook · Optimization Modeling · Scenario Analysis · Data Visualization

## Key Takeaways

- Gas and hybrid strategies may outperform all-EV strategies when upfront EV costs dominate operating savings.
- EV feasibility depends heavily on regional charging assumptions and downtime penalties.
- Optimization provides a more defensible recommendation than choosing vehicles based only on fuel efficiency or purchase price.
- Scenario analysis helps compare profit-maximizing decisions against business preferences such as sustainability or vehicle variety.

## Repository Contents

```text
EV_Fleet_Optimizer/
├── Optimization_Project_Code.ipynb
└── README.md
