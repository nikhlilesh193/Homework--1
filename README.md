Homework 1 
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Student Name: Nikhilesh Katakam 

700#: 700772365

Course: CS5760 – Natural Language Processing 

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Submission Overview
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
This repository contains the complete solution for Homework 1 of CS5760. All questions (Q1–Q5) are implemented and explained in the provided source files.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Files in This Repository
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Homework1/

Homework 1_Solution.py

Homework 1_Solution.pdf

README.md

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

File Descriptions

Homework 1_Solution.py Contains all Python code required for Homework 1, including:

Regex solutions (Q1)

Byte Pair Encoding (BPE) implementation (Q2)

BPE training and segmentation on a paragraph

Telugu tokenization (Q5)

Homework 1_Solution.pdf Contains written explanations, outputs, and answers for:

Regex questions

Manual BPE steps

Bayes Rule explanations

Add-1 smoothing calculations

Telugu tokenization analysis and reflection

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Question-wise Summary

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Q1. Regular Expressions


implemented regular expressions to match:

U.S. ZIP codes

Words not starting with capital letters

Numbers with optional signs, commas, decimals, and scientific notation

Variants of the word "email"

Interjections such as go, goo, gooo

Lines ending with a question mark and optional closing punctuation

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Q2. Byte Pair Encoding (BPE)

Manually performed BPE merges on a toy corpus

Implemented a mini-BPE learner in Python

Tracked bigram frequencies and vocabulary growth

Demonstrated segmentation of seen, unseen, and invented words

Explained how subword tokenization solves the OOV problem

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Q3. Bayes Rule Applied to Text

Explained P(c), P(d | c), and P(c | d)

Justified why the denominator P(d) can be ignored during classification

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Q4. Add-1 (Laplace) Smoothing

Computed likelihood denominators

Calculated conditional probabilities for seen and unseen words

Demonstrated how smoothing prevents zero probabilities

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Q5. Programming Question – Telugu Tokenization

Language Used: Telugu

Steps performed:

Naïve space-based tokenization

Manual token correction handling punctuation and suffixes

Tokenization using Indic NLP Library

Comparison between naive, manual, and tool-based tokens

Identification of multiword expressions (MWEs)

Linguistic reflection on tokenization challenges

Key challenges discussed:

Agglutination and morphology

Punctuation attachment

Multiword expressions

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
How to Run the Code
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

python "Homework 1_Solution.py"

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Tools & Libraries Used
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Python 3

indic_nlp_library

collections (Counter)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
