**Analysis of the UCI Heart Disease Dataset:**
  The dataset contains medical measurements from patients who were referred for cardiac evaluation.
  These were not randomly selected individuals, but people who already showed symptoms or risk factors for heart disease (e.g., chest pain, abnormal ECG, high cholesterol).
  Because of this, the dataset does not represent the general population, and the patterns observed reflect clinical behavior, not population-level heart disease prevalence.

- There are more men than women appear in the dataset. This matches historical referral patterns: men were more commonly sent for cardiac evaluation..
- Women show a higher rate of atypical angina compared to men. This reflects known clinical trends where women often present with less typical heart disease symptoms.
- Heart disease cases rise from ages ~40 to ~60, then drop sharply. Interpretation: Between 40–60, risk naturally increases, After ~60, fewer people are represented because
  older adults sometimes cannot undergo certain tests or may have already received treatment or experienced mortality. This creates an artificial decline in the dataset,
  not in real life.
- Resting ECG (restecg) patterns: For patients with heart disease, normal ECG was the most common category however for Men: more LV hypertrophy than ST-T abnormality and
  Women: the opposite trend
- Cholesterol shows a U-shaped pattern: Both very low and very high cholesterol bins showed higher rates of heart disease. Only in the 120–240 range was “no heart disease” more
  common. Again, this reflects the hospital-based sampling, where extreme values trigger testing.
