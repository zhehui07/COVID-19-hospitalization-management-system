# COVID-19-hospitalization-management-system
Database Topic:
COVID-19 hospitalization management system

Database Purpose
With the massive amount of COVID-19 patients occupying hospital beds, the purpose of the database is
to collect health information of inpatients, improve prognosis, modify treatment strategies, and adjust
admission standards in order to manage COVID-19 patients more efficiently. This database will be used
by both physicians and hospital administrative staff.

Business Problems Addressed
● Provide patients’ information to physicians to give appropriate treatments and further reduce the
COVID-19 death rate.
● Allow medical care providers to record and compare different treatment results, which helps to
further improve treatment strategies.
● Ensure that physicians can identify the severity of the disease through clinical symptoms and
examinations and further adjust admission standards to better control the number of COVID-19
inpatients.
● Allow administrative staff to collect patients’ treatment-related information and generate descriptive
patient reports.
● Ensure that administrative staff are able to find available beds immediately for COVID-19 patients.
● Supply information to improve the scheduling of admission and discharge, and to allocate scarce
medical resources more fairly for COVID-19.
● Permit administrative staff to track the geographical distribution of COVID-19 patients to prevent
the spread.

Business Rules
● Assume all patients have already been hospitalized.
● Assume each patient has only one current address.
● Assume there can be one or more patients in each address.
● Assume each patient is treated by one or more physicians.
● Assume each physician treats zero or more patients.
● Assume each patient has one or more treatments.
● Assume each treatment is given to zero or more patients.
● Assume each physician can perform zero or more treatments.
● Assume each treatment is performed by zero or more physicians.
● Assume each patient must occupy one bed per admission.
● Assume each bed is occupied by zero or one patient.
● Assume each patient has zero or more medical conditions in his or her medical history.
● Assume each medical condition is shown in zero or more patients’ medical history.
● Assume each patient has been admitted once or more.
● Assume each admission record is assigned to only one patient.
● Assume each patient takes zero or more examinations.
● Assume each examination has been taken by zero or more patients.
● Assume each patient has one or more clinical symptoms.
● Assume a clinical symptom is shown in zero or more patients.
● AdmissionType includes emergency admission and regular admission.
● DischargeType includes expiring, recovered, and null.
● Patients less than 12 years old are not admitted due to the lack of specific equipment for kids.

Design Requirements
● Eliminate any multi-valued and/or composite attribute.
● Remove any repeating groups.
● Avoid a many-to-many relationship.
● Pay attention to the multiplicity (cardinality and partition).
● Make sure the type of relationship is correct (Identifying vs Non-Identifying).
● All entities must be connected.
● Avoid any unnecessary relationship.
● Make sure the ERD and design document match.
● Use Crow’s Foot Notation.
● Specify the primary key fields in each table by specifying PK beside the field.
● Specify the foreign key fields in each table by specifying FK beside the field.
