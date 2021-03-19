# mm-ipam

CSV files that defines the skeleton for various parts of our IPAM set up. More information on how to import https://docs.menandmice.com/display/MM920/Import+IPAM+data

### data-center-site.txt
The CSV file describes the hierarchy for IP addressing for a typical data center 

#### How to use it
- Replace <SITE> with three letter a abbreviation of the location (LVS, POR, etc)
- Replace <LOCATION> with the <SITE> followed by facility and city/state (e.i. IAD - Equinix Ashburn VA)
- Replace <ACTION> with the appropiate action: create for new resources, update for existings one
