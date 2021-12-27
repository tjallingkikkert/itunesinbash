# itunesinbash
control Apple Music / iTunes from the terminal

controls:\n
l to set "loved" to true\n
n/N for next/previous song
s to toggle shuffle on/off
p to toggle pause/play
q to quit
+/- for Music volume
r to start current song from the start

change "Music" to "iTunes" in the script to make it work with itunes
create scripts directory in your home folder:

mkdir ~/scripts

put this script (scan) in this folder
make it executable
cd ~/scripts
chmod 700 scan

add scripts directory to your path to run from anywhere
export PATH="$HOME/scripts:$PATH"
run with scan & enjoy
