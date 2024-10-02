submitting:
Nadir Elmakias 207422486
Netanel Alis 314938655

in order to lauch the system run the launcher.sh script with the 2 parameters:
- difficulty level
- number of miner containers to run

important notes about the script:
* the script will pull the docker images from dockerhub just make sure you are already logged in 
* in order to run the docker command the script requires sudo to run 
* before running the script use "chmod +x launcher.sh"
* the script will create the mounted directory where the script file is found
  and automaticaly create the configuration file with the required configurations for the system to run
* on any consecutive run of the system the script will remove all pipes from previous runs
  and will update the configuration file accordingly.
  (all tou need to do is run the script with the new difficulty and number of miners to create) 
