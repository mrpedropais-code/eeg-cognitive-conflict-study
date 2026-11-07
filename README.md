# Brain Activity and Performance Under Cognitive Conflict: An EEG Study

Final-year dissertation, BSc (Hons) Psychology, Aston University (2026). Supervised by Stephen Mayhew.

**[Read the full report (PDF)](Pais_2026_EEG_Cognitive_Conflict_Dissertation.pdf)**

## The question

When people face a hard mental task, do those whose brains work harder perform better, or worse? This study recorded brain activity (EEG) and heart rate while participants completed a Stroop task, and tested whether individual differences in brain and heart responses predicted how efficiently each person performed.

## Data

- **54 participants** recruited and tested in person; final samples of 48–52 after exclusions
- **Brain activity:** EEG recorded on a Biopac MP36, synchronised to the task with a Stimtracker
- **Heart rate:** ECG recorded at the same time
- **Behaviour:** reaction times and accuracy across 144 Stroop trials per participant, collected through a task built in PsychoPy

## Method

1. **Study planning:** a power analysis in G*Power set the minimum sample at 34 participants for 80% power to detect a medium effect (d = 0.5).
2. **Cleaning:** trials outside 200–1200 ms were removed, and participants with incomplete records were excluded, using rules set before analysis.
3. **Feature extraction:** EEG was filtered into theta (4–8 Hz) and alpha (8–13 Hz) bands and power was measured as root mean square (RMS). Heartbeats were detected automatically and converted to beats per minute.
4. **Derived measure:** performance was combined into one score, the Inverse Efficiency Score (mean reaction time divided by proportion correct), so that speed and accuracy were not judged separately.
5. **Analysis in Jamovi:** paired-samples t-tests (task vs. rest), Shapiro-Wilk normality checks, Spearman correlations where normality failed, and multiple regression with multicollinearity checks (VIF).

## Key findings

- The task worked as intended: people were slower and less accurate when the word and ink colour conflicted (d = 0.86).
- Theta power rose sharply during the task (d = 1.10), alpha power fell (d = 0.35), and heart rate rose by about 3 beats per minute (d = 0.67).
- **Theta increase was the only significant predictor of performance (B = 75.03, p = .007), and in an unexpected direction:** people whose theta rose more performed *worse*. This suggests theta reflects how much effort a person needed, not how efficient their brain was.

## Limitations

- EEG used a single electrode at the back of the head, rather than the frontal sites most linked to cognitive control.
- Alpha was averaged across the whole task, which may have diluted the effect of the hardest trials.
- Heart rate in beats per minute is a broad measure; heart rate variability would be more sensitive.

## Skills shown

Study design and power analysis · data collection · signal processing · data cleaning to pre-set rules · assumption testing · regression · scientific writing

## Note on data

The participant data was collected under university ethics approval as part of a wider project and is not shared here.
