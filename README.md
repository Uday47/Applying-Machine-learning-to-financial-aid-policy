## Applying-Machine-learning-to-financial-aid-policy
**Problem Statement**: You are given a dataset containing details of Financial aid applicants such as their Electricity bill, School_fees, Income class they belong to etc. We can automate the Financial Aid approval process which will save both time and effort. 

We will build a simple logistic regression algorithm that can correctly classify two things.

1.   Is the applicant eligible for Financial aid.
2.   And how much should be the waiver.

I've also uploaded the demo financial aid dataset. 

**Financial Aid policy**

It and not abused by people who think of it as an entitlement. This report suggests a financial aid model implementation that can improve the chances of identifying the genuineness of the applicant. The report suggests slight modifications to the existing aid model to make it more effective. The candidates are asked to submit their recent electricity bill, school fees amount along with an income certificate. Collectively, these documents can add much more weight to the genuineness of candidate’s need. Those who can’t submit these can write a mail to the office or can follow the existing model. The reason I chose these attributes is

1. Electricity Bill – I chose electricity consumption bills over other bills like water bill and LPG bill because most of the rural areas have access to electricity than they have to tap water and LPG. There are many countries that use electricity consumption data for socio-economic classification.

2. School fees – Education is one thing where no one wants to compromise. There are people who study at international schools and pay 2 lakh rupees a year and there are those who study at government schools and pay 200 rupees a year as their tuition fees.
hough there can be exceptions who study on scholarships, this attribute can provide much better insight into the idea.

3. Income certificate – Income certificates are one of the mandatory documents that every household has and requires. These can be used to demonstrate need of aid. They are many complex socio-economic scales. But for simplicity we’ll use the below scale

**About the dataset**

*Name*

This column gives the names of the applicants who’ve applied for the financial aid. It has 100 male and 100 female unique names.

*Electricity Bill*

This column gives the electricity bill of the respective applicant. In this dataset, the values range from 0-5000 INR

*Income Class*

This column provides the info about the income class the applicant belongs to. There are many complex Socio-Economic scales out there. But for simplicity we’ve used the following scale (Family income in INR).

· Poor (1)- Annual income less than 80000 PA

· Lower Class (2) - Annual income between 1 lac pa - 3.5 lac.

· Lower middle class (3) - 3.75 lacs to 9 lacs.

· Upper middle class (4) - 10 lacs to 25 lacs

· Rich lower bracket (5) - 27 lacs to 50 lacs.

· Rich upper bracket (6) - 55 lacs to 1.5 crore

*School fees*

This column gives the information about the School fees the applicant pays to the institution they study at. The scale ranges from 0-1 Lac INR

*Exception*

This column gives info whether the applicant is an exception. (Special cases are when the income of the candidate is relatively high but they show genuine need of aid financial aid. Example: All the money is being spent on an ailing family member.

*Aid_eligibility*

This column provides information whether the candidate eligible for aid or not?

*Aid_percent*

This column gives the grant amount the applicant has received (percentage of amount discounted from the fees).
