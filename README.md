# Policy Text Analytics — Word Frequency Analysis

This project performs a simple Natural Language Processing (NLP) analysis on a policy document from the Department of Education’s Policy and Advisory Library (PAL).
(https://www2.education.vic.gov.au/pal/early-childhood-education-and-care-services-at-schools/policy)

The goal is to identify the most important themes in the policy by counting and ranking the most frequently used meaningful words.

By removing common English sight words (e.g., “and”, “the”, “with”) and reducing basic plural forms, the analysis highlights the key focus areas of the policy.

# Why This Project Is Useful

Policies can be long and complex.
This script helps extract the core message by:

✔ Summarising content without manual reading

✔ Highlighting main topics and stakeholder roles

✔ Supporting quick understanding for educators and analysts

✔ Providing a foundation for more advanced NLP (topic modeling, summarisation, etc.)

# Skills Demonstrated

| Area | Description |
|------|-------------|
| Python programming | String manipulation, loops, list & dictionary operations |
| File handling | Reading and cleaning raw text data |
| Data preprocessing | Lowercasing, stop-word removal, simple plural reduction |
| NLP fundamentals | Tokenization and word frequency analysis |
| Sorting & analysis | Ranking most common terms to reveal document themes |

This showcases practical data transformation and text analytics skills — useful for Data Analyst and Machine Learning roles.

# Example Outcome (Top 20 Words)
For the "Early Childhood Education and Care Services at Schools" policy, the top terms include:
service, school, ecec, early, childhood, education, enrolment, kindergarten, children, provider, 
learning, site, manager, principal, care, management, policy, building, elv, support.

These results clearly point to:

- Early childhood education services
- School-based delivery
- Management and enrolment responsibilities

# How to Run

Save a text policy file (e.g. policy.txt) in the project folder

Save a stop-word list file (sightword.txt)

Run the script and input the file names when prompted:

*python word_freq.py*

The program will output the most frequent meaningful words sorted by importance.

# Future Enhancements

- Automated punctuation removal
- Better plural/lemma handling (e.g., families → family)
- Visualisation of results (bar chart / word cloud)
- Support for multiple documents for policy comparison
