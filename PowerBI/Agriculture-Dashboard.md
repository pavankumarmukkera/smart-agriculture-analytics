# Smart Agriculture - Power BI Dashboard

## Objective
Explore agricultural productivity, crop yields,
farm distribution and water usage.

## Data Source
SampleData/agriculture-data.csv

The dataset is synthetic and intended for learning.

## Proposed Dashboard Pages

### 1. Farm Overview
- Total Farms
- Total Cultivated Area
- Total Crop Yield
- Total Water Consumption

### 2. Crop Performance
- Yield by Crop
- Average Yield per Hectare
- Crop Distribution

### 3. Regional Analysis
- Farms by Region
- Crop Yield by Region
- Water Usage by Region

## Example DAX Measures

### Total Yield
```dax
Total Yield = SUM(Agriculture[YieldTonnes])
```

### Total Area
```dax
Total Area = SUM(Agriculture[AreaHectares])
```

### Yield per Hectare
```dax
Yield per Hectare =
DIVIDE([Total Yield], [Total Area])
```

### Total Water Usage
```dax
Total Water Usage =
SUM(Agriculture[WaterUsageLitres])
```

## Important
Rename the imported table to Agriculture
before using these example DAX measures.

## Status
Dashboard design and example DAX only.
No completed PBIX report is included.
