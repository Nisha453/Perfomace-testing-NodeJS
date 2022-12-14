# Perfomace-testing-NodeJS

## Prerequisite 
### Java
```
sudo apt install default-jre
sudo apt install default-jdk
```
### Jmeter
Please download the Jmeter from the following link: https://jmeter.apache.org/ and install it on the VM instance

### System used for the testing
Please clone the following Repository and deploy it on the VM instance.
```
git clone https://github.com/bbachi/nodejs-restapi-mongo.git
```

### Cloud Service used for deployment
Cybera cloud service is used for deployment of the system and Jmeter. 
Link: https://cloud.cybera.ca/auth/login/?next=/

### Run Test Cases
Get the test cases from the Testing folder. open the terminal on the Jmeter bin folder and run the following command
```
jmeter.sh -n -t test-case-path -l output-file-path -e -o output-folder-path
```

### Utilization data
SAR tool is used to record the data for utilization. Run this command to measure utilization
```
sar -[ options ] time_interval number_of_tines_to_display
```

### Results
- The result data can be found in the output file mentioned above
- You can use data visulization tool to make a visual representation of the data.


