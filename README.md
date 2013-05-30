UTILITIES
============================================

This is a collection of scripts in different languages which I use to
perform not better specified tasks

battery_notify.sh
-----------------
This is simply a script that checks the battery status and send a desktop notification when the battery is discharging and the percentage is below 14%.
Requires **notify-send**, you may find it in the package notify-osd on debian.

You may run it with a crontab or rather with conky!

for example in conkyrc:

  ${execi 180 ~/utilities/battery_notify.sh}


