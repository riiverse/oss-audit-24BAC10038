 Open Source Audit Project

Name: Eipshita Basuli

Roll Number: 24BAC10038

Course: Open Source Software (NGMC)

Software Chosen: VLC Media Player

 Project Overview

This project presents a structured audit of VLC Media Player, one of the most widely used open-source multimedia applications.

The report covers:

Origin and development
Licensing model
Linux ecosystem presence
Comparison with proprietary alternatives

Additionally, five shell scripts are created to demonstrate practical Linux and automation skills aligned with open-source principles.

 System Requirements
Ubuntu Linux (or WSL Ubuntu)
Bash Shell
VLC Media Player
Basic Linux utilities: dpkg, grep, awk, du, etc.
 Setup Instructions

Open the terminal and run:

git clone https://github.com/DrishtiTripathi2230/oss-audit-24BCE10039.git
cd oss-audit-24BCE10039
sudo apt update
sudo apt install vlc
vlc --version
 Scripts Included
🔹 Script 1 — System Identity Report

Displays system information such as kernel version, user, uptime, and date.

Concepts Used:

Variables
Command substitution $( )
echo
🔹 Script 2 — FOSS Package Inspector

Checks whether VLC is installed and displays its version and details.

Concepts Used:

if-else
dpkg
grep
case
🔹 Script 3 — Disk and Permission Auditor

Analyzes key directories for disk usage and permissions.

Concepts Used:

for loop
du
ls -ld
awk
🔹 Script 4 — Log File Analyzer

Reads a log file, counts keyword occurrences, and shows recent matches.

Concepts Used:

while loop
grep
Variables
🔹 Script 5 — Open Source Manifesto Generator

Generates a personalized open-source philosophy statement based on user input.

Concepts Used:

read
String handling
File output (>)
date
 How to Run the Scripts
Step 1: Give Execution Permission
chmod +x script1.sh script2.sh script3.sh script4.sh script5.sh
Step 2: Execute Scripts
./script1.sh
./script2.sh
./script3.sh
./script4.sh /var/log/syslog error
./script5.sh
 Project Structure
oss-audit-24BCE10039/
│── README.md
│── script1.sh
│── script2.sh
│── script3.sh
│── script4.sh
│── script5.sh
 Notes
All scripts are tested on Ubuntu (WSL environment).
Scripts run completely via terminal (no GUI required).
Ensure execution permissions are granted before running scripts.
 Conclusion

This project provided both conceptual and practical insights into open-source software. It demonstrates how VLC Media Player reflects the principles of openness, collaboration, and flexibility.

At the same time, it strengthens hands-on experience with Linux commands and shell scripting.
