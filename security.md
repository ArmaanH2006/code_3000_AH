# Security Statement

## Intended Users
This repository contains my coursework for CSE 3000: Contemporary Issues in
Computer Science and Engineering. It holds Python scripts and Jupyter notebooks
for the even-numbered assignments (a bot predictor, model bias analysis with
SHAP, data de-anonymization, and sustainability calculations) along with small
course-provided datasets. The intended users are me, my instructor, and my TAs,
who access the repo through Gradescope's GitHub connection for grading and
feedback. It is not intended for production use or for the general public.

## Risk Assessment
- **Data:** The CSV files in `mod02_data`, `mod04_data`, and `mod06_data` are
  course-provided sample or synthetic data and do not contain real personal
  information. If they fell into the wrong hands, the main concern would be
  misuse of the techniques practiced here, such as the de-anonymization methods
  from Module 6 being applied to real individuals. Because the data is synthetic,
  the impact is low.
- **Code:** The scripts perform data analysis and modeling and do not handle
  passwords, API keys, or other credentials. If someone gained access, they could
  copy my work (an academic integrity concern) or alter it if they had write
  access, which could affect my grades.
- **Overall risk:** Low, but not zero, so I follow basic safeguards.

## Steps Taken to Secure the Repository
- **CODEOWNERS file:** Designates me as the owner of the repository's files so
  that changes are tied to my review.
- **.gitignore:** Keeps the virtual environment (`3000-env/`), `__pycache__/`,
  and other local files from being committed.
- **No secrets in the repo:** I do not commit API keys, tokens, or credentials.
- **Access control:** The repo is private and shared only with my instructor
  and TAs.
- **Branch protection:** A ruleset is not necessary because this is a
  single-contributor course repo with no sensitive data.
- **Account security:** My GitHub account uses two-factor authentication.