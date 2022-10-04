# Project: No-Show Appointments

## Table of Contents
- Introduction
- Data Wrangling
- Exploratory Data Analysis
- Conclusions

## Introduction
For this project, I analysed the No_Show Appointment dataset which consists of information of around 100 thousand medical appointments collected from Brazil. The dataset is focused on answering the question of whether or not patients show up for their appointment and it contains 14 columns.

### Dataset Columns and Description
- PatientId: Identification of a patient.
- AppointmentID: Identification of each appointment.
- Gender: Male or Female.
- ScheduledDay: The day patient set up their appointment.
- AppointmentDay: The actual day of appointment.
- Age: How old the patient is.
- Neighbourhood: Location of the hospital.
- Scholarship: Indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família (True(1) or False(0)).
- Hipertension: Indicates whether or not the patient has hypertension (True(1) or False(0)).
- Diabetes: Indicates whether or not the patient has diabetes (True(1) or False(0)).
- Alcoholism: Indicates whether or not the patient has alcoholism (True(1) or False(0)).
- Handcap: Indicates whether or not the patient is handicapped (on a scale of 0 to 4).
- SMS_received: Indicates whether or not 1 or more messages was sent to the patient (True(1) or False(0)).
- No-show: It says ‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up. 

### Questions
1. What are the characteristics of people who missed their appointment?
2. Does sending messages to patients increase the chances of them showing up?
3. Do older people show up more?
4. Which gender schedules appointments more?
5. Which gender missed appointments more?
6. Are older people more prone to the diseases and which are they most prone to?
7. Which disease group missed appointments the most?
8. Which day did most people have their appointments scheduled?
9. What day do people miss appointments more?

## Conclusions
### Findings
- Females schedule appointments more than males
- Sending messages did not increase the rate at which patients show up for their appointment
- Older people showed up more for appointment
- Gender has no relationship with the rate at which patients miss their appointment
- Older people are more prone to diseases
- Diabetes is the most associated with older people
- People rarely had appointments on Saturday
- Despite Saturday having the least appointment rate, it also had the least show up rate 

### Limitations
- The AppointmentDay column only had date and didn't have the time of day in hours, minutes and seconds
- Inferential statistics wasn't used in this analysis, so statistical conclusions can't be implied.
