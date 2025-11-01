Overview:
    
The main aim of this project is to develop a *Laptop Request Catalog Item* using the *ServiceNow platform*. This catalog item enables employees or users to easily request new laptops through a structured and automated service catalog process.
The project focuses on creating a user-friendly catalog form with variables, UI policies, and UI actions to enhance the request experience. It automates visibility rules and form reset actions, ensuring smooth interaction and efficient handling of hardware requests.
By leveraging ServiceNow’s catalog management and update set features, this project ensures *easy deployment, **consistency across instances, and **better management of IT assets*, ultimately streamlining the laptop request and approval workflow within an organization.

Source Video File:


Implementation Steps:

Step 1: Setting up ServiceNow Instance
Open ServiceNow and create a Local Update Set named “Laptop Request” and make it current.

Step 2: Creating a New Update Set
Go to Service Catalog → Maintain Items, create a new catalog item named Laptop Request, and save it.

Step 3: Creating Service Catalog Item
Add the required variables under the Variables related list and save the form.

Step 4: Adding Variables
Create a Catalog UI Policy for the Laptop Request item to show accessories details when “Additional Accessories” is checked.

Step 5: Creating Catalog UI Policy
Add a UI Policy Action to make the “Accessories Details” field visible and mandatory.

Step 6: Creating UI Action
Create a UI Action on the Shopping Cart table with the action name “Reset Form” using a client-side script to clear the form.

Step 7: Exporting Update Set
Complete and export the update set as an XML file.

Step 8: Importing Update Set into Another Instance
Import the update set XML into another ServiceNow instance and commit it.

Step 9: Testing the Catalog Item
Test the Laptop Request catalog item to ensure the UI policy and UI action work correctly. 

Screenshots:

![IMG-20251101-WA0005](https://github.com/user-attachments/assets/917414fa-17c2-4e72-b337-2d018b18fa73)


![IMG-20251101-WA0006](https://github.com/user-attachments/assets/fa0faaec-7253-4414-9274-d77f0f969054)


![IMG-20251101-WA0017](https://github.com/user-attachments/assets/c01d0bb1-0c35-47e9-8629-efd567af52b6)


![IMG-20251101-WA0016](https://github.com/user-attachments/assets/d32609d1-bcde-4042-8cd2-e4086175b9f1)


![IMG-20251101-WA0015](https://github.com/user-attachments/assets/d4aa3c82-3e3b-4433-b862-5a47f4279eaf)


![IMG-20251101-WA0014](https://github.com/user-attachments/assets/419d947d-14d9-4a8c-8140-7d51aa18ddb2)


![IMG-20251101-WA0011](https://github.com/user-attachments/assets/cd31f910-619e-4aa1-9216-93c89802ba4f)


![IMG-20251101-WA0010](https://github.com/user-attachments/assets/81c17fe4-0fa2-4ce8-b68e-f6b4dced9696)


![IMG-20251101-WA0009](https://github.com/user-attachments/assets/a1e4384d-faf5-4dca-884d-26a26aff3107)


![IMG-20251101-WA0008](https://github.com/user-attachments/assets/2fe50fc9-1029-4758-8e86-3c6a887730ad)


![IMG-20251101-WA0007](https://github.com/user-attachments/assets/dfc698fe-70f9-47e6-a1e7-5390a9d6262f)


![IMG-20251101-WA0012](https://github.com/user-attachments/assets/d5788f8d-81db-479a-a3a7-608c67da7118)


![IMG-20251101-WA0013](https://github.com/user-attachments/assets/a97c8503-84c0-453d-8b69-26dbd3b2b0d5)


Project Demo Link:

Conclusion:

The ServiceNow Laptop Request Catalog successfully created a robust, automated solution for hardware provisioning. By leveraging the Service Catalog and the platform's native automation features, we provided a centralized, efficient, and transparent process. This project demonstrates the platform's power to quickly modernize and streamline core business services, setting a new benchmark for efficient ITSM and ITAM compliance.
    
Acknowledgement:

This project was completed under the Muthalvan Program as part of academic learning at Grace College of Engineering, Thoothukudi. Special thanks to mentors and the ServiceNow Developer Community for guidance and support.

Author:

Our Team Memberes: 
RUBY ESTHER Y ,
RENUGA SREE S ,
NARMATHA SRI S ,
SWARNA T.

Department: Artificial Intelligence and Data Science(AI-DS).

College: Grace College of Engineering, Thoothukudi.           
