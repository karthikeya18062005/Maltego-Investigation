Spam Email Investigation Using Maltego

Introduction

This project documents an investigation conducted using Maltego to analyze a suspicious spam email. The investigation uncovered a database containing 46,000 leaked email addresses, linked to malicious activity.

Objective

The primary goal of this investigation was to trace the origins of a spam email and identify compromised data sources.

Tools Used

Maltego (OSINT Tool)

HaveIBeenPwned (Data breach checker)

IPQS (Email deliverability and risk analysis)

Findings

46,000+ leaked email addresses were found in a file named office46k.txt hosted on a malicious IP (83.166.240.72).

Two key email addresses identified as compromised:

admin@vagaro.com

Greg.Mason@vnabwh.com

Multiple malicious URLs and breached domains were linked to this data exposure.

Investigation Process

Spam Email Analysis: Identified key email addresses from the spam email.

Entity Discovery in Maltego: Used Maltego transforms to expand connections from the spam email.

Data Correlation: Linked domains, IP addresses, and document sources.

Breach Confirmation: Verified compromised emails through HaveIBeenPwned and IPQS.

Conclusion

This investigation demonstrates how Maltego can efficiently analyze spam emails, track threat actors, and reveal compromised data sources. Users are advised to:

Regularly check their emails on HaveIBeenPwned.

Avoid clicking unknown links in suspicious emails.

Educate themselves about phishing tactics and social engineering attacks.

Disclaimer

This project is intended for educational purposes only. The data uncovered was already publicly available, and no unauthorized access was attempted.

How to Run the Analysis

Download the Maltego graph file from the Graphs folder.

Open Maltego and import the .mtgx file.

Follow the steps outlined in the investigation process.

Contact

For any queries or collaborations, feel free to connect with me via:

Email: karthikeya18062005@gmail.com

LinkedIn: https://www.linkedin.com/in/kattekolasomasekharakarthikeya/
