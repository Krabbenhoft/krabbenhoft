[Back to Portfolio](./)

Email Willaim Littleton at wlittleton@csuniv.edu for implementation details.

Senior Project: Automated Data Spillage Prevention & Retention Policy Enforcement for Hybrid File Storage
===================

-   **Class:** Senior Project
-   **Grade:** A
-   **Language(s):** Python
-   **Source Code Repository:** [krabbenhoft/csci-499](https://github.com/Krabbenhoft/csci-499)  
    (Please [email me](mailto:isaac.krabbenhoft@gmail.com) to request access.)

## Project description
The purpose of the project is to create a data governance pipeline that uses free open source tools to automatically scan files spread accross both on premises SMB shares and remote files in OneDrive.

### Statement of Purpose
There is substancial data stored accross both on premises and cloud drives in the DOW. Overretaining information increases storage costs and attack surface. By identifying sensitive files to delete, costs can be lowered, attack surfaced reduced, and AI can be safely adopted.

### Project Language(s), Software, and Hardware
Most of the implementation was all carried out in Python. For extracting text from documents, Apache Tika was used.

### Project Requirements
The acceptance criteria included that:
1. There must be a policy template that specifies various data classification levels including for example Public, CUI, and PII; retention periods; rules for data disposition such as review, archive, and delete; and responsibilities for different end users.
2. There must be a technical report evaulting at least three distinct open source tools according to their accuracy, ease of use, performance, and community support.
3. The selected scanner must have at least 95% accuracy in detecting whether documents contain PII or not.
4. There must be a prototype that scans 1,000 mixed file type files, logs all files detected as sensitive in a manifest file, and creates an actionable CSV for end users.

### Project Implementation Description & Explanation
For test data, I created a synthetic dataset. This let me test the precision, recall, F1-scores, and binarization accuracy of the various scanners.

[Back to Portfolio](./)