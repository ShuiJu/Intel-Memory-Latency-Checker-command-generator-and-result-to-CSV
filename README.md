# Intel Memory Latency Checker command generator and result convert to CSV
These tools are used for quickly generate or run 
./mlc --idle_latency -c0 -L -b1m
A script is also here for a better experience using MLC.

Step 1:
Download MLC from Intel
 [Intel Memory Latency Checker](https://www.intel.com/content/www/us/en/developer/articles/tool/intelr-memory-latency-checker.html).

## IF you want to generate command yourself:

Step 2:
Use command generator.
mlc latency.html

Step 3:
Open Powershell in folder that contains mlc.exe, paste the command to run.
If you want to test different core, paste it into something with a findn`replace such as Notepad, replace -c0 to -c1 or -c8. The count of cores starts with 0.

Step 4:
Copy everything in your powershell windows, open mlc latency to csv.html, paste and convert all of the results into a CSV file

## IF you want to be lazy: (recommanded)
Step 2:
Put that bat file into the folder that contains mlc.exe, then run it.
If you want to test different core, edit it in something with a findn`replace such as Notepad, replace -c0 to -c1 or -c8. The count of cores starts with 0.

Step 3:
Find the file after the bat finished at the same folder with mlc.exe in it. Copy paste the text into mlc latency to csv.html to get csv file.
