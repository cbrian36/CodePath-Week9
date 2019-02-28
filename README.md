# CodePath-Week9


## Honeypots Deployed
  1. Ubuntu - Dionaea with HTTP
  2. Ubuntu - Snort
  3. Ubuntu - Glastopf
  4. Ubuntu - Suricata
  5. Ubuntu - Cowrie
	
## Issues Encountered
The Deploy (wget) Command for installing a honeypot into a VM and wiring it back to the admin server did not work.
The issue is that the external IP address of the admin server is listed two too many times in the command. For
example, this is the Deploy Command the MHN admin console provided me for the Dionaea with HTTP honeypot
```
wget "http://35.202.59.12, 35.202.59.12/api/script/?text=true&script_id=2" -O deploy.sh && sudo bash deploy.sh http://35.202.59.12, 35.202.59.12 MDGRuS3R
```

However, this is the correct Deploy Command
```
wget "http://35.202.59.12/api/script/?text=true&script_id=2" -O deploy.sh && sudo bash deploy.sh http://35.202.59.12 MDGRuS3R
```
	

	
A summary of the data collected: number of attacks, number of malware samples, etc.
## Attack Summary
### Number of Attacks: X
### Numer of Malware Samples: X

### Top 5 Attacker IPs:
  1. 
  2. 
  3. 
  4. 
  5. 

### Top 5 Attacked Ports:
  1. 
  2. 
  3. 
  4. 
  5. 

### Top 5 Honey Pots:
  1. 
  2. 
  3. 
  4. 
  5. 
  
### Top 5 Sensors:
  1. 
  2. 
  3. 
  4. 
  5. 
  
### Top 5 Attacks Signatures:
  1. 
  2. 
  3. 
  4. 
  5. 
	
## Unresolved Questions
	None at this time
	
## JSON Export
