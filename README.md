# Website_blocker
A small program which blocks the site user wants for a specific time duration in the day 

You can change time and add other websites also

for changing time simply in the if condition change the integer values to desired values
For letting the program start on its own put this line in the crontab 


@reboot /path of this file

to enter crontab in linux type

sudo crontab -e

and add the above line in the end save the file and the script will run in background

For LINUX user

set hosts_path to "/etc/hosts"



For Windows user

set hosts_path to r"c:\Windows\System32\Drivers\etc\hosts"


