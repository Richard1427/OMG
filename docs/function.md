# function
## Initialize input:
Requirement 1: Users can upload a file in .txt or .xls format

Rationale 1: The program processes data and requires file support to generate sequence representation scatter plots.

Test scenario: Document extraction boxes are added to the initial interface for users to submit documents.

Priority: High

## Default output:
Requirement 2: After processing files, the program automatically generates scatter plots of gene expression, so that users can visualize the analysis and provide scatter correlation coefficients for reference.

Principle 2: Processing inside the program, generating scatter plots in default state and related data.

Test scenario: Default selection of genes to draw scatter plots and describe features.

Priority: High

## Exception handling:
Requirement 3: Users need feedback when uploading invalid, missing or abnormal files.

Rationale 3: Exception handling reduces the extra time of users in order to provide a better user experience.

Test scenario: When users upload invalid, damaged, abnormal files, pop-up window prompt.
Priority: Medium

## Return to the home page:
Requirement 4: When one set of genetic files is analyzed and the user wants to test another set of genetic files, he will jump back to the file upload page in the page.

Rationale 4: When users have multiple sets of genetic test files, they can meet the functional requirements.

Test scenario: Add the option to return to the home page in the return interface.

Priority: Low
