# Medlang
This project introduces MedLang, a domain-specific language (DSL) designed to simplify the process of defining symptoms, medical rules, and diagnostic logic. MedLang enables users to write intuitive commands describing patient symptoms and conditional rules, which are interpreted by a Python-based rule engine to generate possible diagnoses. 

MedLang: A Simple Medical Diagnosis Assistance Program

Project Title
MedLang – A Custom Coding Language for Medical Diagnosis Assistance

Course
B.Sc. (Hons.) Mathematics – IDC

Author
Alka Treesa Joseph

1. Introduction
MedLang is a simple, rule-based medical diagnosis assistance program developed using Python.
The main aim of this project is to demonstrate how a domain-specific language (DSL) approach can be used to assist in basic medical decision-making based on patient symptoms.
Instead of using complex medical software, MedLang allows symptoms and medical rules to be defined in an easy and understandable format. The system then matches user-provided symptoms with predefined rules to suggest possible diseases.

2. Objective of the Program
To design a simple medical rule system using Python
To simulate a domain-specific language (MedLang) for healthcare
To generate possible diagnoses based on symptoms
To demonstrate rule-based inference in medical decision-making
To show how Python can act as an interpreter for a custom DSL
3. Tools and Technologies Used
Programming Language: Python
Platform: Google Colab
Concepts Used:
Dictionary data structure
Conditional statements
Loops
Rule-based logic
4. Working of the Program
Medical rules are predefined for common diseases such as Flu, Cold, and Malaria.
The user enters symptoms separated by commas.
The program processes the input and compares it with stored medical rules.
If all symptoms of a disease match the user input, the disease is suggested as a possible diagnosis.
If no match is found, the program advises consulting a doctor.

5. Sample Input
fever, cough, headache
6. Sample Output
Possible Diagnosis:
- Flu
