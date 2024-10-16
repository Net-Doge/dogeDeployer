This product was developed by net.doge

The files included are examples of what needs to be in the folder,
Run the file dogeDeployer.bat as Administrator or it will not function well if you're trying to install sysmon

This product is designed to make a deployment script for your splunk environment and optionally install sysmon as well

The script produces a file called deploymentScriptbyDoge.bat which will be configured by the dogeDeployer.bat script

Follow the prompts on screen on the script!


Files in the same directory should be:
- splunkuniversalinstaller.msi (MUST BE THIS NAME)
- Sysmon.exe (FROM SYSINTERNALS)
- sysmonconfig.xml (OPTIONAL)
- inputs.conf (Optional)

IF inputs.conf IS NOT COPIED TO %SPLUNKHOME%/etc/system/local THEN YOU DIDN'T RUN AS ADMINISTRATOR. 
