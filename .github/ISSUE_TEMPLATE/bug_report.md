---
name: Bug report
about: Create a report to help us improve
title: 'Incorrect sample network-quorum.yaml file'
labels: bug
assignees: 'BAF Team'

---

**Describe the bug**
The sample network-quorum.yaml file contains both quorum and corda values as external_url_suffix in multiple places. For ex- In warehouse organization below value is present:-
external_url_suffix: test.corda.blockchaincloudpoc.com 

**To Reproduce**
Steps to reproduce the behavior:
1. Go to "blockchain-automation-framework/platforms/quorum/configuration/samples/network-quorum.yaml
2. Click on network-quorum.yaml
3. Scroll down to line no.122 i.e organization name: manufacturer, line no. 176 i.e organization name: store and line no. 230 i.e organization name: warehouse.
4. See error - external_url_suffix: test.corda.blockchaincloudpoc.com 

**Expected behavior**
It should have below value:-
external_url_suffix: test.quorum.blockchaincloudpoc.com  

**Screenshots**
Not Applicable

**Environment (please complete the following information):**
 - OS: [e.g. Windows]
 - Version [e.g. 10]

**Additional context**
Add any other context about the problem here.
