# Shared Preprocessing Tools

## Overview
Utilities dan tools yang digunakan bersama untuk preprocessing dataset Smart Home IoT menjadi format yang cocok untuk smart door authentication analysis.

## Scripts

### data_loader.py
- Load dataset dari CSV
- Basic data validation
- Missing value handling

### smart_door_adapter.py
- Mapping IoT data ke smart door context
- Device_Type filtering untuk "Smart Lock"
- Feature extraction untuk door analysis

### time_features.py
- Timestamp processing
- Indonesian timezone conversion (UTC to WIB)
- Working hours extraction (8-17 WIB)
- Weekend/weekday classification

### anomaly_labeler.py
- Label preprocessing
- Normal/Anomaly mapping
- Indonesian context anomaly rules

## Usage
```python
from shared.preprocessing import data_loader, smart_door_adapter

# Load and preprocess data
data = data_loader.load_iot_dataset()
door_data = smart_door_adapter.convert_to_door_context(data)
