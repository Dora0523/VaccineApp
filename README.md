# VaccineApp
## **Introduction**
This project is an application to manage the COVID vaccination distribution process in Quebec in simplified situation. 

The design of the application relations can be demonstrated by this ER diagram:
![ER](https://user-images.githubusercontent.com/65501463/129459075-4659c867-5321-415d-aef5-659da1d93377.png)


Database relation model is translated into following:
![RelationModel](https://user-images.githubusercontent.com/65501463/129459028-5622b5a7-f4c7-4f4e-8ee5-ec27969f8044.png)


## **Functions**
### **Registration**
The application allows registration to anyone who is a Quebec resident with a valid health insurance card. 
Information will be updated if the HI number entered is already in the system

A priority system is setup to ensure that the population with highest risk will be vaccinated first:
1. Health Care workers, Elderly (>= 65), Immunologically Compromised
2. Teachers, Children below 10, Those in physical proximity to first priority
3. Essential Service Workers, Those in physical proximity to second priority
4. Everybody else

### **Vaccine Appointment**
The application can allows a registered person to make an appointment for vaccine shots with preferred location, date and time that is available in the database.
Person who already took maximum number of required doses will be prevented from making another appointment

### **Enter Vaccination Info**
The application allows registered person who took the vaccine shot to enter the vaccination information to the database system.

Warning will be raised if the vaccine brand entered does not match the previous record

### **Exit Program**
The application will return to the main menu entil 'Exit Application' is selected

## **DEMO**
###**Main Menu**
![截屏2021-08-14 下午4 38 46](https://user-images.githubusercontent.com/65501463/129459487-64a46c32-2ecc-4fcd-985d-f1545c65a02a.png)

### **Option 1**
![image](https://user-images.githubusercontent.com/65501463/129459492-4e4ff1d9-86fd-44cf-a248-1b6aaff161b4.png)

![image](https://user-images.githubusercontent.com/65501463/129459494-1bbe1dfc-0a8c-4ff6-8ee9-0f0133f8b17e.png)

Update personal information
![image](https://user-images.githubusercontent.com/65501463/129459501-92e63d01-9c31-4dc2-be46-d280220c8c12.png)

![image](https://user-images.githubusercontent.com/65501463/129459503-a4ba3879-3670-428c-bbaf-323438192396.png)


### **Option 2**
![image](https://user-images.githubusercontent.com/65501463/129459521-5f1324be-837f-43c3-95ef-62632c1980c3.png)

![image](https://user-images.githubusercontent.com/65501463/129459523-7fc0a7a6-3c13-44b1-9d0a-6ff7c8b5b917.png)

#### Special Cases:

1. Slot not available
![image](https://user-images.githubusercontent.com/65501463/129459531-0f4a9fa5-378d-4b4f-b991-e76c9cda6744.png)

2. Maximum number of doses taken
![image](https://user-images.githubusercontent.com/65501463/129459557-fc2002a5-c171-4c91-8243-dcfe518a85a1.png)

3. Vaccine brand does not match the previous record
![image](https://user-images.githubusercontent.com/65501463/129459581-2191169c-5195-4a94-8cfe-382534f9c417.png)

### **Option 3**
![image](https://user-images.githubusercontent.com/65501463/129459568-ead3894c-f0c7-448e-a885-8dc2c09c97e6.png)

![image](https://user-images.githubusercontent.com/65501463/129459572-c390b76e-dc82-4a0e-8739-1893f2891ee6.png)


## **Sidenote**
Designed database information can be exported as csv file and perform an easy data analysis on the daily vaccination number
![image](https://user-images.githubusercontent.com/65501463/129459622-da4b3764-305d-4882-94af-18dda552d091.png)

![image](https://user-images.githubusercontent.com/65501463/129459626-ad6a5cd0-d900-406a-868c-927fd7dd3e25.png)
