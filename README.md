# Satellite Health Prediction Dataset

## About the Dataset
This dataset is designed for an imaginary study to detect faulty satellites and prevent communication interruptions. It demonstrates how confirmation bias can lead to misleading results by using a synthetic dataset with a well-developed storyline.

---

## Problem Statement
You are leading a team to conduct a study that enables the space agency to predict the health status of satellites based on telemetry data. This predictive capability will allow for proactive maintenance and ensure optimal performance in space missions.

---

## Stakeholders' Concerns
- **Accurately predicting satellite health** to minimize the risk of mission failures and optimize satellite usage.
- **Identifying critical factors** affecting satellite health for focused improvements during design and maintenance.
- **Reducing false positives and false negatives** in predictions to balance maintenance efforts and address real issues promptly.

---

## Misclassification Costs (Estimated)
### False Positive (Healthy component predicted as malfunctioning):
- Unnecessary maintenance check: **$5,000**
- Unwarranted component replacement: **$50,000**

### False Negative (Malfunctioning component predicted as healthy):
- Data loss or degradation: **$100,000**
- Partial mission failure: **$500,000**
- Total mission failure or satellite loss: **$300,000,000**

---

## Team Focus
- **Data Exploration**: Understand the relationships between telemetry variables and satellite health.
- **Model Reliability**: Select appropriate algorithms, engineer features, and validate model performance using relevant metrics.
- **Data Quality**: Address issues like missing values and incorrect data entries.
- **Variable Insights**: Investigate the importance of each variable and communicate findings to stakeholders for informed decision-making.

---

## Data Dictionary
| Variable                   | Range            | Description                                                                 |
|----------------------------|------------------|-----------------------------------------------------------------------------|
| **time_since_launch (days)** | 0 to 3650        | Time since the satellite was launched.                                      |
| **orbital_altitude (km)**   | 300 to 2000      | Altitude of the satellite's orbit.                                          |
| **battery_voltage (V)**     | 20 to 30         | Satellite's battery voltage.                                                |
| **solar_panel_temperature (°C)** | -50 to 50      | Temperature of the satellite's solar panels.                                |
| **attitude_control_error (degrees)** | 0 to 5     | Error in the satellite's attitude control system.                           |
| **data_transmission_rate (Mbps)** | 10 to 100    | Rate of data transmission from the satellite to the ground station.         |
| **thermal_control_status (0 or 1)** | 0 or 1      | Binary flag indicating if the thermal control system is working (1) or not (0). |
| **satellite_health (0 or 1)** | 0 or 1          | Target variable - binary flag indicating if the satellite is healthy (1) or unhealthy (0). |

---

## Purpose
This dataset enables teams to:
1. **Detect faults in satellites** proactively to avoid communication interruptions.
2. **Understand critical factors** impacting satellite health.
3. **Build accurate models** that minimize risks, optimize performance, and support space mission success.

---
