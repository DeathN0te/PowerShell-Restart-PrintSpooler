# PowerShell-Restart-PrintSpooler
This script will create a log of services that are running with custom headers for each piece of information. It then exports that data to two different file formats (JSON,HTML). 
It also checks the Print Spooler to see if any files are stuck in queue for more than "X" amount of time. If it meets the criteria, it automatically restarts the print spooler. 
