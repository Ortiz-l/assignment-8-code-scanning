# Answers to Assignment 8 Part 3

Add your answers to the questions in Assignment 8 Part 3, Step 2 below. 

## Vulernability Remediation:
### Vulnerability 1: CVE-2019-20477
1. Which package or library are you addressing?
The package we are addressing is pypi/pyyaml@5.1 versions 5.1 or above and under 5.2.

2. Which CVE is linked to this vulnerability?
The CVE number CVE-2019-20477 is linked to this vulnerability.

3. What remediation steps do you suggest?
The remediation steps for this vulnerability are updating the version of PyYaml to 5.2 or higher if possible or updating software containing the PyYaml package to verisons that use a version of pyyaml that is 5.2 or greater. To help reduce risk related to this vulnerability, common cybersecurity best practices steps can be taken, such as: proper network segmentation, least priveledges permissions, and zero trust security measures. Finally, as CVE-2019-20477 is linked to CWE-502, mitigating this weakness can also help address this vulnerabilities impact. Some strategies are using signing/sealing features of the programming language to ensure deserialized data has not been tainted, populating new data from the deserialized data, and explicitly defining final objects to prevent deserialization.

### Vulnerability 2: CVE-2020-1747
1. Which vulnerability are you addressing?
The vulnerability being addressed is a PyYAML vulnerability in versions below version 5.3.1. 

2. Which CVE is linked to this vulnerability?
The CVE number linked to this vulnerability is CVE-2020-1747.

3. What remediation steps do you suggest? 
For remediation, the first suggested step is to update the PyYAML package being used to version 5.3.1 or greater. Enforcing common cybersecurity best practices are also a good step to mitigate potential affects from this vulnerability, if the patch cannot be performed. Additionally, this vulnerability is attached to the weakness CWE-20, improper input validation, and some mitigation steps for this underlying weakness are performing input validation and reducing the attack surface to reduce what untrusted inputs can allow a user access to.