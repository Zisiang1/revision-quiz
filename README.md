# revision-quiz

Two multiple-choice revision quizzes in a single self-contained page:

- **ICT2212 Quiz 1** - Ethical Hacking, weeks 1-5 (60 questions, 5 topics)
- **INF2001 Quiz 1** - Intro to Software Engineering, weeks 1-5 (60 questions, 9 topics)

Switch quizzes with the tabs at the top. Each quiz keeps its own progress, score, flagged
questions and topic filter.

## Features

- Multiple-choice mode (keys `A`-`D` or `1`-`4`) with immediate feedback and the rationale
- Typed-answer mode: write your answer, reveal the model answer, then mark yourself
- Topic filter, shuffle, retry-only-what-you-missed, summary broken down by topic
- Progress saved in the browser (localStorage), per quiz
- Light/dark theme; works offline once loaded

No build step, no dependencies, no tracking - one HTML file.

## Notes

The page is built from `data/*.json` by `build.py`, which is not published here.
Questions are paraphrased revision prompts derived from lecture material, not reproductions
of it. This site is public: nothing sensitive should be committed to it.
