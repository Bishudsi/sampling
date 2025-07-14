# Assignment: Questionnaire Design and Sample Evaluation

## Requirements

The goal of this assignment is to practice developing and evaluating sampling materials.

### Part A - Survey Design:

Select one of the scenarios below and design a survey to meet the need(s) outlined in the prompt.

1.	In two to three sentences, describe the purpose of your survey
2.	Describe your target population, sampling frame, sampling units, and overall sampling strategy.
3.	Write a 5-10 question survey to address your chosen scenario below.

##### Scenarios
1.	You work in the Human Resources Department at a large tech company. Over the past few months, the company has been experiencing a high turnover rate across many of its departments, specifically within the entry- and lower-level positions. The company wishes to understand why this turnover is happening, and what changes need to occur to improve employee satisfaction.
2.	You work for a Canadian national political party during a federal election. Throughout the campaign period, your party has seen relatively high approval ratings, but an opposing party is also polling favorably and may still have a chance to win the election. You are one month away from the election and you want to understand what voters want from your party and its leader in order to maintain your lead and eventually win the election.
3.	You are a student researcher in the sociology department at the University of Toronto. You are working on a research project that concerns the relationship between music taste and age. This involves both comparisons between different people of different ages and comparisons of the same individual at different ages during their lifetime. You wish to understand to what extent age influences music taste, specifically as it relates to perceptions of popular music. Your results will be written into an academic paper that you hope to publish.

### Part B - Survey Evaluation:

For the **Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33)**, conducted by Statistics Canada find any and all available documentation for the data gathered and identify and describe the survey features indicated below.

1. Sample type
   A cross-sectional probability design is used in the survey and uses a startified 2 stage sampling design

2. Sample size
   The total sample size is 50000 households

3. Target population
   Persons aged 15 and over living in private households in Canada across the 10 provinces while excludes full-time (residing for more than six months) residents of institutions.

4. Sampling frame
   Dwelling frame from Statistics Canada, Telephone number frames (landline and cellular), Administrative data (e.g., census, billing files)

5. Survey mode(s) 
   Electronic questionnaire (EQ) – online, self-administered, CATI (Computer-Assisted Telephone Interviewing), conducted in both English and French.

6. Timeline
   04 Sep 2018 to 28 Dec 2018

7. Response rate
   The overall response rate is 41.9%

8. Weights
   The person-level weight (WGHT_PER) allows estimation of the number of Canadians aged 15+ with specific characteristics. Bootstrap weights are included for variance estimation. 
   
   Weights are adjusted to align survey estimates with independent age-sex distributions by province, improving representativeness and precision.

9. Data processing
   Data were processed using the SSPE system, ensuring consistent, high-quality outputs through standardized procedures. Automated and manual edits (e.g., family, consistency, and flow edits) were applied at both macro and micro levels. The CATI system included built-in checks for valid responses and skip patterns, with unresolved issues reviewed by head office. All records underwent extensive validation to ensure data integrity.

10. Cleaning, imputation, etc
    Personal income was primarily obtained via tax data linkage (T1FF)
    Donor-based imputation primarily used for Score-based matching of similar respondents
    Mean imputation used when donor pool is insufficient
    Multi-step imputation is used for covering Income, Formal & informal volunteering, Donations variables.

11. Sources of error
    Sampling Error:  Estimates vary from sample to sample; quantified using bootstrap weights.
    Non-Sampling Errors:
        Coverage Error: Excludes institutionalized populations and households without telephones; under/over-coverage possible.
        Non-Response Error: 41.9% response rate; weights adjusted using administrative data to reduce bias.
        Response Error: Inaccurate or biased answers due to recall or misunderstanding.
        Processing Error: May occur during data entry, coding, or editing despite quality controls.

12. Limitations, known biases, etc
    Excludes residents of the territories, institutions, and households without telephones.
    With a response rate of 41.9, bias may persist despite weighting and adjustments using administrative data.
    Respondents may misremember or underreport volunteering, donations, or participation over the past 12 months.
    Responses may vary between online and telephone modes, affecting consistency.
    Imputed values, especially for income or volunteering, may not fully reflect actual respondent behavior.
    Susceptible to social desirability bias, particularly for charitable and civic behavior.

13. Link to documentation and any additional sources used
    https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&Id=796234

# Your Changes

## Part A - Survey Design: 

The number of your chosen topic: `#`

Describe the purpose of your survey:

## Identify Factors Driving Turnover
The survey is intended to learn what aspects of the work environment, management practices, compensation, job expectations, or growth opportunities might be the cause for employees’ decisions to leave.

## Collate Feedback from Employees
By collecting feedbacks directly from current and recently departed employees, would help to capture insights about their experiences, concerns, and motivations.

## Support Data-Driven Decision Making
The insights gathered from this survey will enable the Human Resources department and company leadership to make informed, strategic decisions regarding organizational policies, internal communication, workload management, and career development initiatives. These efforts will be directed toward fostering a more supportive, engaging, and sustainable workplace culture, ultimately enhancing employee retention and overall satisfaction.

Describe your target population, sampling frame, sampling units, and observational units:

## Target Population
The target population includes all employees within the company, primarily the entry and lower-level staff across all departments.

## Sampling Frame
The sampling frame will be company’s HR database, which contains a current and historical list of employees, including job level, department, employment status, and contact information.

## Sampling Units
The sampling units are the individual employees selected from the sampling frame to receive the survey.

## Observational Units
The observational units are the individual employees who were part of Sampling Units and have completed the survey.

Your 5-10 question survey:
```
1. On a scale of 1 to 5, how satisfied are you with your overall experience working at the company?
   (1 = Very Dissatisfied, 5 = Very Satisfied)
2. Do you feel you have clear opportunities for career advancement within the company?
   Yes
   No
   Not sure
3. How would you rate the support you receive from your direct supervisor or manager?
   (1 = Very Poor, 5 = Excellent)
4. Do you feel your workload is manageable and aligned with your job expectations?
   (1 = Not at all manageable, 5 = Completely manageable)
5. To what extent do you feel valued and recognized for your contributions?
   (1 = Not at all, 5 = Very much)
6. What were the main reasons you considered or decided to leave (or would consider leaving) the company?
   
7. What changes or improvements would make you more likely to stay with the company longer?

8. How likely are you to recommend this company as a good place to work to others?
   (1 = Not at all likely, 5 = Extremely likely)

9. write your question here... (optional)
10. write your question here... (optional)


## Part B - Survey Evaluation:

Identify and describe survey features:

```
## Target population
   The survey focused and is aimed towards the entry level and low level staff, as to resolve the level with focus on the understanding the reason of attribution within those roles.

## Length of Survey
   Survey is designed to complete within 5-7 minutes, with hope to receive the higher rate of survey completion.

## Anonymity and Confidentiality
   The survey is performed with Anonymity and confidentiality to ensure its unaffected and feebacks are honest.

## Participation is voluntary
   Current and Past Employees selected in sampling unit are free to participate or not in the survey.

## Time Frame
   Survey should be closed or completed within time frame (may be with 7 days)

## Disclosure on Data Usability and Reporting
   Results will be analyzed by HR and leadership team.
```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 29/06/2025`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
