# COVAC - Data Entry Exercises { #covac-data-entry-exercises }

**DHIS2 Immunization Toolkit**

**COVID-19 Vaccination Registry**

**Data Entry Exercises - COVAC**

## Preparation Notes for TRAINER

(to be removed when exercises are shared with participant)

You will need to review these exercises and modify them based on your specific workflow. Areas that may be skipped or modified are noted but this is also meant to be at your discretion to modify, remove or add to freely. Each exercise refers to an accompanying quick guide that has more detailed instructions on a specific task outlined within an exercise and is meant for the learner to take as a job aid after the training is complete.

You will need to prepare use cases to be entered into DHIS2 within these exercises. If you have real, previously filled vaccination forms that are routinely used this will be the most ideal solution. If you do not, fill in some forms that can be used during the training. Use the same form that the implementation is using which matches your DHIS2 configuration.

Each of the exercises refers to an accompanying quick guide as a reminder for the process being demonstrated. You will need to update the quick guides to reflect your configuration before sharing them for use as job aids during training and within the context of your own implementation.

If you are planning to enter data in real time, please create use-cases for data entry following this process as needed.

## Exercise 1 - Register a new case

In the first exercise, you will register a new person receiving their 1st dose into DHIS2 using tracker capture. In order to complete the exercise, you will need to refer to Section 1 of your filled in vaccination reporting form.

Follow these steps to register a new case:

1. Login as your user
2. Go to Apps - > Tracker Capture
3. Select the health facility in which you are working with
4. Select the program COVAC – COVID-19 Vaccination Registry
5. Select the “Register” button
6. Enter the details of your case taken from the vaccination reporting from
7. If using an ID generated by the system, write it down on your vaccination reporting form/vaccination card
8. Click on “Save and continue” to enter the case’s dashboard

Refer to the quick guide “COVAC Quick Guide – Register a new case” for a reminder on how to register a new person in DHIS2.

## Exercise 2 - Fill in 1st dose details

In exercise 2, you will fill in the details associated with the first vaccination within the program, with the details taken from your reporting form.  

Follow these steps when entering data into stage 1:

1. Within the case’s tracker dashboard, review the data entry page. Select the date in which the 1st dose was given
2. You will notice a number of fields can be hidden or shown. Responses to the following fields will either keep fields hidden or enable them for data entry:
   1. If the case is not female or female and less then 50 years of age, you will not be able to enter data related to pregnancy
   2. If the case is female and less then 50 years of age, you will need to answer the questions on pregnancy before being able to enter other data. If the female person is pregnant, you can not enter other data.
   3. You can only enter underlying conditions if you indicate they have an underlying condition
   4. The fields for vaccine given, vaccine manufacturer and suggested date for next dose are automatically filled in
3. Enter the details of your case as taken from sections 2, 3 and 4 of your reporting form
4. When you have completed entering details for the case, select the “Complete” button at the bottom of the data entry form. It will ask you to confirm if you want to complete the selected event; select “Complete” once again.
5. Once you complete the data entry for the 1st dose, you must schedule the 2nd dose. There will be an automatic date that is calculated as 10 weeks from the date the 1st dose was given. You can change this if you need to or use the default period of 10 weeks. Click on save when the date has been set appropriately.

Refer to the quick guide “COVAC Quick Guide – Data Entry – Vaccination (1st dose)” and “COVAC Quick Guide – Data Entry – Scheduling the 2nd dose”  for a reminder on how to enter these details into DHIS2.

## Exercise 3 - Finding your case

In exercise 3, you will find the case that you need to update.

To find your case:

IF using the front page filters list

1. Navigate to the health facility you are working in
2. Apply the filters for:
   1. All clients
   2. Clients with a scheduled visit
   3. Clients with an overdue vaccine dose
   4. Completed clients
3. Select the case you need to work on from the list that is shown based on the case you are updating for (ie. match the ID/demographic information of the case in the list with the case’s COVAC profile information). If you can not identify the case this way, you will need to search for it. Please see the instructions on using the search feature.

Refer to the first quick guides “COVAC Quick Guide – Using the front page list filters” for a reminder on how to use this list to find a case in DHIS2.

IF using search

1. Navigate to the health facility you are working in
2. Select the “Search” button
3. From the screen that appears, enter information to search for the case. If you are able to use the unique ID, this will find your case immediately and take you directly to the case’s dashboard when you select the search button.
4. If you are searching for the case using details other than a unique ID, enter these details and click on the search button.
5. Select the case you need to work on from the pop-up based on the lab results that you are entering (ie. match the ID/demographic information of the case in the list with the case’s COVAC profile information).

Refer to the first quick guides “COVAC Quick Guide – Searching for a case” for a reminder on how to search for a case in DHIS2.

## Exercise 4 - Fill in 2nd dose details

In exercise 4, you will fill in the details associated with the second vaccination within the program, with the details taken from your reporting form.  

Follow these steps when entering data into stage 2:

1. Within the case’s tracker dashboard, review the data entry page. Select the date in which the 2nd dose was given. Compare this to the date the dose was scheduled. These dates might be different.
2. You will notice a number of fields can be hidden or shown. Responses to the following fields will either keep fields hidden or enable them for data entry:
   1. If the case is not female or female and less then 50 years of age, you will not be able to enter data related to pregnancy
   2. If the case is female and less then 50 years of age, you will need to answer the questions on pregnancy before being able to enter other data. If the female person is pregnant, you can not enter other data.
   3. You can only enter underlying conditions if you indicate they have an underlying condition
   4. The fields for vaccine given, vaccine manufacturer and suggested date for next dose are automatically filled in
3. Enter the details of your case as taken from sections 2, 3 and 4 of your reporting form
4. When you have completed entering details for the case, select the “Complete” button at the bottom of the data entry form. It will ask you to confirm if you want to complete the selected event; select “Complete” once again.
5. It will ask you to schedule another dose. Close this box as you do not need to schedule another dose.

Refer to the quick guide “COVAC Quick Guide – Data Entry – Vaccination (2nd dose) ” for a reminder on how to enter these details into DHIS2.

## Exercise 5 - Complete the enrollment

Follow these instructions to complete the enrollment:

1. Ensure you are still logged in and viewing your case
2. Now that all of the information for this case has been entered, you can complete the entire case’s interaction with this program. In order to complete the case, navigate to the top of the case’s tracker dashboard.
3. In the enrollment box, there will be another “Complete” button. This will complete the case’s entire interaction with this program and should only be completed when their national level data has been finalized and entered.
4. Select this “Complete” button. DHIS2 will ask you “Are you sure you want to complete the selected enrollment?” When you are certain, select “Yes”
5. To verify the enrollment is completed, you can navigate back to the front page list by selecting the “Back” button from the case’s dashboard in the top left corner.
6. Select the “Completed clients” filter button.
7. The case you have completed should now be at the top of the list.

Refer to the “COVAC Quick Guide – Completing the enrollment” for a reminder on how to search for a case in DHIS2.

## Exercise 6 - Review of all concepts

In exercise 6, you will be completing data entry from start to finish for all components of a case. You will be using filled in copies of the COVAC Reporting Form in order to complete this exercise.

To complete this exercise:

1. Login as your user
2. Register a new case based on the details provided in the COVAC Reporting form
3. Enter details for the 1st dose
4. Complete the 1st dose by selecting the complete button
5. Schedule the 2nd dose
6. Exit the case and search for it using the person’s ID
7. After finding your person, enter the details of the 2nd dose
8. Complete the 2nd dose by selecting the complete button
9. Dismiss the scheduling as they will no longer receive further doses
10. Complete the enrollment
11. Verify it is complete by checking your “completed clients” list

Please refer to each of the individual exercises and quick guides for a refresher on how to complete each of the steps presented here.

## Exercise 7 - Scheduled doses

NOTE TO TRAINER: SPECIFY THE ORG UNIT TO USE WHICH HAS PEOPLE SCHEDULED FOR THEIR SECOND DOSE (IN WHICH THE DATE HAS NOT YET PASSED)

In exercise 7, you will find people that are scheduled to receive their second dose.

To do this:

1. Select “Reports” from within tracker capture
2. Select “Upcoming events”
3. Specify the inputs for the report
4. Select “Go” to run the report
5. You can then print the report if you need it for future reference

Refer to the “COVAC Quick Guide – Finding people scheduled for their 2nd dose” for a reminder on how to run this report in DHIS2.

## Exercise 8 - Overdue doses

NOTE TO TRAINER: SPECIFY THE ORG UNIT TO USE WHICH HAS PEOPLE THAT WERE SCHEDULED FOR THEIR SECOND DOSE (IN WHICH THE DATE HAS NOW PASSED)

In exercise 8, you will find people that are overdue for the second dose

To do this:

1. Select “Reports” from within tracker capture
2. Select “Overdue  events”
3. Specify the inputs for the report
4. You can then print the report if you need it for future reference

Refer to the “COVAC Quick Guide – Finding People that missed their 2nd dose” for a reminder on how to run this report in DHIS2.