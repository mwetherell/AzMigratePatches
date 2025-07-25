# AzMigratePatches
Author: Dinesh Reddy Gottam (PG member of the Azure Migrate team)
# prereqs
these DLLs have only been tested on discovery appliance version: v25.24.02.07
# disclaimer
these DLLs are experimental. Use at your own risk.
# Instructions:
!---note this is NOT for the target migration appliance that runs on your AzL cluster---!

1. log into your azure migrate - DISCOVERY - appliance

2. browse to: C:\Program Files\Microsoft Azure Gateway Service

3. stop the asrgwy service: Stop-Service asrgwy

4. copy (overwrite) the DLLs 

5. start the asrgwy service:  Stop-Service asrgwy

that's it. if necessary do your housekeeping and restart your migrations jobs
