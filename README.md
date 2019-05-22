# Host-Based-Assessment-Infrastructure-Assessment
Host-Based Assessment is a process to audit an Infrastrure. Infrastructure has multiple resources like operating systems (Linux, Windows), databases, firewalls, servers etc. If we are unable to audit these targets through the professional tools like Nessus and Qualys then in this scenario we prepare HBA script.

Usage:
1. Run the script with admin/root privileges.
2. Need to change file permission to make it executable - chmod a+x filename.sh
3. After execution of script you will get a zip file as a output in same directory from script will be executed.
4. Compare the result with CIS benchmark guidelines. Example - https://security.uri.edu/files/CIS_Red_Hat_Enterprise_Linux_7_Benchmark_v1.1.0.pdf

Note: Execute it on your own risk. No changes will be made after execution. Script is made only to fetch required information.
