
# SAFETY INCIDENT ANALYSIS - EXECUTIVE SUMMARY

## Project Overview
Analysis of 11 years (2014-2024) of UK workplace safety incidents from HSE RIDDOR data, 
with focus on construction industry hazards and severity prediction.

## Key Findings

### 1. Construction Industry Dominance
- **Most dangerous industry** for fatal incidents
- Top hazards: Falls from height (216 deaths), vehicle strikes (73), collapses (57)
- Fatalities remained steady even during COVID-19 lockdowns

### 2. Temporal Trends
- **COVID-19 Impact**: 27.4% drop in non-fatal incidents (2020/21)
- Construction continued as essential work
- Post-COVID recovery to ~61,000 incidents/year

### 3. Industry-Specific Hazard Profiles
- Chi-square test confirms: p < 0.000001 (highly significant)
- Each industry has distinct accident patterns
- Agriculture: machinery (30 deaths), drowning (17)
- Construction: height falls, electrical, collapses

### 4. Machine Learning Model Performance
- **Random Forest Classifier**: 72.4% accuracy
- **Fatal Detection Rate**: 90% (critical for prevention)
- **Top Predictors**: Incident count (53%), accident type (17%), industry (14%)

## Business Value for Construction
1. **Targeted Interventions**: Focus on fall protection systems
2. **Resource Allocation**: Prioritize height safety equipment
3. **Predictive Insights**: Identify high-risk scenarios early
4. **Benchmarking**: Compare safety performance against industry

## Model Limitations
- Class imbalance (fewer fatal cases)
- Limited contextual features (weather, time, worker demographics)
- Correlation, not causation

## Recommendations
1. Implement enhanced fall protection in construction
2. Increase safety inspections for high-risk combinations
3. Collect richer data (weather, experience, equipment age)
4. Deploy model for real-time risk assessment

---
**Dataset**: HSE RIDDOR (4,854 incident records)
**Time Period**: 2014/15 to 2024/25
**Model**: Random Forest (100 trees, balanced classes)
