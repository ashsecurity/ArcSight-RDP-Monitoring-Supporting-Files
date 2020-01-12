# ArcSight-RDP-Monitoring-Supporting-Files

Files required to setup RDP monitoring in ArcSight

`winc/microsoft_windows_terminalservices_localsessionmanager_operational/`folder contains microsoft_windows_terminalservices_localsessionmanager.userdata.jsonparser.properties file, that is the parser for the RDP connections events. It should be placed into the `$ARCSIGHT_HOME\user\agent\fcp\` folder. 


`microsoft` folder contains terminalservices_localsessionmanager.csv file, which is the categorizer for the events. This folder and file should be placed in `$ARCSIGHT_HOME\user\agent\acp\categorizer\current\` folder. 

>$ARCSIGHT_HOME is the name of the folder where connector is installed including *current* folder.
