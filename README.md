g="\033[1;32m"
r="\033[1;31m"
b="\033[1;34m"
w="\033[0m"
o="\033[1;33m"
y="\e[0;33m"

RED="$(printf '\033[31m')"  GREEN="$(printf '\033[32m')"  ORANGE="$(printf '\033[33m')"  BLUE="$(printf '\033[34m')"
MAGENTA="$(printf '\033[35m')"  CYAN="$(printf '\033[36m')"  WHITE="$(printf '\033[37m')" BLACK="$(printf '\033[30m')"
REDBG="$(printf '\033[41m')"  GREENBG="$(printf '\033[42m')"  ORANGEBG="$(printf '\033[43m')"  BLUEBG="$(printf '\033[44m')"
MAGENTABG="$(printf '\033[45m')"  CYANBG="$(printf '\033[46m')"  WHITEBG="$(printf '\033[47m')" BLACKBG="$(printf '\033[40m')"
DEFAULT_FG="$(printf '\033[39m')"  DEFAULT_BG="$(printf '\033[49m')"  

clear
echo -e "$y  ____ ___            .___                       "
echo -e "$y |    |   \______   __| _/____ _/  |_  ____      "
echo -e "$y |    |   /\____ \ / __ |\__  \\   __\/ __ \     "
echo -e "$y |    |  / |  |_> > /_/ | / __ \|  | \  ___/     "
echo -e "$y |______/  |   __/\____ |(____  /__|  \___  >    "
echo -e "$y           |__|        \/     \/          \/     "
echo ""
echo -e "$y [>] Tool Name : AllHackingTools"
echo -e "$y [>] Developer : Misha Korzhik"
echo ""
echo -e $w"["$o"SYSTEM"$w"]"$w" I don't close Termux App And CNTR + C."$w
echo -e $w"["$o"SYSTEM"$w"]"$w" Press enter. To update AllHackingTools"$w
read a1
cd
cd
rm -rf AutoUpdateMyTools
git clone https://github.com/mishakorzik/AutoUpdateMyTools
cd AutoUpdateMyTools
bash AllHackingToolupdate.sh
