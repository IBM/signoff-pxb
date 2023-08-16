# signoff-pxb
Repos for pxb related release sign-off

Each PX-Backup release need to follow this sign-off process and share all artifacts before releasing to production.
PX team need to share the compatibility metrics as well for release. 


## Following are the tests scope for PX-Backup

- Installation tests
- Torpedo tests
- Functional tests
- Market place tests
- Integration tests

### [Owner PX team] Tests that must be executed in the staging environment and performed with every release of px-backup:

- Installation tests
- Torpedo tests
- Functional tests


### [Owner PX team] Tests that must be executed in the production environment and performed after every release of px-backup

- Market place tests


### [Owner IBM/PX team] Tests that must be executed in the staging environment and performed with every release of px-backup:

- Integration tests, related with IBM Services dependencies - Frequency: Any changes in VPC CSI Drivers, PX-Backup release and BOM update
- Integration tests, related with PX Services(PXE) dependency - Frequency: Any changes in PXE
  

#### Integration tests
- Taking backup/restoring of application which is using VPC Block CSI driver related storage - Frequency: run weekly(default IKS, ROKS, Satellite version)

- Installation tests compatibility with IKS/ROKS/Satellite - Frequency: - run weekly( all supported versions - not on same day, 1 region per iteration)

- Taking backup/restoring of application which is using PXE related storage - PX-Team -  Frequency - weekly
