# nagios-plugins

Nagios plugins i had to modify.

## Installation

Put the plugin into your nagios plugins directory (/usr/lib/nagios/plugins/ for me)

Add execution permission to the copied plugin

    # chmod +x /usr/lib/nagios/plugins/*my_plugin*

## check_smartmon.py

Source: https://exchange.nagios.org/directory/Plugins/Operating-Systems/Linux/check_smartmon/details

Put a sticky bit on the file

    # chmod u+s check_smartmon.py

