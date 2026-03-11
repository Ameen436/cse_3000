# Repository Security Assessment

### Intended Users
The intended users of this repository are primarily my CSE-3000 course instructor and TAs for grading purposes, as well as myself.

### Risk Assessment
If the code or data in this repo fell into the wrong hands, the primary risk would be academic integrity issues (others copying my work) or the exposure of my personal coding style and project structure. Since this repo does not contain sensitive API keys or private user data, the technical risk to third parties is minimal. However, unauthorized access could lead to "code poisoning" or malicious commits if the repo were used in a larger production environment.

### Security Steps Taken
To secure this repository, I have implemented the following:
* **Branch Protection:** I have enabled rulesets that require a pull request and a review before merging into the main branch.
* **CODEOWNERS:** I've added a CODEOWNERS file to ensure that I am notified and required to sign off on any changes to critical files.
* **Secret Scanning:** I have ensured that no sensitive credentials (like passwords or tokens) are hardcoded in the scripts.
* **Access Control:** Access is limited to authorized GitHub users only, and I regularly review the collaborator list.
