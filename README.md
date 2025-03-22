# 🧠 Effects of Mental Health on Substance Use 💊

# 👀 See the code [HERE]()

The original data used in this project can be found in the "original_nsduh_data" folder and is labelled "NSDUH_2023.sav".
The cleaned data containing only the relevant variables is labelled "clean_nsduh_data".

## 📊 Skills Showcased


## 🤷 Research Question
How does mental health influence substance use in lesbian, gay and bisexual (LGB) individuals compared to their non-LGB counterparts?

NOTE: Since there are no questions asking about if respondents are transgender, we will only be focusing on LGB rather than LGBT. Future research should take the transgender population into account.

## 🔎 Hypotheses
1. LGB individuals who have experienced psychological distress in the past month are more likely to engage in regular substance use (alcohol, cigarette, and marijuana) compared to non-LGB individuals.
2. LGB individuals who report experiencing a past year major depressive episode will be more likely to engage in regular substance use (alcohol, cigarette, and marijuana) compared to non-LGB individuals.
3. LGB individuals who have experienced serious psychological distress in the past month will be more likely to have a higher frequency of binge drinking in the past month compared to non-LGB individuals.
4. LGB individuals who have had suicidal thoughts, plans, or attempts in the past year will be more likely to have a substance use disorder compared to non-LGB individuals.

## 📖 Variables
The data found in this project is from the [2023 National Survey on Drug Use and Health](https://www.samhsa.gov/data/data-we-collect/nsduh-national-survey-drug-use-and-health/national-releases/2023). This survey measures substance use, mental illness, and treatment in the civilian non-institutionalized population aged 12 or older. For the purposes of this project, however, I will only be focusing on adults. 

The final dataset after cleaning and merging both waves had 40,389 rows and 22 columns.

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

### 4. **CIG30USE**- during the past 30 days, on how many days did you smoke part of or all of a cigarette?
Values:

* Range 0-30

### 5. **NICDEPEND**- nicotine dependence in past month based on criteria according to the Nicotine Dependence Syndrome Scale and the Fagerstrom Test of Nicotine
Values:

* 0 = No
* 1 = Yes

### 6. **ALC30USE**- number of days respondent had at least one drink of alcohol in the past 30 days
Values:

* Range 0-30

### 7. **ALCBINGE30**- number of days respondent had 4+ drinks in the past 30 days
Values:

* Range 0-30

### 8. **MJ30USE**- number of days respondent used marijuana/cannabis in any form in the past 30 days
Values:

* Range 0-30

### 9. **ALCDISORDER_YEAR**- whether respondent fits DSM-5 criteria for alcohol use disorder
Values:

* 0 = No
* 1 = Yes

### 10. **MJDISORDER_YEAR**- whether respondent fits criteria for marijuana use disorder
Values:

* 0 = No
* 1 = Yes

### 11. **PSYCH_DISTRESS_30**- experienced serious psychological distress in the past month
Values:

* 0 = No
* 1 = Yes

### 12. **SUICIDE**- recoded past year thoughts, plans OR attempts of suicide
Values:

* 0 = No
* 1 = Yes, one or more (thoughts, plans, attempts, or some combination)

### 13. **MAJORDEPRESSIVE_YEAR**- past year major depressive episode (MDE)
Values:

* 0 = No
* 1 = Yes

## 📉 Findings
