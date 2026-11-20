# Am I Exam-Ready? (A1 German)

A 14-question check across vocabulary, grammar and reading. It estimates readiness for an A1 exam (Goethe or ÖSD), breaks the result down by skill, and names the 3 gaps to fix before booking.


## How readiness is calculated

| Step | Rule |
|---|---|
| Skill accuracy | Correct ÷ questions, per skill (Vocabulary, Grammar, Reading) |
| Overall accuracy | Correct ÷ all questions |
| Weakest skill | The lowest of the three skill accuracies |
| Readiness | 60% × overall + 40% × weakest, as a score out of 100 |
| Ready | Readiness ≥ 80, every skill ≥ 70%, and at most 1 confident wrong answer |
| Borderline | Readiness ≥ 60 but not Ready |
| Not yet | Readiness < 60 |

Why these rules: the exam is passed or failed across skills, so a strong average should not hide a weak skill. The 40% weight on the weakest skill and the 70% floor enforce that. The "sure but wrong" rule reflects that confident errors are harder to catch than guesses.

Worked example: vocabulary 4 of 4, grammar 4 of 6, reading 3 of 4. Overall is 11 of 14 (0.786). Weakest is grammar (0.667). Readiness = 0.6 × 0.786 + 0.4 × 0.667 ≈ 74, which is Borderline.

## What it does not measure

- Listening, writing and speaking. The official A1 exam tests all four.
- Exam-day factors such as timing and nerves.
- Statistical precision. 14 questions is a small sample, so the score is a signal, not a guarantee.
- Whether the weights (60/40) and thresholds (80, 70%) predict real exam results. They are judgment calls and have not been validated against learner outcomes.

## Next steps (v2)

1. Add listening (audio clips) and a writing task with a self-check rubric.
2. Grow the bank to 50+ questions and rotate them so repeat attempts do not just memorise answers.
3. With learner consent, log scores and exam outcomes, then test whether the formula predicts passing better than simple accuracy.

## Stack

Single HTML file, vanilla JavaScript, inline CSS. No dependencies.
