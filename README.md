# Remote-Repository
//YMAL\\
YAML is AINT markup language.
**#YAML Hirarchy**
Stages:
- Stage: Build
  Jobs:
  - Job: BuildPackage
    Steps:
    - Build
    - Package
    - Publish
- Stage: Deploy
  Job:
  - Job: StartDeployment
    Steps:
    - Delpoypackage
**# Stage** - Satge is collectiin of Jobs
-Stage:
  Jobs:
  - Job: BuildonWindows
    Steps:
    - Build
  - Job: BuildonMAC
    Steps:
    - Build
**# Job** - Job is collection of steps that runs on agent/envoronment
jobs:
- Job: Buildpackage
  Steps:
  - Build
  - Package
  - Publish
**#Steps** - Steps helps to define the set of process to set up your an activity/task which you want to perform on any specific job.
Steps:
- Build
- Package
- Publish

     
