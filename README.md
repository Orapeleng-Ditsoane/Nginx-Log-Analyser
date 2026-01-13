# Nginx-Log-Analyser
Simple tool to analyze logs

A shell script that reads the log file and provides the following information:

Top 5 IP addresses with the most requests
Top 5 most requested paths
Top 5 response status codes
Top 5 user agents

How to run the script:
 1. make a file executable.
 2. chmod +x nginx-log-analyser.sh
 3. ./nginx-log-analyser.sh <file name>
