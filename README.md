**Port Scanner**

A simple Python script that scans a specified remote host for open ports within the range of 1 to 1024.

**Features**:

-User-friendly: Provides feedback during the scan to let the user know which host is being scanned.

-Efficient: Set with a 0.5-second timeout for each port to expedite the scanning process.

-Range: Scans ports from 1 to 1024 to cover most common services.

-Error Handling: Gracefully handles common errors like unresolvable hostnames and unreachable hosts. Also, allows users to interrupt the scan using Ctrl+C.


**Prerequisites**

You'll need to have Python installed on your system to run the script. No external libraries are required.

**Usage**

1. Clone this repository to your local machine.
2. Navigate to the directory containing the script.
3. Run the script using the command: 
   python <script_name>.py
4. When prompted, enter the hostname or IP address of the remote server you wish to scan.

**Output**

The script will provide feedback in real-time, indicating which ports are open. Once the scan is completed, it will also indicate the total time taken for the scan.


**Note**

Use this script responsibly. Scanning networks without permission can be illegal in many jurisdictions. Always obtain proper authorization before running any scanning tools.
