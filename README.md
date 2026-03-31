oss-audit-24BCG10040

Student Name: Syed Saad Haider 
Registration Number: 24BCG10040 
Course: Open Source Software (NGMC) 


Software Audited: LibreOffice 

Project Overview
This repository contains the technical components of the Open Source Audit Capstone Project. It includes a suite of Bash scripts designed to audit a Linux system and analyze the installation and environment of LibreOffice .

Scripts Description
The following five scripts were developed to demonstrate practical Linux skills and automation :


script1_system_info.sh (System Identity Report): Collects and displays essential system metadata including kernel version, current user, uptime, and distribution details.


script2_package_checker.sh (FOSS Package Inspector): Verifies if LibreOffice is installed using the system package manager and retrieves its version and metadata.


script3_disk_audit.sh (Disk and Permission Auditor): Performs a high-level audit of directory sizes and filesystem permissions for critical system paths and the LibreOffice installation directory.


script4_log_analyzer.sh (Log File Analyzer): Scans system logs for specific keywords (such as "error") to count occurrences and summarize recent activity.


script5_manifest_generator.sh (OSS Manifesto Generator): An interactive script that captures user input to generate a personalized open-source philosophy statement.

How to Run:

Clone the repo - git clone https://github.com/d7rev/oss-audit-24BCG10040.git
cd oss-audit-24BCG10040

Make the scripts executable: chmod +x *.sh

Run individual scripts:
./script1_system_info.sh
./script2_package_checker.sh
./script3_disk_audit.sh
./script4_log_analyzer.sh /var/log/syslog  # Provide a valid log file path
./script5_manifest_generator.sh
