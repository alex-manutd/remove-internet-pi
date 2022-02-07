# remove-internet-pi
Instructions to remove internet-pi from Raspberry Pi running Docker.

Basically uninstall Docker, then delete all the directories created by this project: rm -rf internet-monitoring pi-hole shelly-plug-prometheus starlink-exporter in the Pi home directory. Everything is run as a Docker container, so it should be well-insulated from the rest of the system.
