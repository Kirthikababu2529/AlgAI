1. Introduction
Overview of the Project
This project involves creating a synthetic dataset to simulate patient health records for a small clinic. The dataset includes fields such as patient id, visit_date, age, gender, diagnosis, treatment, and follow up. The goal is to generate 5,000 records that realistically reflect the distribution of patient ages, genders, and health conditions.
Why Create a Synthetic Dataset?
Creating a synthetic dataset allows us to simulate real-world scenarios without compromising patient privacy. It also enables us to test and analyze data-driven models, ensuring they perform well under various conditions.
Objectives
•	Generate a Realistic Dataset: Ensure the dataset mimics real-world patient distributions, including age, gender, and health conditions.
•	Balanced Gender Distribution: Ensure gender distribution is realistic (45% male, 43% female, and 12% others).
•	Follow-up Visit Allocation: Approximately 30% of patients should have follow-up visits, particularly those with chronic diseases, surgeries, or viral infections.

2. Methodology
Data Generation Process
Tools and Technologies Used
•	Python: Programming language used for data generation and manipulation.
•	Pandas: A powerful library for data manipulation and analysis.
•	Numpy: Used for numerical operations, including random data generation.
•	Jupyter Notebook: Interactive environment for coding and analysis.
Dataset Structure
The dataset consists of the following fields:
•	patient_id: Unique identifier for each patient.
•	visit_date: Date of the patient's visit.
•	age: Age of the patient.
•	gender: Gender of the patient (male, female, others).
•	diagnosis: Diagnosis provided during the visit.
•	treatment: Treatment prescribed.
•	follow_up: Indicator if a follow-up visit is required

![Screenshot 2024-08-13 113845](https://github.com/user-attachments/assets/1f444150-42d6-4b70-959e-b611090dc2cb)
