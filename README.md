# HealthcareAppointment_no_showAnalysis
Patient Appointment system No show Analysis


# Healthcare Appointment No-Show Analysis

This project investigates why patients miss scheduled medical appointments using a cleaned dataset and an interactive Power BI dashboard. By identifying trends and potential risk factors, the analysis helps healthcare providers reduce no-show rates and improve patient engagement.

## 📁 Files in This Repository

- `cleaned.csv`: Final preprocessed dataset ready for analysis.
- `trends.pbix`: Power BI report containing interactive visualizations and insights.

## 🎯 Objective

To uncover patterns behind patient no-shows using visual analytics, and to support data-driven decisions in healthcare scheduling systems.

## 📊 Data Overview

The dataset includes over 100,000 medical appointment records with the following key features:

- **Demographics**: Gender, Age, Neighborhood  
- **Appointment Info**: Scheduled Day, Appointment Day  
- **Health Flags**: Hypertension, Diabetes, Alcoholism, Handicaps  
- **Engagement**: SMS_received, No-show status

### Sample Columns:

| PatientID | Age | Gender | ScheduledDay | AppointmentDay | SMS_received | No-show |
|-----------|-----|--------|---------------|----------------|----------------|----------|
| A12345    | 35  | Female | 2016-04-29    | 2016-05-03     | 1              | No       |

## 📈 Key Findings from Power BI Dashboard

- 🔹 **Age Impact**: Younger patients (under 25) show higher no-show rates.
- 🔹 **Timing Matters**: Longer gaps between scheduling and appointment day increase no-shows.
- 🔹 **Chronic Conditions**: Patients with hypertension and diabetes are more likely to attend.

## 🛠 Tools Used

- **Microsoft Excel** — Initial data cleaning and filtering
- **Power BI** — Data modeling and interactive dashboard creation

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone 


## Tools Used:
- Power BI
- Excel (for data cleaning)

## Key Insights:
- **No-show rate by gender**
- **No-show rate by age group**
- **No-show trends by day of the week**
- **Impact of SMS reminders on no-shows**

## Instructions:
1. Open the `.pbix` file in Power BI.
2. Interact with the report to explore the no-show patterns.
