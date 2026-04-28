# HEATpulse
We developed HEATpulse, a reproducible analysis pipeline designed to detect and characterize warm spells based on the Warm Spell Duration Index (WSDI). In this framework, warm spells are defined as periods of at least six consecutive days with daily maximum temperatures exceeding the station-specific 90th percentile (TX90).

The pipeline integrates data preprocessing, percentile-based threshold calculation, event detection, and statistical analysis across multiple weather stations. For each station, HEATpulse identifies warm spell events, computes their frequency and duration, and evaluates temporal trends using linear regression.

In addition to event detection, the framework generates a suite of visual outputs, including annual frequency trends, density-based temporal distributions, streamgraphs, and heatmaps of monthly exceedances. These outputs enable a comprehensive assessment of the spatiotemporal dynamics of extreme heat events across diverse climatic regions.

By combining standardized climate indices with an automated and scalable workflow, HEATpulse provides a robust tool for investigating the persistence and evolution of extreme heat under varying environmental conditions.
