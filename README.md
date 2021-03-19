# MM-IPAM

CSV files that defines the skeleton for various parts of our IPAM set up. More information on how to import on [M&M: Import IPAM Data](https://docs.menandmice.com/display/MM920/Import+IPAM+data).

## File Description

### data-center-site.txt
The CSV file describes the hierarchy for IP addressing for a typical data center location.

#### How to use it
- Replace ```SITE``` with three letter a abbreviation of the location (LVS, POR, etc)
- Replace ```LOCATION``` with the ```SITE``` followed by facility and city/state (e.i. IAD - Equinix Ashburn VA)
- Replace ```ACTION``` with the correct action: ```create``` for new resources, ```update``` for existings one
