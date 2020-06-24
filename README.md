# Medical Service Database

## Tables
MSP(<ins>MName</ins>, MDescription)  
Vaccin(<ins>VName</ins>, Dose, AgreRequired, Price)  
Citizen(<ins>FID</ins>, <ins>CName</ins>, Gender, BloodType, CDOB, Remarks)  
Family(<ins>FID</ins>, FName, FAddr)  
VaccinOperation(<ins>SerialNo</ins>, OpDate, FID, CName, VName, MName)  

## Requirements
Development of the corresponding database application
a. Deliverable: A Microsoft Access application
b. Tasks: Your application should include the following:

1. Create the tables  
  a. Create the tables described above  
  b. Your database should include at least five records in each table and
     your data should be appropriately formatted.  

2. Create Forms:  
  a. To Add /Delete in all the tables whose records are created with a
     user input, with Navigation Buttons. One form per table  

3. Create Reports to answer the following queries.  
  a. List for a specific pediatrician, the citizens in each family that
     he/she’s taking care of. The pediatrician name is a parameter that
     should be chosen from a combo box inside a form.  
  b. List all the vaccines and its corresponding age which are not taken
     by a specific citizen.  
  c. Find the total cost of all vaccines taken by all citizens in a specific
     family. The parameter family name should be chosen from a combo
     box inside a form.  

4. Create a Startup Menu including links to all the above reports and forms.  

### Note
All the forms and reports should be displayed as Windows not tab and have a
unified design.  
