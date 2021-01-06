# Module 4

## 4.1 - Introduction to Collection and Customization

### Create your account in CUSTOMIZATION

Click the button below to request an account on the DHIS2 Customization.
You will receive an invitation by email with instructions on how to complete the registration in DHIS2.

*Note: the email address you use with OpenEDX will be sent to the DHIS2 database to create an account.*

## 4.2 - Design Principles

## Session Quiz - DHIS2 Customization

### NOTE: THIS IS A GRADED QUIZ

You are allowed 3 attempts for this quiz.

There is 30 seconds of time between each attempt, so if you don't get it right, just breathe in, watch the videos once more and carefully read the question again.

------------------------------------------------------------------------

&gt;&gt;DHIS2 is an off-the-shelf solution that requires no additional configuration upon installation.&lt;&lt;
( ) True
(x) False

[Explanation]
In both the DHIS2 History/Introduction and DHIS2 design principles presentation, it is highlighted that DHIS2 is a generic solution that needs to be tailored to fit local needs and requirements
[Explanation]

&gt;&gt;You need to be a computer programmer (someone who knows computer languages) to take part in the configuration of DHIS2.&lt;&lt;
( ) True
(x) False

[Explanation]
Many aspects of DHIS2 configuration can take place directly through the user-interface. This concept was discussed in the DHIS2 design principles presentation and demonstrated through numerous configuration sessions.
[Explanation]

&gt;&gt;DHIS2 only supports the integration of data from one health program at a time.&lt;&lt;
( ) True
(x) False

[Explanation]
Multiple programs can be integrated into the DHIS2 platform together. This is shown as both a concept and demo in the DHIS2 design principles session.
[Explanation]

&gt;&gt;Reports in DHIS2 are dynamic and can be the combination of data from several different data sources.&lt;&lt;
(x) True
( ) False

[Explanation]
Report can be a combination of data from multiple sources. This is shown in the DHIS2 design principles session.
[Explanation]

&gt;&gt;What is the difference between Data Elements and Indicators (select one)?&lt;&lt;
( ) They are both the same.
( ) Data Elements measure the coverage while indicators collects data values from the paper forms
(x) Data Elements are the raw data while Indicators are calculated values/formulas

[Explanation]
The key difference here is that indicators represent calculated values, and can typically be made up of several data elements. Data elements are the raw items of data that are collected through routine processes.
[Explanation]

## 4.3 - Organisation Units

## Assignment - Organosation Units, Data Elements & Data Sets

### NOTE: These graded assignments belong to a series that goes throughout module 4

This series of assignments consist of 3 sets:

- **Set 1: Organisation Units**
- Set 2: Data Elements
- Set 3: Data Sets

This series will allow you to build bits by bits a data set and populate it.

At the end of the last assignment (assignment 4.6.2) you will be ask to check whether you have completed the whole series or not. This check will allow the course team members to validate the result of your assignments in DHIS2 Customization. It is only after this validation process that the final grade of this series of assignment will be confirmed. As for the other assignments, you are allowed 3 attempts.

*Note: Before the validation from the course team, the max grade for this series will be applied, but this grade is not the validated one.*

------------------------------------------------------------------------

### Assignments Module 4 - Set 1/3 - Organisation Units

### Instructions

You need to be logged in [DHIS2 Customisation](https://live.academy.dhis2.org/cu1/dhis-web-commons/security/login.action) to perform the following assignments.

You are tasked with creating a portion of the organization unit hierarchy within your country. The data should be entered at the correct level so appropriate outputs can be created. The hierarchy in this example country has 4 levels:

1. Country
2. Province
3. District
4. Facility

You will notice that the Country level organisation unit has been created using your e-mail address when you enter organisation unit maintenance. This is so that you will only see the organisation units that you are creating, rather than seeing everyone’s organisation units together. Feel free to change the name of this organisation unit to something else if you desire.

<img src="https://lh6.googleusercontent.com/gOQoQyjmI6c4ZlzG1LPq9nFewZmJCo65NO6dtcU3y65fX6cpb3YllUxecVaqyu_wasuaft1dm4t0Jq0D02H67ik_MMUSSmMoqNve2p33jRoY9a2noT2kwW82-2XXmLBwuDIa9eA3" width="624" height="335" />

***Please work on the following:***

### Assignment 4.3.2

Create 4 organisation unit groups with the following names (and belonging to the indicated group sets) and assign your above facilities (the organisation units you have made at level 4) appropriately:

**Note:** **Make sure to add a prefix using your initials to these names (ie. SND_Hospital, SND_Health Center) when you create them in DHIS2. As everyone is creating items in the same system, you need to provide the groups with unique names.**

*Group Set 1 : Facility Type*

- Hospital
- Health center

*Group Set 2 : Ownership*

- Private
- Public

### Assignment 4.3.3

Create two organisation unit group sets and assign them the appropriate organisation unit groups:

**Note:** **Make sure to add a prefix using your initials to these names (ie. SND_Type, SND_Ownership) when you create them in DHIS2. As everyone is creating items in the same system, you need to provide the group sets with unique names.**

- Type
- Ownership

## Session Quiz - Organisation Units

### NOTE: THIS IS A GRADED QUIZ

You are allowed 3 attempts for this quiz.

There is 30 seconds of time between each attempt, so if you don't get it right, just breathe in, watch the videos once more and carefully read the question again.

------------------------------------------------------------------------

Which one of these are not an organisation unit? (select one)
( ) Ermita Public Health Centre
( ) National Capital Region
( ) Manila Hospital
(x) Malaria Elimination Project

[Explanation]
In the organization units presentation, it is mentioned that multiple concepts should not be mixed in the hierarchy
[Explanation]

The organisation unit hierarchy: (select one)
(x) Can use organisation unit groups to model additional hierarchies (for example, public/private facilities) for analysis
( ) Only supports a limited number of levels
( ) Does not include any administrative layers outside of the facility

[Explanation]
The concept of using organisation unit groups during analysis was shown during the organisation units presentation. These are user defined as was shown in the organisation unit demo.
[Explanation]

Imagine you've created the following health facilities in DHIS2:
-Alberta Public Health Clinic
-Ontario Private Hospital
-Windsor Public Health Clinic
-London Public Hospital
As you can see there are two ownership types: private and public. There are also two facility types: clinic and hospital.

Now you want to create organisation units groups for these facilities. Which organisation unit groups would be best? (Select one or more)
[ ]

**Health Clinic**: Alberta Public Health Clinic / Windsor Public Health Clinic AND

**Hospital**: Ontario Private Hospital / London Public Hospital / Windsor Public Health Clinic

[x]

**Health Clinic**: Alberta Public Health Clinic / Windsor Public Health Clinic AND

**Hospital**: Ontario Private Hospital / London Public Hospital

[x]

**Publicly Owned Facilities**: Alberta Public Health Clinic / Windsor Public Health Clinic / London Public Hospital AND

**Privately Owned Facilities**: Ontario Private Hospital

[ ]

**Publicly Owned Facilities**: Windsor Public Health Clinic / London Public Hospital AND

**Privately Owned Facilities**: Ontario Private Hospital / Alberta Public Health Clinic

[Explanation]
In this case, we can group the public health clinics and hospitals together. This would be equivalent to defining the type of facility within a system. We can also group public and private facilities together, which would equivalent of defining the ownership of these facilities. This was discussed during the organization unit presentation.
[Explanation]

When managing organization units in DHIS2 through the user interface, we can define the following geographical features: (select one or more)
[x] Latitude/Longitude (for example, the location of a facility)
[x] Geographical Symbols that define groups
[ ] Geographical Boundaries for regions, provinces, districts, etc.

[Explanation]
This was shown when demoing the creation of organisation units. We can add in lat/long coordinates of a facility during creation, and assign symbols to organization unit groups.
[Explanation]

## 4.4 Data Elements

### Activity 1 - Data Element Naming

#### Data Set Exemple

You are provided with the following summary data set to collect information on HIV, malaria and TB. We will use this example to properly name, create and group data elements. Please see the following sections.

| Data Element                                                                                    | Value |
| :---------------------------------------------------------------------------------------------- | :---- |
| Number of female sex workers reached with HIV prevention programs (Outreach)                    |       |
| Number of PLHIV Attended                                                                        |       |
| Number of HIV positive TB patients who are already on ART or started on ART during TB treatment |       |
| TB07.10 Number of patients with positive bacteriological results out of diagnosis               |       |
| TB07.19 Number of patients examined for follow-up                                               |       |
| MAL02.01 Malaria Slide (Tested)                                                                 |       |

#### Instructions - Data Element Naming

Fill in the table below (the 'Name in DHIS 2' column), assigning the data element a name you think is suitable for use in a database such as DHIS 2. You will later be asked to create these in DHIS 2.

| Associated Program/Data Set  | Name on Form                                                                                    | Name in DHIS2 |
| :--------------------------- | :---------------------------------------------------------------------------------------------- | :------------ |
| HIV1 Program Progress Report | Number of female sex workers reached with HIV prevention programs (Outreach)                    |               |
| PLHIV2 Network Activities    | Number of PLHIV Attended                                                                        |               |
| ART3                         | Number of HIV positive TB patients who are already on ART or started on ART during TB treatment |               |
| TB4 07                       | TB07.10 Number of patients with positive bacteriological results out of diagnosis               |               |
| TB 07                        | TB07.19 Number of patients examined for follow-up                                               |               |
| Malaria Monthly Report       | MAL02.01 Malaria Slide (Tested)                                                                 |               |

1. Human immunodeficiency virus
2. People living with HIV
3. Anti-retro-viral therapy
4. Tuberculosis

## Assignment - Organisation Units, Data Elements & Data Sets

### NOTE: These graded assignments belong to a series that goes throughout module 4

This series of assignments consist of 3 sets:

- Set 1: Organisation Units
- **Set 2: Data Elements**
- Set 3: Data Sets

This series will allow you to build bits by bits a data set and populate it.

At the end of the last assignment (assignment 4.6.2) you will be ask to check whether you have completed the whole series or not. This check will allow the course team members to validate the result of your assignments in DHIS2 Customization. It is only after this validation process that the final grade of this series of assignment will be confirmed. As for the other assignments, you are allowed 3 attempts.

*Note: Before the validation from the course team, the max grade for this series will be applied, but this grade is not the validated one.*

### Assignments Module 4 - Set 2/3 - Data Elements

### Instructions

You need to be logged in [DHIS2 Customisation](https://live.academy.dhis2.org/cu1/dhis-web-commons/security/login.action) to perform the following assignments.

#### Data Set Example

You are provided with the following summary data set to collect information on HIV, malaria and TB. We will use this example to properly name, create and group data elements. Please see the following sections.

| Data Element                                                                                    | Value |
| :---------------------------------------------------------------------------------------------- | :---- |
| Number of female sex workers reached with HIV prevention programs (Outreach)                    |       |
| Number of PLHIV Attended                                                                        |       |
| Number of HIV positive TB patients who are already on ART or started on ART during TB treatment |       |
| TB07.10 Number of patients with positive bacteriological results out of diagnosis               |       |
| TB07.19 Number of patients examined for follow-up                                               |       |
| MAL02.01 Malaria Slide (Tested)                                                                 |       |

### Assignment 4.4.1 - Data element Creation

You were previously asked to fill in this table as part of the Data Element naming activity. Please continue with this example and:

1. Proceed to create these data elements in DHIS 2 (Use your initials as a prefix. Example: I create a data element for ANC 1 visit, I can call it SND_ANC 1st visit)
2. Create and Assign them to a Data Element group

| Associated Program/Data Set  | Name on Form                                                                                    | Name in DHIS 2 |
| :--------------------------- | :---------------------------------------------------------------------------------------------- | :------------- |
| HIV1 Program Progress Report | Number of female sex workers reached with HIV prevention programs (Outreach)                    |                |
| PLHIV2 Network Activities    | Number of PLHIV Attended                                                                        |                |
| ART3                         | Number of HIV positive TB patients who are already on ART or started on ART during TB treatment |                |
| TB4 07                       | TB07.10 Number of patients with positive bacteriological results out of diagnosis               |                |
| TB 07                        | TB07.19 Number of patients examined for follow-up                                               |                |
| Malaria Monthly Report       | MAL02.01 Malaria Slide (Tested)                                                                 |                |

1. Human immunodeficiency virus
2. People living with HIV
3. Anti-retro-viral therapy
4. Tuberculosis

### Assignment 4.4.2 - Data Element Groups

Create 3 data element groups, assigning the data element appropriately based on the health program that they belong to. Use your initials to prefix the data element groups that you create as you did for the data elements.

The groups should consist of the following (the data elements in DHIS2 that you assign will be the new names you have assigned them in Section 1):

HIV

- Number of female sex workers reached with HIV prevention programs (Outreach)
- Number of PLHIV Attended
- Number of HIV positive TB patients who are already on ART or started on ART during TB treatment

Malaria

- MAL02.01 Malaria Slide (Tested)

TB

- TB07.10 Number of patients with positive bacteriological results out of diagnosis
- TB07.19 Number of patients examined for follow-up

### Assignment 4.4.3 - Data Element Group Set

Create a group set that consists of the HIV, Malaria and TB data element groups that you have created. As before, prefix the group set with your initials.

## Session Quiz - Data Elements

### NOTE: THIS IS A GRADED QUIZ

You are allowed 3 attempts for this quiz.

There is 30 seconds of time between each attempt, so if you don't get it right, just breathe in, watch the videos once more and carefully read the question again.

------------------------------------------------------------------------

Data Element names should: (select one)
( ) Be as long and descriptive as possible
(x) Use self-contained names which describe the data effectively for output
( ) Replicate the name on a paper form
( ) Be considered for input as a priority

[Explanation]
When discussing data elements, we should always consider how they will appear in output. This is discussed in more detail during the data elements presentation.
[Explanation]

I have a section of data elements that I am collecting all related to child delivery. I want to create the data element represented by the "Number of deliveries with complication" on the paper form. What is the most appropriate name for this data element? (select one)
( ) Number of deliveries with complication
( ) Complicated deliveries
(x) Deliveries with complication

[Explanation]
During the data element presentation, naming principles were discussed. Here, since we have a set of delivery data elements, it is better to start the name off with "Delivery" as all the delivery types could easily be found together in a list.
[Explanation]

Data elements in DHIS2 can only be summed (added) together. No other operations, such as finding the average or counts of a particular value, can be performed.
( ) True
(x) False

[Explanation]
When creating data elements, we can define various aggregation types. While sum tends to be a common option, other types can be used if needed.
[Explanation]

Data Element Groups are used for grouping together similar data elements for thematic analysis.
(x) True
( ) False

[Explanation]
Data element groups are user defined and assist us in finding our data elements during analysis. Their use was shown throughout all the analysis apps and their creation was shown in the data element creation session.
[Explanation]

## 4.5 - Data Collection

### Activity 1 - Introducing the data entry app interface

Please do this activity in [TRAININGLAND](https://live.academy.dhis2.org/tl1/dhis-web-commons/security/login.action).

Familiarize yourself with the web data entry interface by opening a data set, navigating the data set and entering some data values. In order to open a data set you must first select the organisation unit, data set and period that you would like to review.

- Select any organisation unit by either using the magnifying glass or expanding the tree on the left side of the screen.

<img src="https://lh6.googleusercontent.com/NF6JHczxTCzgv-IQRFulELu__g6r5ht2koYZ0-PTO0ACMX8nMMUV-sgGs5tGDiBBWwB67DIFhXYjts7u2SMLnyzYCW3PPbBzob-MY5Xriv2Zfi43rzt8254Iu3tCOLBVMlmVQIk7" width="323" height="499" />

The organisation unit that you select will be highlighted in an orange color. It will also be displayed as the selected organisation unit in the data entry pane.

After you have selected an organisation unit:

- Proceed to select a data set (in this example we will use the Primary Health Care Monthly data set)
- and Period (select a period in 2018 such as January 2018 or March 2018 as these periods currently do not have any data; use the "Next year" button to select periods in 2018).

<img src="https://lh3.googleusercontent.com/otO0TwkDhAEg2TDDHQW0xpar4LCFKf6WDdBrRG9fotYa4vNQLPl4WVpPNRX5waSOzpdAKEMsf7HPqhBWI7RTAvstG6okZVDeB8lIRJSbMCMhUv9Z_s3qlZrb8RQV4HXupq7JmsDV" width="624" height="159" />

After selecting these parameters the data set will be displayed. **Note: If you select a organisation/period that already has data entered in it already for 2018, try selecting a different organisation unit or period in which no data has been entered.**

<img src="https://lh5.googleusercontent.com/AtXSo27WxOBYpIt44DORQv81E7-amWtGfQz-sb-yFW6lK9kb7t5HI2q5s89l5LNpSwklk981CXe_ZSFd2I6mb2io0fett2T1wh9tPeVudHDK0pZYk4tV0s-Bu6jpj9uniudSaVZX" width="624" height="289" />

- Enter the following practice data for the first section of the data set (labelled "Primary Health Care Monthly") to get a feel for using the data entry app. You can quickly navigate within the data entry app by using enter or tab to move forward/down and shift+tab to move backward/up between the various data element values when entering your data. Notice that when you enter values they will quickly change from yellow to green indicating they have been saved.

<img src="/static/Primary_Health_Care_Monthly.png" width="632" height="625" alt="Primary_Health_Care_Monthly" />

### Activity 2 - Reviewing the data element history, audit trail and validation rules

Please do this activity in [TRAININGLAND](https://live.academy.dhis2.org/tl1/dhis-web-commons/security/login.action).

Start this activity by running validation for the data that you have previously entered according to the example data provided in Activity 1:

- You can select **Run validation** at either the top or bottom of the data entry page.

<img src="https://lh4.googleusercontent.com/gIZjoBgyaUaeu-k-r__ZLzcgQw9enqq0nYGEvFwTFpa-_79lcg1RLWYSSfrSmOy5-K-W6oSWj1N_hUK9jL6A0MmtL-hMZXw4OQrv6Y5q6T9jg4xH5h2v7hOW-F0J49vPNV6a_xJq" width="592" height="88" />

When you run validation, a pop-up screen will prompt you that some validation rule violations have been detected.

<img src="https://lh6.googleusercontent.com/pjUQj5ZuORx3XkMPw7zb3ojBD8ibdjoNM2-8XI69mOD35wgSmPAH7b8yOEK2oUY78__4sb3f9GCnEf8xT1uKMBDcfceuL97kGQafad8UZjd3I7MB6zp_JUU3aERXRr0E2MTE1t5i" width="624" height="276" />

This includes:

- **Birth live &gt;= Breastfeeding within 1 hour after delivery**: the amount of infants that are breastfeed within 1 hour after delivery is a sub-set of the total live births within a facility. Therefore live births should always be greater than or equal to the number of infants breastfeed within 1 hour after delivery.
- **Delivery by Caesarean Section &lt;= Delivery by skilled birth attendant**: Caesarean Section’s are a sub-set of total deliveries performed by a skilled birth attendant, and therefore should be less than or equal to the deliveries performed by skilled birth attendant.
- **Delivery with complication &lt;= Delivery by skilled birth attendant**: Deliveries with complication are a sub-set of total deliveries performed by a skilled birth attendant, and therefore should be less than or equal to the deliveries performed by skilled birth attendant.

Let us fix these validation rules before continuing.

- Update the following data elements to fix the issues with validation. In this case, we could imagine some simple data entry errors occurring. In the first example (Birth live) a 6 was entered instead of a 9. In the second example (Delivery by skilled birth attendant) the 7 was not entered at the end of the data value.

<img src="/static/fix_validation__ules_table.png" width="631" height="107" alt="fixing validation rules" />

After you have edited the values:

- run the validation again. This time, you should see a successful result.

<img src="https://lh6.googleusercontent.com/dT0NgttFrmSVnM8I3q9QrSDliGHUd6cNOkCY4YlII0qtouJfU1AoMrso26Ovdtf673yq3bZT_VLSUud34chccdqp2thed1UgAkUI3_ZoFAAsPahms6VHnEdvIZIfcQZ3Wn7KiAP3" width="452" height="187" />

- Double click on the value for Birth live (194) after you have corrected it.

This will bring up the data history page for you to review.

<img src="https://lh6.googleusercontent.com/MBMs1Ngiz0thPOzTf0RFCGvdvWSB47zqFmHGYzmbL9lTPqYSVstE5_8KKrgI6mKBb4lyxs1rK-w8aZ0yJ8l4TPMfA4yJq5RbUdlnUDpGu-gUsC0kfu3KCH0mo62jhDjwBDJ374pZ" width="624" height="635" />

- You can also select “Audit Trail” to review any changes you have made to the data element value.

<img src="https://lh3.googleusercontent.com/6JPq7gKy8lHxx53y62fV3MHYWhF2dv0R1WflywBF_8uwJOXJ2Lb4QNsfyCxd_1bUhRMeaMpqwpNbd0J6l74v78c-pXgjbML7Rqm-ueE_HrvfKteJM7_ky7t6YD1MAfTQQbxZhS_v" width="624" height="515" />

### Activity 3 - Completing data entry

Please do this activity in [TRAININGLAND](https://live.academy.dhis2.org/tl1/dhis-web-commons/security/login.action).

- Complete the data entry process by clicking on the complete button for the organisation unit/period/data set combination you have been working with.

<img src="https://lh3.googleusercontent.com/r9rqQ4SqYF1FDesgcLDDFHWpj6bLdNHb9BDJBREpviEJZ0fdRG5mTLHOf5FAeMfeIUjhfFjBDnmI_EfEfPao7Ps0cD53JMFjQ2-hWX8T70WD-0riXGQcFr0vfdfFE-eEPLpOaJCi" width="599" height="84" />

After you click on the “Complete” button, it will be grayed out. This will now contribute to being a complete report when you run the reporting rate completeness later on in DHIS2.

<img src="https://lh6.googleusercontent.com/x0aT-Ql-lRsLY7A8XWShb0EurHHygaBmdlV_z6o7qibAtlXeYDssXjpXVqYOVVGtftT5kq3gG0FU4fciXzeUDPtVyOxtjOwxB6-iAlvenq6e8BORqe9Ucowpn1bcYf82IaKAw1zK" width="594" height="72" />

- Re-load the data entry application
- and re-select the organisation/period/data set combination you were previously editing.

<img src="https://lh5.googleusercontent.com/yrwKP-EmMV-vw80blh8wsWeFB_XRNTuuzspbzMTYOI9tDv3MwX5sn8DZW2TOoeDIu4shMvHrYfVosRWci4RCimVr-Z3svxGs8WVo2hNTp0SbFpYGFToIYSWwxr_TiQL15X9-__PT" width="624" height="177" />

With the data set displayed:

- Scroll down to the bottom of the data entry page. You will now see the "Completed by" tag underneath the complete button.
- You can click on "See details" to bring up additional information on the person who entered this data.

<img src="https://lh5.googleusercontent.com/RHRiDATKho-IXXtXku70CZDgSoVtWi_7ZMHAkRojJH7RdO2wGqu8AMwNGRee-fXX9IQTZP0Ef13F5nm4PKQXyUZwAXvIbOsHeE_vmJDArm87Y5XfliqH1y52UBxl8gQcBlJeerGB" width="599" height="157" />

<img src="https://lh4.googleusercontent.com/yq5nyrhyt0SEluuVsRN0y0U-NQiOC0B1crqUHb98LHAnOfCLmML_aplbZhlNKI95fEDuccW4EIVPGqAA-sIHRVLFWAC9ax37o5JvTM8knJqvZ17rieKS9qjth-P_gTnDZ8o6p0zu" width="475" height="458" />

### Activity 4 - Offline data entry

Please do this activity in [TRAININGLAND](https://live.academy.dhis2.org/tl1/dhis-web-commons/security/login.action).

- To perform offline data entry, disconnect from the internet.

DHIS2 will prompt you indicating "You are offline, data will be stored locally".

<img src="https://lh4.googleusercontent.com/9OQY6aAp9c3G1jkOJ6KM2q9N5HJBfK2wPB-ZVSP_E189xGRV7RyPjhOnnBxC5tgfD4Oz7mUEitTw5cIXSpnbRijY15M2YafWbsGM74nt15i4eTP62uq1D5lz4KQl_bjwwyCTuNZR" width="594" height="51" />

- Try navigating around and selecting different organisation units at the facility level.

You can also change between the different data sets and periods. Note that you will not see any data that is only stored online; therefore most of the organisation unit/data set/period combinations you select will not display data until you are back online.

- Enter some data in offline mode for the primary health care monthly data set using a period in 2018 as you did before for the Immunization section of the form.

<img src="/static/offline_data_entry.png" width="633" height="209" alt="offline data entry form" />

- Re-connect  to the internet. A prompt will indicate that "There is data stored locally, please upload to server".
- Click on the Upload button to upload the data.

<img src="https://lh6.googleusercontent.com/TkAmMIQUHjwe7kiFF5cUxA37aVqCfBugWgjX1YW9eTJx2zqAUREmaVlLYfxNRlUacd5NbSTVFP_x8gYxOLnrfnqjVPyxMPMyQltvN9wbrTknZcPg5EKyXoNq8gtIB9qcly1YF-1C" width="589" height="55" />

After the upload is complete, you will receive a prompt indicating that the "Upload to server was successful".

<img src="https://lh5.googleusercontent.com/kHgph-TEXCdIUGii27p0kXaui7eY58JaU4ohP1twa8lUM6IswhrJuajDY7s8X0ZWcEQWKsUVS0jUQzjH9esCDS5FZzPjPG3XGBobffSbggrDRMUtnkqfTNaIPhqBa7Mc1BQS_EaM" width="590" height="49" />

### Activity 1 - Installing, logging in and entering data using an Android device

To perform this activity, you will need an Android device (at this point, only Android devices are supported)

On the Android device, you will need to install the app:

- Navigate to the play store on your phone and find the "**Data Capture for DHIS2**" app in the play store: <https://play.google.com/store/apps/details?id=org.dhis2.mobile&hl=en>
- Install the app when you find it in the play store.

<img src="https://lh4.googleusercontent.com/X2r3OYSUHsSpQREOtNbkSRDn388B9dFR3l1sz_aW2puyzxB2V549r1ToxFGMxe_Yy_U070LvVQ9EDICvc6SarGz6jW_PgbPg-6mi64PBHDP5crGHsS10G4qWFSg2_GK9r5OB0VUt" width="270" height="480" />

- Open the app up on your phone (**DHIS2 Data Capture**)

<img src="https://lh6.googleusercontent.com/s59UMcsWJ69dJjVNq_EF1jJFWq_RcV4z7DM5taWTze7eoPwhjFVK221npk2_21SZmN1WreS4HYWv3_MPsuf-60jEKu5U5mG7xJv5sQbjW7nNmJNW7_riZP2fsS2ShJoPuvAzUicd" width="270" height="480" />

Fill in the details as follows:

- **Server URL**: <https://live.academy.dhis2.org/tl1>
- **Username**: Select a user-name from the table below (for example, if my last name starts with J, I would use android5)
- **Password**: Password1

<img src="https://lh6.googleusercontent.com/2zF4kcFF3wYg6rhpSqE18_cpeyl2XrBJK8LeZU26y8PMXYqMMGFrEmuiDxOLBG3tuCj8s4ttk0y_mdltuCZ4tnqo5lg8iCJGMnsmtM-hhVl1tBtD1EJcPEihn_reBmnCoa4RTY-j" width="270" height="480" />

***Note**: For the username, several have been created for this exercise. Please select an account according to your last name. This is being done so that we can separate the data that is entered by the android devices across the various organisation units within Trainingland so it is easier for each user to find their data when the log in through their web browser later on.*

<img src="/static/android_data_capture_table.png" width="648" height="480" alt="Android data capture table" />

- Click on the "**Log in**" button to log in. You will see this interface initially.
- Select "**Choose organisation unit**".
- and select an organisation unit to continue.

<img src="https://lh6.googleusercontent.com/8rFGVhUBs8HUgfmq-qFOQZVcf2-60cZv3Nb9vmXhuLTBOb07e13qklyP3gMqRymTbBJ8KBJFO7kD1JadrKXoQVblKzOPV4PC9ecqG2I4HB-n8iKt7Y_25DiNm5JtAxFzCPHv3ROM" width="270" height="480" /> <img src="https://lh3.googleusercontent.com/Ssr8rysPxYe9L_LSsxariKGuvICyPwLwgwnfofEeLhqwtZx2wrl6Vo-Lgq-g0ED3vDauAQq4UhunOwTbMABS0qAaQ8jFXZwdacyMX72WwAMFYG939nEMHtWEzzT4Eph4BC1cgUIS" width="270" height="480" />

- Next, tap "**Choose data set**".
- and select the "**Syndromic Surveillance**" data set.

<img src="https://lh4.googleusercontent.com/j0ry9jKX3CUIWBCcgSzPTfpfUX7gbsoYVwk75ayN-hcafFWDOBnmnHgtCHza3uXEHlF1fop81pvmAlzTRUNyCEvDhyxNwgrzrLCIrzfcm07pUAzAEH4tQhrieT5gGbKCsSGRI-dw" width="270" height="480" /> <img src="https://lh4.googleusercontent.com/dPxjzLizfme9LOJWzjr0cMBHw8jvcMHtCWZnvse8ZUVDn1bYJEoXfBsEr9sHx2gXnNSVS_u8WDYRx9nlrysz-3YWRluUxNYokwR5LTPBEaJdfLySAjnOhCXij9lqRAVcIrmhcE6t" width="270" height="480" />

Next select "**Choose period**" and select a period of your choice.

<img src="https://lh6.googleusercontent.com/Ha0Epp6nNoRw_Qfkl6uGW5VhzJnMNRnzTlriFNQyOtSlGyKRb0AeksF8IcUjEJmfvXDzapvqIsaLOnhAD_ZLVMn9P6A67DYMASGcrp7LtChAgWISmOQSOQ8rE09FSM1I8cJD11IF" width="270" height="480" /> <img src="https://lh3.googleusercontent.com/ITmoiByymalVO0iLOZybnx9HU4HtA63liCUPTU9EXY4pL9GmL-_FqAktF20wbLokQbgmObZOzkt10aG5pS5vRo_L5ErnAqxiDG9BMcCD_0kHgRsEu03MMR-w08dYo037EPXMbMJf" width="270" height="480" />

The information will fill in on the Android device.

- Make a note of the organisation unit/data set/period combination you have selected so you can verify the data has been uploaded later on.
- Tap on the summary box which contains the combined information of your data set, period and organisation unit selection.

<img src="https://lh3.googleusercontent.com/swuj_r__FBuDq0AGabouSI4lf0wQ0u1UlD-k3gyzi1ONX80oH_Zg92BIfaX-xwDtT1109tzgb9s4Sv0RQfx7jUE-t4h1nI3XqcuyZusHI_Q4c-iS2wMN3W2Jn5mblsh-a6pNIH-D" width="270" height="480" />

- You can now proceed to enter some data.
- Click on the Save button to send the data to DHIS2.

If you swipe down your notification tray, you will see the message "**Import process completed successfully**" indicating the data has been successfully sent to DHIS2.

(***Note**: If there is data already present in the organisation unit/period/data set combination you have selected, please try to select a different organisation unit/period combination with no data present*)

<img src="https://lh5.googleusercontent.com/rtIYIWdheMmnkSZaCSLdi29Z6SsygvqeLd0AbjKIKSHQ2sipzq7zviYQqWXNU8cZJb2frQi5X3W3yBnOeg6v-hTBbdUGEtBdu4JZIKCV8k-HDkp4yh5GAGTjvhoIKcqrYw-doc-J" width="270" height="480" /> <img src="https://lh3.googleusercontent.com/ydSEu6s1PYLaWb00m5v1XfAizCh-fet71LLxx2yHssGK5nVERTFlTtwkAIFK4fUiX1xgZsVI2Eg-prL6HUGIT0v7PuT86e8I2G4X4EISSgApqkxncr-UutQZZVpZNtaC5FEefZWr" width="270" height="480" />

- Log back into Trainingland through your web browser on your computer and make sure your data has been imported successfully online.
- Find the organisation unit/data set/period combination you selected on the Android device. In the example above this was the following:

<img src="https://lh4.googleusercontent.com/CAu26ETUFryudhyuiJnjtyy_0oTLP4rbcwmg6V8RLgBKdmk28j2nxZykIPQHInPFwnVzkvvMrNncy7mOZQQ6DGaPRE5rTc3L_oyIzB0n-_MO2PdUvbWrzTbKIaN3VyvRLMESMxun" width="624" height="153" />

- Review the data entry page and see if the data is present.

The data set should also be marked as complete and have the details of the user who completed the data entry using the android device.

<img src="https://lh6.googleusercontent.com/GebEPPtJOlhYJJTDi0cP8Z7h5Nz-EmRK7CgKpxhMz4dycsXw4EnCC4gj7-CHOBxSBjhfmCPA-mi-R5OMCCxMqqNEgNQp4dbdgGnOaATxlB5fHZlKwSWRE6eDAe1ZzlS-9be1DYRy" width="435" height="423" />

### Activity 2 - Entering data offline using an Android device

In order to start this activity, you must first ensure you are logged in to the android device with your internet connection active. If you try to log-in without an internet connection it will not work.

After you have logged in:

- Turn off the wi-fi and mobile data on your phone to ensure you no longer have any connectivity.

<img src="https://lh5.googleusercontent.com/RXTDn5WwzCyQLGal--2_Pp_V74NNTZiLkCVsw_3ewb6Vq-woUh738Kd4yO1AOdoopsQEO3ELqt6-BC9mt2B8pwsIFULkBJZs0cggoDcSwi79K0MY6EZBla0T0Fw6OLaGJufMQYCO" width="270" height="480" />

Now you can proceed to:

- select an organisation unit/period/data set combination
- and enter some data offline.

Remember not to log-out of the android app while performing this activity or you will lose the data you have entered!

<img src="https://lh6.googleusercontent.com/jX_R6mUrScqnAWe-2ytll3h58kVwgCEoAcZThqlPUnmqCx9YzbvxbfscgXigQdWggbttc9LwPknAnAwCDRS7f1SoFLMcDmXSUG_GLWgKaMDgj8sDbQ0XjIxTvKIhZJTzxaLnPQLk" width="270" height="480" /> <img src="https://lh6.googleusercontent.com/M68vnh2OSv8RCbwYMjrFv_wHQlrzgFCSKdevbdzCrO2R_6D8IaPd2-sPz3k6CMmFETCzjB6M50URd_EA8VRRWQOywunBaHgdSnY1AZoumNJnCxkJ3hb_l2h4HN-W00LhyNM8_wU4" width="270" height="480" />

- After you click on Save you will see that you do not receive any notification that the data was imported successfully.

<img src="https://lh5.googleusercontent.com/VOgnajKQIDUVHHy8V8KfjQkHlpztEQ34W1Jm0bKHWiifAbGDPkWJADkMTTERTLAsrjnZ5W3wyg7m-8Mo3uuE_5oNmb0OZzpjn-7qJE6dvr8jhLpAbU7xqiTh7LjGefXiX6L17TFO" width="270" height="480" />

- Turn your wi-fi or mobile data back on in order to upload the data.

When you turn your data back on you will receive the notification.

<img src="https://lh4.googleusercontent.com/GNIimhO_ukDL9AzMv2eeG8-FjvVZ3McSzNhAq6W_sPB5VDMoqv8n9jsk68L_RzGXz5jdbKEqVTFIRYgA6mHrQaezVzatUtk4FKulwsl_2r-Yp2OMrOBLXEroOU6qlxfFyxReYXad" width="270" height="480" />

- You can log back into Trainingland through your web browser on your computer to check if the data you entered offline on the android device is now online.

In the offline example the following organisation unit/data set/period combination was selected:

<img src="https://lh3.googleusercontent.com/7bBrztAjH7FsS9p__O5UiedsX2tPvaPo-6LLBYxSwfJWJ3xAw4z9JXTjsW7QZMjApOYY_FcruL-HKt6vCYf4RBxlWFEvMcgD876LofYjrzyCj8N2kaQtip7Qzkj9J05bZUTg26Id" width="624" height="153" />

- Review the data entry page and see if the data is present.

The data set should also be marked as complete and have the details of the user who completed the data entry using the android device.

<img src="https://lh3.googleusercontent.com/C07Lj5BIOdM6juas97Gz6FBQHhC8lNPe9A2QN0ftVJ2mDELpCTzCFJe2OvVSSCYalfxjOu_L17Rv36rLQoBolK69tSDF-FvNFZutB9P4Tjf1vp3TU2EAcs47NlF_cijDtVSglHe4" width="468" height="455" />

### Mini Quiz (not graded) - PDF and CSV Import

&gt;&gt;PDF forms can be automatically generated by DHIS 2 in order to enter data offline&lt;&lt;
(x) True
( ) False

[explanation]
PDF forms can be generated within the data set maintenance application to allow users to enter their data completely offline. There are some drawbacks to this however as changes in the PDF will not be reflected online until the PDF is either re-imported or the changes are manually made online as well.
[explanation]

&gt;&gt;DHIS 2 can natively import an Excel file in any format&lt;&lt;
( ) True
(x) False

[explanation]
DHIS 2 can natively import a CSV file. CSV files can be made in any number of applications (including Excel). The CSV format that DHIS 2 recognizes is specific, and the file that is imported must follow this format if using the built in tools that DHIS 2 provides for importing data.
[explanation]

&gt;&gt;DHIS 2 has functionality to import large amounts of data at once so this data does not need to be re-entered again&lt;&lt;
(x) True
( ) False

[explanation]
DHIS 2 supports several different file formats when importing data. Using these formats, large amounts of data can be imported together. This can be a one-time occurrence when migrating from a legacy system or a routine occurrence where data is normally being brought into DHIS 2 from other sources.
[explanation]

## Session Quiz - Data Collection

### NOTE: THIS IS A GRADED QUIZ

You are allowed 3 attempts for this quiz.

There is 30 seconds of time between each attempt, so if you don't get it right, just breathe in, watch the videos once more and carefully read the question again.

------------------------------------------------------------------------

The main function of Data Sets in DHIS2 is to: (select one)
( ) Create dynamic outputs
( ) Group together data elements for analysis
(x) Capture Data
( ) Analyse data quality

[Explanation]
Data Sets are used to capture data from different sources in DHIS2. Outputs are not directly tied to data sets and can be a mix of different data sets as needed.
[Explanation]

Some different methods for me to input data using DHIS2 include: (select one or more)
[x] Performing a manual import of data
[x] Using an Android Device
[ ] Scanning Data directly from a paper form
[x] Using the data entry app within DHIS2

[Explanation]
Different types of data collection methods were shown throughout Module 4. DHIS2 does not have the ability to scan in results from a paper form directly however.
[Explanation]

In the web data entry app, you can view the following: (select one or more)
[x] Data element history (referring to the history of a particular item)
[x] Audit trail (showing you changes made to a particular item)
[ ] The distribution of the data over a particular period, such as variance or standard deviation

[Explanation]
DHIS2 does allow for you to examine data distributions such as variance and standard deviation, but this cannot be done directly in the data entry web app. The audit trail and data element history were shown in the data entry web app session.
[Explanation]

In the web data entry app what type of quick quality checks can be performed? (select one or more)
[x] That individual minimum and maximum limits are not violated
[x] Validation rules that run user defined conditions which check that certain logical, mathematical criteria are met
[x] That values are being entered in the correct format (ie. text cannot be entered in a numerical field)

[Explanation]
In the web data entry app, various quality checks can be run while entering data. These were shown in the data entry web app session.
[Explanation]

Android Data Entry can be performed offline without an internet connection
(x) True
( ) False

[Explanation]
As long as you are logged in to the Android app (and do not log out) and you can continue to enter data directly on the Android device without an internet connection.
[Explanation]

Alternative methods of bringing data into DHIS2, such as importing the data or using PDF files, are possible
(x) True
( ) False

[Explanation]
Other methods of bringing data into DHIS2 are possible. This allows for transferring data from legacy systems or creating a data warehouse with data that is in different formats.
[Explanation]

## 4.6 - Data Sets

## Assignment - Organisation Units, Data Elements & Data Sets

### NOTE: These graded assignments belong to a series that goes throughout module 4

This series of assignments consist of 3 sets:

- Set 1: Organisation Units
- Set 2: Data Elements
- **Set 3: Data Sets**

This series will allow you to build bits by bits a data set and populate it.

At the end of the last assignment (assignment 4.6.2) you will be ask to check whether you have completed the whole series or not. This check will allow the course team members to validate the result of your assignments in DHIS2 Customization. It is only after this validation process that the final grade of this series of assignment will be confirmed. As for the other assignments, you are allowed 3 attempts.

*Note: Before the validation from the course team, the max grade for this series will be applied, but this grade is not the validated one.*

------------------------------------------------------------------------

### Assignments Module 4 - Set 3/3 - Data Sets

### Instructions

You need to be logged in [DHIS2 Customization](https://live.academy.dhis2.org/cu1/dhis-web-commons/security/login.action) to perform the following assignments.

#### Data Set Example

In the data element section you were provided with the following example data set.

| Data Element                                                                                    | Value |
| :---------------------------------------------------------------------------------------------- | :---- |
| Number of female sex workers reached with HIV prevention programs (Outreach)                    |       |
| Number of PLHIV Attended                                                                        |       |
| Number of HIV positive TB patients who are already on ART or started on ART during TB treatment |       |
| TB07.10 Number of patients with positive bacteriological results out of diagnosis               |       |
| TB07.19 Number of patients examined for follow-up                                               |       |
| MAL02.01 Malaria Slide (Tested)                                                                 |       |

### Assignment 4.6.1 - Create a default data set

#### Part 1

Using the data elements you have already created in the data element exercise, recreate this data set as a monthly data set collected at the facility level (assign the data set to the facilities you have created). Note that the Data set has already been created for you when you created your account. You can edit it and provide it with a better name if desired. You will need to edit the data sets properties, add the data elements that you have created to this data set and assign it to an organisation unit. This is to get around the issue of managing user privileges that was discussed in the video demonstration, as this data set is by default assigned to your user.

<img src="https://lh5.googleusercontent.com/JYME2zKZiGMD4wIcbBbehALqZC9lLBYnl4B-nLz3yVQDeKlKeCDwZP3Ml2wjoDtlMuTVmFD6rFlqkiJoKvZkVAXQxDgnq-bLce7dPc3PiuTjYOlCdEhD_W9urEhFggSGWITp39bh" width="389" height="245" />

#### Part 2

Navigate to data entry app and select an organisation unit which you have assigned the data set to. Select a period and the data set you have created to confirm it has been created successfully.

### Assignment 4.6.2 - Create a section data set

#### Part 1

Divide the data set above into 3 sections as depicted below. You can either modify the data set you have created in Part 1 or make a new data set if you like.

##### HIV Section

| Data Element                                                                                    | Value |
| :---------------------------------------------------------------------------------------------- | :---- |
| Number of female sex workers reached with HIV prevention programs (Outreach)                    |       |
| Number of PLHIV Attended                                                                        |       |
| Number of HIV positive TB patients who are already on ART or started on ART during TB treatment |       |

##### TB Section

| Data Element                                                                      | Value |
| --------------------------------------------------------------------------------- | ----- |
| TB07.10 Number of patients with positive bacteriological results out of diagnosis |       |
| TB07.19 Number of patients examined for follow-up                                 |       |

##### Malaria Section

| Data Element                    | Value |
| :------------------------------ | :---- |
| MAL02.01 Malaria Slide (Tested) |       |

#### Part 2

Clear your cache before checking again. Do this by going to Apps -&gt; Browser cache cleaner -&gt; Select All -&gt; Clear

Navigate to data entry and select an organisation unit which you have assigned the data set to. Select a period and the data set you have created to confirm it has been created successfully. Enter some data in the data set to confirm it will store the data correctly.

**Note: You must enter some data in the data entry app to complete the 3 components of the customization assignments.**

This check will allow the course team members to validate the result of your assignments in DHIS2 Customization.
As for the other assignments, you are allowed 3 attempts.

(x) I performed all the assignments in DHIS2 Customisation and want the course team to review the result of my work.
( ) I have not finalized all the assignments yet.

Note: It is only after this validation process that the final grade of this series of assignment will be confirmed.

## Session Quiz - Data sets

### NOTE: THIS IS A GRADED QUIZ

You are allowed 3 attempts for this quiz.

There is 30 seconds of time between each attempt, so if you don't get it right, just breathe in, watch the videos once more and carefully read the question again.

------------------------------------------------------------------------

Data Sets can be separated into user-defined sections:
(x) True
( ) False

[Explanation]
The process of creating a data set that is separated into sections was shown during the data set creation session.
[Explanation]

We can configure data sets to allow us to: (select one or more)
[x] Enter data into future periods
[x] Define what is considered a timely submission
[x] Contain as many or as few data elements as required

[Explanation]
These different parameters can all be configured when creating a data set in DHIS2. This was shown during the data set creation session.
[Explanation]

## 4.7 - Module Readings

Additional Readings (not graded):

[DHIS2 Manual: Data Import](https://docs.dhis2.org/2.25/en/user/html/import.html)

### Feedback - DHIS2 Customisation

Please take 2 or 3 minutes to complete this feedback survey once you are done with the Module 4. Your careful response will have a real impact on how courses like this are run. Thank you!

Looks like your browser doesn't support iframes
