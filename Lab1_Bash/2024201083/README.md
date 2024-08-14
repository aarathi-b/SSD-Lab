SSD Lab 1: Bash scripting

1) Bash script to extract all lines from access.log where the request method is POST
and the HTTP status code is 404
grep is used to filter from the file lines with 'POST'. It is piped to another grep to filter 404.

2) Bash script to calculate the total power level of all the seniors in
power_levels.txt
Using awk to find sum of column 4 and printing it at the end of records.

How to run the program
Go to the folder 2024201083
./2024201083_q1.sh will give output for first question
./2024201083_q2.sh will give output for second question
