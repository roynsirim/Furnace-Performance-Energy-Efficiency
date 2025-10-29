# Furnace-Performance-Energy-Efficiency-
Predictive model built to analyse energy efficiency, predicting the worst performing furnace within a fleet of furnaces.

Objectives:

**Primary Objective**:
Identify specific furnaces that are underperforming in terms of energy efficiency to target for improvement initiatives. This could lead to maintenance, or process optimisation.

**Analytical Objectives**:
**Rank furnaces by energy efficiency**: Clearly determine which furnaces exhibit the highest kWh/tonne values (Worst Performer).
**Investigate potential correlations**: Explore if kWh/tonne correlates with Tonnes/hour or kWh/hour to understand contributing factors to poor performance. For example, is a furnace consuming more energy per tonne because it's running slower, or because it's inherently less efficient?
**Quantify the performance gap**: Determine the difference in kWh/tonne between the worst and best-performing furnaces.

**Key Metrics and Their Relevance**:
**kWh (energy consumed)**: Total energy used. This is a primary cost driver.
**Tonnes (output)**: Total material processed. This is a primary measure of productivity and revenue generation.
**Cycle time (hours)**: Duration of one operational cycle. Important for understanding throughput and potential bottlenecks.
**kWh per tonne (Energy Efficiency Metric)**: This is our primary metric of interest. It directly measures how much energy is required to produce one tonne of output.
**Relevance**: A higher kWh/tonne indicates lower energy efficiency and higher energy cost per unit of production. This is the direct measure for identifying our "worst performing" furnace from an energy perspective.
**Tonnes per hour (Productivity Metric)**: Measures the rate of production.
**kWh per hour (Energy Consumption Rate Metric)**: Measures the rate at which energy is consumed.
**Relevance**: This helps us understand the intensity of energy use. A high kWh/hour doesn't necessarily mean poor energy efficiency if productivity (Tonnes/hour) is also very high. However, if kWh/hour is high while Tonnes/hour is low, it points to significant inefficiency.

What **"Poor Performance"** Means in Measurable Terms:
For this analysis, "poor performance" is primarily defined by:
**High kWh/tonne**: A furnace is considered a poor performer if its kWh/tonne value is significantly higher than the average kWh/tonne across all furnaces, or if it consistently ranks among the highest values. We might define a threshold, e.g., "any furnace with kWh/tonne greater than the 75th percentile" or "the top 2 furnaces with the highest kWh/tonne."

**Expected Insights from the Analysis**:
**Identification of the Worst-Performing Furnace(s)**: A clear ranking of furnaces by kWh/tonne, pinpointing the primary target(s) for improvement.
**Quantification of the Energy Efficiency Gap**: Understanding how much more energy the worst performer(s) use per tonne compared to the best performer(s).
**Potential Root Causes (Hypotheses**): Insights might suggest why a furnace is performing poorly. For example:
Is high kWh/tonne due to low Tonnes/hour (e.g., slow cycle times, frequent downtime)?
Is it due to inherently high kWh/hour even at normal productivity (e.g., older equipment, insulation issues, inefficient heating elements)?
Are there specific operating conditions (e.g., higher temperatures, different material batches) that lead to worse efficiency for certain furnaces?
**Foundation for Recommendations**: The analysis will provide the evidence needed to recommend specific actions, such as:
Targeted maintenance for inefficient furnaces.
Process optimisation (e.g., adjusting cycle times, pre-heating procedures).
