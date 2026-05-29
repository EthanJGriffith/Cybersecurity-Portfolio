#Overview
   Learn how to use tools to analyze potentially malicous documents

#Tools Used
- oledump.py
- Cyberchef

  
 #Walkthrough
  - Task 3 (File Analysis)
    - Analyse the potentially malicous file agenttesla.xlsm
    - Output gave Macro on data stream 4 
    - Ran oledump.py -s 4 on agenttesla.xlsm for data steam 4
    - Ran previous command with --vbadecompress
    - Public Ip 193.203.203.67 of Sqtnew and a an executable inside
    - Taking the Sqtnew value to cyberchef
    - Output revealed powershell script hidden inside of the file with -executionpolicy, Invoke-WebRequest Web requests for downloading files from the URL http://193.203.203.67, the file will be saved as well Start-Process shows that the exe will be executed upon opening the xlsm file. 
    - Analyze potentially malicous file possible_malicous.docx a
    - Output gave 16 data streams with stream 8 having macro code
   
   - Task 4 Fake Net
    - 

