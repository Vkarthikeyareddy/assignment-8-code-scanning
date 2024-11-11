# Answers to Assignment 8 Part 3

Add your answers to the questions in Assignment 8 Part 3, Step 2 below. 

## Vulernability Remediation:
### Vulnerability 1: 
1. Which package or library are you addressing?
Package involved is PyYAML, specifically version 5.1

2. Which CVE is linked to this vulnerability?
CVE-2019-20477

3. What remediation steps do you suggest?
a. Upgrade the PyYAML package to at least version 5.2, as it resolves the critical vulnerability involving deserailization of untrusted data.
b. Update the requirements.txt or any other dependency management file in your project to specify the updated version (>=5.2).
c. Run pip install --upgrade PyYAML to ensure the environment uses the secure version.

### Vulnerability 2:
1. Which vulnerability are you addressing?
The vulnerability being addressed is Improper Input Validation in PyYAML version 5.1.

2. Which CVE is linked to this vulnerability?
CVE-2020-14343

3. What remediation steps do you suggest? 
a. Upgrade the PyYAML package to version 5.4 or higher to fix the vulnerability related to improper input validation.
b. Update the requirements.txt or any relevant dependency management file to reflect PyYAML>=5.4.
c. Run the command pip install --upgrade PyYAML to ensure the environment is using the fixed version.
