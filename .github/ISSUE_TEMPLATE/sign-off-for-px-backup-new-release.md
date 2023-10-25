---
name: Sign-Off for PX-Backup new release
about: Use this template to upload all required artefacts for sign-off process
title: ''
labels: sign-off
assignees: ''

---

---

**PXB Sign-off-Template**
Following are the tasks which has to be completed by following teams

**NOTE:** This issue should not be closed until PX-Backup build/version pushed to IBM Cloud Catalog 

**Sign-off process Step 1:**

**Portworx Team:**

- [ ] Planned PX-Backup Release Version:
- [ ] Lists of Tests executed:
- [ ] Screenshots/Summary of Test Execution:
- [ ] IKS/ROKS Support Matrix for new version:
- [ ] Steps for existing users to migrate to new versions:
- [ ] Bug fixes V/S TestCase mapping:
- [ ] Please attach logs from both the PX-Backup and stork(source and destination cluster) components that were used during the execution of the tests described above:


**IBM Team:**

- [ ] Planned PX-Backup Release Version:
- [ ] Provide information about the IKS cluster(including BOM version) where integration tests were conducted:
- [ ] Provide information about the ROKS cluster(including BOM version) where integration tests were conducted:
- [ ] Torpedo Test Result's Details from IKS Cluster:
- [ ] Torpedo Test Result's Details from ROKS Cluster:
- [ ] IBM Team need to verify tasks and sign-off PX_Backup build



**Sign-off process Step 2:**

**NOTE: Once above tasks completed and marked as done including sign-off then PX-Backup and IBM Team need to complete following tasks as well**

**PX-Backup Team:**
- [ ] Push sign-off PX-Backup build to IBM Cloud Catalog in one region i.e us-east or so
- [ ] Verify torpedo tests(via automation) on default IKS and ROKS version - In case of test failure build has to be rollback and discussed with IBM Team.
- [ ] Push sign-off PX-Backup build to all IBM Cloud Catalog regions.

**IBM Team:**
- [ ] Run PX-Backup automated tests on one region for IKS and ROKS default version
- [ ] In case of tests failure discuss with PX-Backup team and take action accordingly
- [ ] Close this issue in case of success test result.
