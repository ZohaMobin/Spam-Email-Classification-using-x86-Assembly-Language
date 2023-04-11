# Email Classification Program

## Introduction

This project aims to classify email messages as either ham or spam using standard classifiers. The focus is specifically on emails as they are a common medium for unsolicited messages and malicious attacks. The program uses various filters to generate a spam score and predict the category to which an email belongs.

## Methodology

The following filters are used to generate the spam score:

- Login page to verify user authentication
- Decryption of password using shift cipher
- Domain verification to ensure the email comes from a legitimate source
- Spam words detection to identify keywords that suggest spam
- Checking substring to identify patterns in the email content
- Calculation of distance between subsequent spam words
- Quick sorting of the distance array
- Naive Bayes algorithm to classify the email as ham or spam

The program is designed to be efficient and effective in identifying spam emails and protecting against malicious attacks.
