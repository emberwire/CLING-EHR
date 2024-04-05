# CLING-EHR

# About KLING(EHR), also known herein as ("Application" or "Program")
This Python program introduces entry-level healthcare students to the foundational aspects of an Electronic Health Record (EHR) system utilizing a Command-Line Interface (CLI). It is designed exclusively for educational purposes. When first launched, all files necessary to manage patient records, medication details, and nurse credentials within a healthcare lab training setting are created on the local machine. The facilitator may "start fresh" by deleting the following files from the application directory: patients.pkl, nurses.pkl, and medications.pkl.

# Capabilities
1. Patient Management: Allows the creation and viewing of all patient records within the system. Each patient record includes a Medical Record Number (MRN), name, date of birth (DOB), sex, allergies, diagnosis, and prescribed medications.

2. Medication Management: Enables the addition and tracking of admistrations of medications to the system. Each medication has a unique ID and name. This functionality is designed for admins and is protected by a password.

3. Nurse Management: Supports adding new nurse-role users to the system, including storing their IDs and hashed passwords for login purposes. This feature is also intended for admins and is secured by a password.

4. Authentication: Emulates a medication administration flow by utilizing a rudimentary mechanism for the user to log in using their credentials (ID and password). For simplicity, it assumes all users are entitled to see any patients, medications, and data. Admins may add nurses to the system using the admin panel.

# Notes and Warnings
1. DO NOT USE THIS PROGRAM WITHIN ANY HEALTHCARE ENVIRONMENT. THIS APPLICATION *IS NOT* FOR USE AS AN ACTUAL ELECTRONIC HEALTH RECORD SYSTEM, CLEARLY.

2. When the application's .pkl files are deleted, all saved data is removed from the local machine. The program only saves entered data on the local machine. In other words, any data entered by the user is not sent anywhere. Of course, if a user's machine is compromised or monitored, we cannot guarantee that the application's files will not be stolen, with or without the user's knowledge. 

3. The Admin password is intentionally stored in clear text.

# DISCLAIMER 
1. By using KLING(EHR) or ("Application"), the user accepts that the use of this Application is at one's own risk and assumes full responsibility for any consequences or repercussions that may arise from using this Application within the limits permitted by applicable law. 

2. AGAIN, *SERIOUSLY*, DO NOT USE WITHIN ANY HEALTHCARE ENVIRONMENT. THIS APPLICATION *IS NOT* FOR USE AS AN ELECTRONIC HEALTH RECORD SYSTEM, CLEARLY.
