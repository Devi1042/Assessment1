# Assessment1
Creating a hospital database with Entities being hospitals, doctors, patients and prescriptions.
Each table is related to the other by their primary and foreign key as per erd diagram included in repo


Relationships
patients to doctors relationship is one to one
hospitals to doctors 1 to many
doctors to patients many to many
patients to prescriptions 1 to many
doctors to prescriptions many to many
 
Queries tested : Print a list of all doctors with hospital ID 3
Print a list of all prescriptions for patient_id 621
Print a list of all prescriptions doctor_id 20 has written
Added two new patients initially with manually assigned person_id and then edited tables to have aut_increment and
added new patient using auto_increment both assigned to doctor_id 20
rachael dave 1990-01-01 1 Darent Club, WA 10465, Patient 20 
emma long 

To use these files
git clone : https://github.com/Devi1042/Assessment1.git 
use join to search using primary and foreign keys
note doctors.person_id = patients.doctor_id 
