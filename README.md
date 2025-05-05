# 🍺 Effects of Substance Use on Mental Health 🧠 

# 👀 See the project [HERE](https://nimj34.github.io/Effects-of-Substance-Use-on-Mental-Health-by-Sexual-Orientation/)

## TABLEAU DASHBOARD IN PROGRESS

The original data used in this project can be found in the "original_nsduh_data" folder and is labelled "NSDUH_2023.sav".
The cleaned data containing only the relevant variables is in the file labelled "clean_nsduh_data".

## 📊 Skills Showcased
R, Data Analysis, Data Visualization, Descriptive Statistics, Binary Logistic Regression, Plot Diagnostics, Literature Review, Predictive Probabilities

## 🤷 Research Question
How does substance use influence mental healht outcomes in lesbian, gay and bisexual (LGB) individuals compared to their non-LGB counterparts?

NOTE: Since there are no questions asking about if respondents are transgender, we will only be focusing on LGB rather than LGBT. Future research should take the transgender population into account.

## 🔎 Hypotheses
1. LGB individuals who engage in regular substance use (alcohol and marijuana) in the past month are more likely to have experienced psychological distress in the past month compared to non-LGB individuals.
2. LGB individuals who engage in regular substance use (alcohol and marijuana) are more likely to report experiencing a past year major depressive episode compared to non-LGB individuals.
3. LGB individuals who have had a substance use disorder in the past year are more likely to have experienced suicidal thoughts, plans, and/or attempts in the past year compared to non-LGB individuals.

## 📉 Key Findings
The hypotheses surrounding the relationship between substance use (alcohol and marijuana) and mental health outcomes for LGB individuals were not supported likely due to the fact that LGB individuals only made up around 14.4% of the sample. 

Individuals who have experienced a major depressive episode in the past year are nearly 8 times more likely to have experienced severe psychological distress in the past month. 

Those with suicidal plans, thoughts, or attempts are 5.5 times more likely to experience psychological distress.

Individuals with a hitory of suicidality in the pat year are 12 times more likely to also report experiencing a past-year major depressive episode.

LGB individuals were around twice as likely as non-LGB individuals to experience severe psychological distress, major depressive episodes, and suicidality.

People with more frequent marijuana use are significantly more likely to experience psychological distress.

People with alcohol or marijuana use disorders are significantly more likely to experience suicidality.

## 📖 Variables
The data found in this project is from the [2023 National Survey on Drug Use and Health](https://www.samhsa.gov/data/data-we-collect/nsduh-national-survey-drug-use-and-health/national-releases/2023). This survey measures substance use, mental illness, and treatment in the civilian non-institutionalized population aged 12 or older. For the purposes of this project, however, I will only be focusing on adults. 

The final dataset after cleaning and merging both waves had 40,389 rows and 24 columns.

### 1. **SEX_ORIENT**- sexual orientation of respondent
Values:

* 1 = Heterosexual
* 2 = Gay/Lesbian
* 3 = Bisexual
* 4 = Other
* 5 = Questioning

### 2. **SEX**- sex at birth of respondent
Values:

* 1 = Female
* 2 = Male

### 3. **AGE**- age category of respondent
Values:

* 2 = 18-25 years old
* 3 = 26-34 years old
* 4 = 35-49 years old
* 5 = 50-64 years old
* 6 = 65+

### 4. **ALC30USE**- number of days respondent had at least one drink of alcohol in the past 30 days
Values:

* Range 0-30

### 5. **MJ30USE**- number of days respondent used marijuana/cannabis in any form in the past 30 days
Values:

* Range 0-30

### 6. **ALCDISORDER_YEAR**- whether respondent fits DSM-5 criteria for alcohol use disorder
Values:

* 0 = No
* 1 = Yes

### 7. **MJDISORDER_YEAR**- whether respondent fits criteria for marijuana use disorder
Values:

* 0 = No
* 1 = Yes

### 8. **PSYCH_DISTRESS_30**- experienced serious psychological distress in the past month
Values:

* 0 = No
* 1 = Yes

### 9. **SUICIDE**- recoded past year thoughts, plans OR attempts of suicide
Values:

* 0 = No
* 1 = Yes, one or more (thoughts, plans, attempts, or some combination)

### 10. **MAJORDEPRESSIVE_YEAR**- past year major depressive episode (MDE)
Values:

* 0 = No
* 1 = Yes

### 11. **ALCFREQ**- non-frequent (drank less than or equal to 4 days in past month) vs frequent (drank more than 4 days in past month) drinkers
Values:

* 0 = Non-Frequent Drinker
* 1 = Frequent Drinker

### 12. **MJFREQ**- non-frequent (used marijuana less than or equal to 4 days in past month) vs frequent (used marijuana more than 4 days in past month) marijuana user
Values:

* 0 = Non-Frequent Marijuana User
* 1 = Frequent Marijuana User
