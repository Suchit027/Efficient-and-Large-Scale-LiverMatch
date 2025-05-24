# Efficient and Large Scale Liver Match

## Overview
This project simulates the process of liver transplantation across a hospital network, from the harvesting of a liver to its allocation and transportation to a recipient patient. The system considers multiple real-world constraints and optimizes liver-patient matching based on:
- Patient health (MELD score, alcoholism degree, age)
- Liver viability (age, life distance it can travel)
- Geographical proximity between donor and recipient hospitals
- Availability of resources (beds and doctors) at the recipient hospital

The entire logic is implemented using PL/SQL, leveraging:
- Procedures for inserting data and orchestrating transplant workflows
- Functions to evaluate transport feasibility
- Triggers to automate resource tracking
- Cursors for efficient record traversal and conditional processing

