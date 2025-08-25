# Data Visualization with Matplotlib and Seaborn Walkthrough
Hands-on series: master 2D/3D Matplotlib and Seaborn to turn data into decisions. Visualize bike-rental demand for ABC Bikes and uncover income drivers from survey data. 12 milestone notebooks teach styling, annotations, and statistical relationships—fast, clear, publication-ready.     
liveProject [Data Visualization with Matplotlib and Seaborn](https://www.manning.com/liveprojectseries/data-visualization-ser)     
Walkthrough [Data Visualization with Matplotlib and Seaborn](https://www.oreilly.com/videos/data-visualization-with/10000MNLW202502/)    

## About the series

This repo hosts a 3-project, 12-milestone walkthrough that turns real datasets into actionable visuals with Matplotlib (2D & 3D) and Seaborn. You’ll play the data analyst for **ABC Bikes** (rental demand across time, weather, and season) and **Global Consensus Bureau** (income drivers like education, hours, gender, age).&#x20;

## Projects & milestones

* **Project 1 — 2D Plotting with Matplotlib (4 milestones).** Build line/scatter, grouped bars, multi-subplot layouts, and seasonal distributions; annotate insights and export publication-quality figures. Examples include hourly rental trends and a four-season violin-plot comparison.

! [Number of Bikes Rented at a day](docs/images/P1_M2.pdf)

* **Project 2 — 3D Plotting with Matplotlib (4 milestones).** Use `mplot3d` to visualize multiple variables at once (e.g., temperature × hour × rentals), adjust rcParams, label points, and control projections.

* **Project 3 — Plotting with Seaborn (4 milestones).** Clean census survey data and explore categorical, numerical, and pairwise relationships with Seaborn (bar/cat, joint/kde, pair plots), including theming and palettes for clear storytelling. 

Each milestone includes a **solution notebook** and produces concrete deliverables (PDF/PNG/HTML) to showcase results.

## What you’ll practice

* Matplotlib figure anatomy (Figure/Axes), subplots/GridSpec, annotations, legends, color maps, and high-DPI export.
* 3D scatter/surfaces with `mplot3d`, axis control, labeling, and rcParams tuning.&#x20;
* Seaborn theming, palettes, categorical/relational/regression grids, joint/kde/rug, and pairwise exploration.

## Prerequisites

You’ll be comfortable with intermediate Python/Pandas and Jupyter; basic Matplotlib familiarity helps. Seaborn milestones assume you can set themes/palettes and tweak plot rcParams.

## Navigate the repo

* Milestones: open the solution notebook in `notebooks/P{project}_M{milestone}.ipynbn`.
* Deliverables: each milestone specifies format and naming (e.g., PDFs at 300 dpi, or HTML exports).

*Tip:* If you’re skimming, begin with Project 1 Milestone 2 (hourly rentals) to see quick wins, then jump to the Seaborn numerical milestone for joint/kde insights.
