# Arctic and Antarctic Sea Ice Extent Analysis

This project investigates historical trends and changes in sea ice extent across the Arctic and Antarctic using observational data and literature-based evidence. The report analyzes the structural, ecological, and climatic roles of sea ice and evaluates the effectiveness of current modelling approaches.

Available to view here: [Sea ice extent report](https://github.com/tjsladen/Sea-ice-extent-analysis/blob/6cfb148eb38071713609da010e6df6dc1ace5719/mthm507CA2.pdf)

📌 Project Summary

    Objective: Understand the temporal evolution and geographic variability of sea ice extent from 1979–2024.

    Methods Used:

        Generalized Additive Models (GAMs) for time series trend analysis.

        Raster plots of sea ice concentration (1990 vs 2023).

        Comparative model evaluation (CMIP5 vs CMIP6).

    Tools & Data:

        Data from the NSIDC and Met Office Climate Dashboard.

        GAM implementation with holdout validation.

        Literature review of climate models and satellite remote sensing techniques.

🧊 Key Findings

    Arctic sea ice extent shows a consistent long-term decline, more easily modelled using time-based trends.

    Antarctic trends are less predictable, likely influenced more by oceanic and atmospheric processes.

    GAM models demonstrated stronger predictive performance in the Arctic (R² ≈ 0.76) than in the Antarctic (R² ≈ 0.49 holdout).

    Seasonal variability is more pronounced in the Antarctic, while spatial losses are more region-specific in the Arctic (e.g., North Atlantic exposure).

    CMIP6 models offered limited improvement over CMIP5 in replicating Antarctic trends.

🔬 Limitations & Proposals

    Limitations:

        Data gaps due to satellite malfunctions.

        False positives in microwave detection of sea ice.

        Bias in global climate models for region-specific patterns.

    Proposed Solutions:

        Use of imputation for historical gaps.

        Regional models tailored to Arctic vs Antarctic conditions.

        Application of deep learning (e.g., CNNs) for model error correction and satellite image classification.

🎓 Academic Context

This report was developed as part of my Master's in Environmental Intelligence and demonstrates skills in:

    Climate data analysis

    Statistical modelling (GAMs)

    Scientific communication and reporting

