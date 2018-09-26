# Open source checklist
Before going live with a public repository, the following considerations should be taken. 

- [ ] **Remove all PII**
  - Use [Clouseau](https://github.com/cfpb/clouseau) for scanning source code, pre-commit
  - Visually inspect each image to ensure there is no GSA-specific information
- [ ] **Remove all potential security information**
  - Passwords, keys, IPs, tokens, etc.
- [ ] **Consider proper use of licensing for the code base**
- [ ] **Consider proper use of open source code within the code base**
  - Review code for any legal or contractual issues
- [ ] **Include GSA standard or updated `README.md`**
  - Have installation instructions documented and tried out before posting
  - Make sure to include and test all configuration dependencies
- [ ] **Include GSA standard or updated `CONTRIBUTING.md` file**
- [ ] **Include GSA standard or updated `LICENSE.md`**
- [ ] **Include an updated `codeinventory.yml`**
- [ ] **If desired, include `CHANGELOG.md`**
- [ ] **Use `.gitignore`**
- [ ] **Setup or use a standard development pipeline**
  - Look at GSA's code scanning documentation - [static_code_scan](https://github.com/GSA/open-source-policy/blob/master/OpenSource_code/static_code_scan.md) and [checkmarx_poc](https://github.com/GSA/open-source-policy/blob/master/OpenSource_code/checkmarx_poc.md) docs
  - Contact the CTO's office for support - cto@gsa.gov

*18F [Before You Ship](https://before-you-ship.18f.gov/) and [12 Factor App](https://12factor.net/) are good resources with lots of helpful info on open source SW creation
