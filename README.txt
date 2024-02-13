This set of code takes raw btmp file and analyze and detects the malicious IP addresses.

File 01_ takes raw data from linux server and saves as a structured data using regex 
File 02_ Connects WHOISIP website using API and retreaves data and merge it with the previous data
File 03_ Analyze the geolocation data
File 04_ Analyze the data from time perspective
File 05_ Connects AbuseIPDB website and takes the information if IP is reported malicious in last 90 days
File 06_ Visualize the data pattern and make it easier for labelling the data
File 07_ A ML model that detects the malicious IPs