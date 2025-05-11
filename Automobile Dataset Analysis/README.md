# **Automobile Dataset Analysis**

## **Overview**
This project shows how to clean, manipulate, and analyze data in Excel. The dataset includes vehicle listings that include information about the vehicle's condition, model, assembly type, fuel type, registration city, and transmission.
The goal is to extract insights and apply various data analysis techniques using functions like VLOOKUP, IF, AND, OR, FIND, RIGHT, LEN. 

## **Tasks Performed**
## **Task 1**
### **To bring columns from sheet 2 to sheet 1:**
- Fuel
- Registration City
- Assembly
- Transmission
- Condition 
### **Technique Used**
- VLOOKUP

## **Task 2**
### **To create a column called Status that shows Expensive for the cars if Price > Average Price:**
### **Formula** 
=AVERAGE(F:F)

## **Task 3**
### **To extract model from make model column into separate column:**
### **Technique Used**
- Text to Columns
- Concatenation using CONCAT()

## **Task 4**
### **To create a column called Selection that shows Selected for the cars that meet the following conditions:**
- Fuel is either Petrol or CNG
- City is not Karachi
- Make could be any except Toyota and Honda
### **Formula** 
=IF(AND(OR(H2="Petrol", H2="CNG"), NOT(I2="Karachi"), NOT(OR(C2="Toyota", C2="Honda"))), "Selected", "Not Selected")

## **Future Improvements**
- Make the analysis automated with Power Query
- For dynamic insights, make a dashboard
- Expand functionality with data visualization in Python

