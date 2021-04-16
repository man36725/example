# Requirements
## Introduction
 * In child hood days almost every one of us had played the game FLMAES. To know the relation between two people it's just a fun game. The results that we are getting after the game is not true it's just a game.
 * Each letter in the word FLAMES has a meaning F - friends, L - Lovers, A - Attraction, M - Marriage, E - Enemies and S - Sisters. These are 6 relations present in the game.

## Research
### Flames Calculator
The main aim of the flames calculator is to make easy to play the game. If any one wants to play the flames game manually first they need to identify and cancel the same letters in both the names and then need to count the left over letters and need to cancel the word FLAMES untill one letter remains this is how manually peoples play the flames game but with the help of this code the whole process made easy by just enetering two names it gives the realtion between those two people in fraction of seconds

there are many systems existing in online those will work through internet but this system will work in even offline

## Cost and Features with Time 
| Time | Feature | Cost |
| ----- | ----- | ----- |
| 10

## Defining Our System
### Certain assumptions:
* Few systems already exists with which our system will interact
    * Works in online
    * works for small names
![Description](https://github.com/arc-arnob/LnT_Mini_Project/blob/main/1_Requirements/system.png)
### Explanation:
* user enters the name of him and his partner then application will return the relation exist between them 
* Note: it's just a game the results are not accurate

* Since we have assumed that few systems already exists we can say that in future sprints new features could be added in which for instance patient record from PMS can be sent to HMS or Analytics or even to emegency services if some patient record shows abnormal pattern.

## SWOT ANALYSIS
![SWOT Analysis](https://github.com/arc-arnob/LnT_Mini_Project/blob/main/1_Requirements/swot.png)

# 4W&#39;s and 1&#39;H

## Who:
* Small and medium sized clients shows interest in it

## What:
* Many Clinics are not able to afford high end HMS or ERP systems and hence still depend on manual calculation playing. to make it easy and simple 
## When:
* This problem began in February 2021, when COVID Vaccination Drive began and small/medium clinics will soon have to administer vaccinations to people.z
## Where:
* This problem is expected to surface in all states of India.

## How:
* As it is a Game if you play manually it take's a amount of time. it is a fun game mostly played by kids 

# Detail requirements
## High Level Requirements: 
| ID | Description | Category | Status | 
| ----- | ----- | ------- | ---------|
| HR01 | User shall be able to add new patient record | Techincal | TBD-S1 | 
| HR02 | User shall be able to read a patient record | Techincal | TBD-S1 |
| HR03 | User shall be able to update a patient record | Techincal | TBD-S1 |
| HR04 | User shall be able to delete a patient record | Techincal | TBD-S1 |
| HR05 | User shall be able to save records in a file | Techincal | TBD-S1 |
| HR06 | User shall be able to read data from a file | Techincal | TBD-S1 |
| HR07 | Data should not be lost in case of faliure | Scenario | FUTURE |
| HR08 | Data should always be stored when closing the system | Scenario | TBD-S1 |
##  Low level Requirements:
 
| ID | Description | HLR ID | Status (Implemented/Future) |
| ------ | --------- | ------ | ----- |
| LR01 | New record shall be added by providing all the asked information and the id should be unique or else patient record should not be accepted. | HR01 | TBD-S1 |
| LR02 | Reading patient data should be possible in 2 ways, first being by searching by id of a patient and second by printing all the records available | HR02 | TBD-S1 |
| LR03 | While reading all the records, only 10 records per page should be visible and should add 10 more if user wants to see more | HR02 | FUTURE |
| LR04 | If user searches for an invalid ID "No Record Found" message should be displayed | HR02 | TBD-S1 |
| LR05 | User need to search by id for the pateint record to be updated, if no such record is available then "No Record Found" Message should be displayed | HR03 | TBD-S1 |
| LR06 | User need to search by id for the pateint record to be deleted, if no such record is available then "No Record Found" Message should be displayed | HR04 | TBD-S1 |
| LR05 | User shall be able to save the files, if file already exists then it should append to file and should not overwrite it and if file does not exists then it should create a new file | HR05 | TBD-S1 |
| LR06 | If opening the file fails, then the system shloud prompt the message "Unable to access file" and should not end the program execution | HR05, HR06, HR07, HR08 | TBD-S1 |
| LR07 | When user Log off the system, message shall be prompted asking the user to save new records to file before exiting or not | HR08 | TBD-S1 |
