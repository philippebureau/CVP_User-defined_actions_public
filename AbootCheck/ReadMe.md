You can use this script to check Aboot version for Field Notice 0044

https://www.arista.com/en/support/advisories-notices/fieldnotices/8756-field-notice-44

The script by default will log an entry in CVP Change Control that state if the device needs to be patched or not

AND will create a file (/tmp/AbootCheck.txt) with the same entries for all switches.  The file name and location can be changed by editing the YAML file argument "outfile"

You can use comment (#) in the script to prevent file creation if it is not needed

NOTE : if CVP is in cluster, the file will be created where scriptaction is running.  You can find wich node is running the service with command "cvpi status scriptaction"
