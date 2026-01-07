# numpy-electricity-consumption-analysis

Electricity consumption analysis using Python and NumPy

## Objective
Analyze daily electricity consumption data and generate useful insights using NumPy arrays.

## Tools Used
- Python
- NumPy

## Data Assumptions
- 1 month = 30 days
- Daily electricity units consumed
- Data stored in a NumPy 1D array

## Analysis Performed
- Calculated total, average, median, minimum, and maximum consumption
- Identified high usage days (>9 units)
- Detected possible wastage days (usage > 20% above average)
- Estimated monthly electricity bill
- Identified best and worst consumption days

## Key Metrics
- Total Units Consumed: 224.7 units
- Average Daily Consumption: ~7.48 units
- Median Daily Consumption: ~7.05 units
- Minimum Consumption: 5.2 units
- Maximum Consumption: 10.5 units
- Estimated Monthly Bill: ₹1348.2

## Insights
- Most days have normal electricity usage
- Only a few days show very high consumption
- High usage days increase the total electricity bill
- Some days indicate possible electricity wastage
- Overall usage pattern is consistent

## Conclusion
This project demonstrates how NumPy can be used to analyze real-world electricity consumption data and generate actionable insights for cost optimization.
