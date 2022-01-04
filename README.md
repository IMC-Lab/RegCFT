# RegCFT
Data for Frontiers Psychology paper Parikh et al., 2022, titled "The efficacy of downward counterfactual thinking for regulating emotional memories in anxious individuals"

## Uplaoded Files
1) Cleaned data file, titled "longForm_data_summary.csv"
2) End Questionnaire data file, titled "EndQ_Summary.txt"

Both are described in detail below. Analysis R code also available upon request (email <nparikh@unc.edu>)


### Cleaned Data File
This file has separate rows for each memory provided per participant. The file does not include participants that were excluded due to attrition or task compliance concerns. A description of the column variables is provided below.

#### Variables (columns):
  - Condition (cond) is provided per memory, where 1 = downward counterfactual thinking. 2 = temporal distancing, and 3 = simply remember what occurred
  - Frequency (freq), Valence (val), Arousal (ar), Detail (det), Regret (reg): phenomenological ratings of the memory, on a scale of 1-7. If the column is labeled [rating]_1, that means it was done at the time of initial memory retrieval, during Session 1. [rating]_3 ratings were taken after memory recall during Session 3
  - Source memory accuracy (acc) measures whether the participant accurately identified which simulation condition was used for each memory. 1 = correct, 0 = incorrect
  - Emotion Regulation Questionnaire (ERQ_reap and ERQ_supp) scores are separated based on two subscales, the reappraisal and suppression subscales. Each participiant has a single score per subscale, which is why all values are the same within an individual participant.
  - State-Trait Anxiety Questionnaire (STAI) Trait score is used. Each participiant has a single score, which is why all values are the same within an individual participant.
  - Social Desirability Scale (SDS) measures how much participants attest to socially desirable characteristics. Each participiant has a single score, which is why all values are the same within an individual participant.
  - Session 2 Pre-simulation EMG score (S2_pre_EMG) and Session 2 Post-simulation EMG score (S2_post_EMG) are EMG measures of the average 1.5 seconds prior to stimulus presentation (pre) and 8 seconds following stimulus onset (post) during Session 2 of the experiment. Session 1 was conducted online and thus does not have EMG measurements, and Session 3 lacked proper counterbalancing and thus EMG measurements are confounded with effects of habituation over time.


### End Questionnaire Data File
This file contains the data from the cognitive judgment questions answered at the end of the experiment. Each participant was asked to answer the following multiple choice questions (worded differently here than to participants):
1) Which technique do you feel was the most effective for you? Counterfactual Thinking (CFT), Temporal Distancing (TD), or Remembering (Rem)
2) Which technique was the easiest to use? CFT or TD
3) Which technique (if any) will you use outside of this experiment to help regulate your emotions? CFT, TD, or Neither (None)
Note that the responses from participants 1-3 did not record correctly, and thus are labeled NA
