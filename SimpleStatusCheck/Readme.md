# Description
The intention of this script is to be able to capture the basic status of vservers and services to be used 
for getting a quick overview of the health of services before and after migrations or other maintenace work
where it is important to get before/after status.

It can be used for other purposes as well where the information might be of help.
 
# Prerequisites
Access to CLI and shell on the NetScaler where the script should be run.
 
# How to use
- Copy/paste all lines to CLI after logging in
- Use scp to copy the output files to local drive if required to be stored
- Investigate the content of the generated files to see the results
- All files will be placed in /tmp/status/ directory
