# performanceTesting: DarazTestPlan

## Project Overview
### This project involves load testing the Daraz website using Apache JMeter to simulate various user scenarios and assess the website's performance under load. The test plan includes multiple thread groups with varying numbers of users, evaluating the website's behavior with 100-150 virtual users.

# Environment Setup and Project Download
## Environment Setup
Install Java: Ensure Java is installed on your machine. You can download and install Java from Oracle's website.<br>
Download Apache JMeter: Download the latest version of Apache JMeter from the official website and follow the installation instructions.

## Project Download
Clone or download the DarazTestPlan.jmx file from the repository.<br>
Save the file to your local directory (D:\jmeter\ or any preferred location).<br>
Running the Load Test in Command Line<br>
To execute the load test for the Daraz website using the command line.<br>

Open the command prompt (cmd).<br>
Navigate to the directory where JMeter is installed.<br>
Run the following command:<br>
``
jmeter -n -t D:\jmeter\DarazTestPlan.jmx -l D:\jmeter\Results\testResult.csv -e -o D:\jmeter\htmlreport\report1 -Jjmeter.reportgenerator.temp_dir=D:/path/to/valid/temporary/directory
``
Make sure to replace the paths (D:\jmeter\) and temporary directory (D:/path/to/valid/temporary/directory) with your actual file paths and valid temporary directory, respectively.

Project Details
Test Plan File: DarazTestPlan.jmx
Test Scenarios: Various thread groups simulate user loads ranging from 100 to 150 virtual users.
Test Result Output: Results are saved in testResult.csv.
HTML Report: Generated in the htmlreport directory.
Running the Load Test
Open the command prompt.
Navigate to the JMeter installation directory.
Run the command provided in the "Running the Load Test in Command Line" section, replacing file paths and directories as needed.
Note
Ensure the specified temporary directory for the report generation has appropriate permissions.
Adjust the thread groups or configurations in the JMX file as necessary for more extensive testing.
For detailed analysis, refer to the generated HTML report (htmlreport directory).
Feel free to reach out for any questions or additional support.

