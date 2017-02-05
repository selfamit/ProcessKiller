# ProcessKiller
Script to kill Linux running process using process name

If a long running process is not responding, instead of finding the process id and then issuing kill command.
Use kill.py script by supplying process name.

Here i have two instance of vlc running but not responding, it will terminate both the vlc.

e.g. kill.py vlc
[sudo] password for aks: 
Found proces :  8168 ?        00:00:00 vlc
 8206 ?        00:00:00 vlc
found ['8168', '00', '00', '00', '8206', '00', '00', '00']
Going to kill process having pid: 8168
Status:0
Going to kill process having pid: 8206
Status:0
