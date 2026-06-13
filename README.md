**🚢 Titanic Dataset — End-to-End Data Analytics ProjectProject Overview**
This is a complete end-to-end Data Analytics project built on the Titanic dataset.

The project covers everything from raw data inspection all the way to a professional

final report — including data cleaning, null value handling, exploratory data analysis,

feature engineering, and visual storytelling.

-----------------------------------------------------------------------------------------------------------
**🎯 Objective**

The goal of this project was to take the raw Titanic dataset, clean it thoroughly,

analyse it deeply, and present meaningful insights about passenger survival patterns

in a professional report format.

-----------------------------------------------------------------------------------------------------------
🔄 Project Pipeline — What We Did
**🔍 Stage 1 — Data Inspection**
Loaded and explored the raw Titanic dataset (1309 rows, 12 columns)

Identified numerical and categorical columns

Detected actual categorical columns based on unique value count

Calculated null counts and null percentages for every column

-----------------------------------------------------------------------------------------------------------
**🧹 Stage 2 — Null Value Handling**
Applied a 5% threshold strategy to split columns into two groups:

Less than 5% nulls → Auto-filled (no user input needed)

More than 5% nulls → Interactive fill with visual comparison

For auto-fill:
Continuous numerical columns → filled with Mean
Binary / low-cardinality columns → filled with Mode
Categorical / text columns → filled with Mode

For interactive fill:

Compared 4 strategies: Mean, Median, Mode, Random

Used KDE plots for visual distribution comparison

Used Standard Deviation for statistical comparison

User selected the best strategy per column

-----------------------------------------------------------------------------------------------------------

Columns handled:

Age 20.09% Missing Data

Cabin 77.46% Missing Data

Survived 31.93% Missing Data

Embarked 0.15% Missing Data

Fare 0.07% Missing Data

-----------------------------------------------------------------------------------------------------------
**⚙️ Stage 3 — Feature Engineering**

Created FamilySize = SibSp + Parch + 1

Created IsAlone flag for solo travellers

Extracted Title from passenger names (Mr, Mrs, Miss, Dr, etc.)

Created AgeGroup categories (Infants, Children, Teens, Adults, Elder Adults, Senior Citizens)

Extracted Surname from Name column

Created TicketType from Ticket column

-----------------------------------------------------------------------------------------------------------
**📊 Stage 4 — Exploratory Data Analysis (EDA)**

Survival rate by Passenger Class (Pclass)

Survival rate by Gender (Sex)

Survival rate by Age Group

Survival rate by Embarkation Port
Survival rate by Family Size

Age distribution by Survival (KDE plot)

Survival Rate by Age Group & Sex


Pairplot of Key Variables (Age, Fare, Pclass, FamilySize)

Complete multi-chart dashboard

-----------------------------------------------------------------------------------------------------------
**📝 Stage 5 — Final Report**
Professional PDF report covering all stages
Includes charts, tables, observations, and decisions for every step
Final conclusions and business recommendations

-----------------------------------------------------------------------------------------------------------
📊 Key Findings from Analysis

Gender: Females survived at a significantly higher rate than males

Class: 1st class passengers had the highest survival rate across both genders

Age: Infants (especially female infants) had the highest survival rate

Family Size: Passengers travelling with 1–2 family members survived more than solo travellers or large 
groups

Embarkation: Southampton (S) had the most passengers; Cherbourg (C) had the highest survival rate

Fare: Passengers who paid zero fare had the highest death rate

Age Group: Passengers between ages 15–50 survived the most

------------------------------------------------------------------------------------------------------------
**💡 Business Recommendations**
Based on the analysis of the Titanic survival data:
Emergency evacuation procedures should prioritise vulnerable groups such as infants, children, and elderly passengers
Equal lifeboat access should be ensured across all passenger classes — not just 1st class
Passenger safety training should be standardised regardless of ticket class
Capacity planning should account for family groups as passengers travelling with small families showed higher survival rates
Port authorities at Southampton should implement stricter safety checks given the highest passenger volume
