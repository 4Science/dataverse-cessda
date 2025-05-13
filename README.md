## SuperDaDa Script for Dataverse 6

This repository is a fork of gdcc/dataverse-cessda, containing the SuperDaDa script for ensuring Dataverse DDI push compliance with CESSDA specifications.

### Changes from the Original Repository

- **Dataverse 5 Versions**: The versions for Dataverse 5 have been retained.
- **New Addition**: Added `SUPER_DADA_DV_6_v1_0/SUPER_DADA_DV_6_v1_0_script.sh`, a revised script compatible with Dataverse 6.

### Usage Instructions

- **Path Adjustments**: Minor path adjustments may be necessary to fit the specific instance where the script will be executed.
- **Execution**: Run the script once initially, then set it up to run via a cron job.

### Important Note

- The script overwrites the Dataverse DDI output.
