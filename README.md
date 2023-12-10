# Ubuntu-Commands

Ctrl + Alt + T  							-> To open terminal.
man echo									-> To know more about Linux Commands.
. 											-> Current Directory.
.. 											-> Previous Directory.
cd 											-> To go directly to Home from anywhere.
cd~											-> To go directly to Home from anywhere.
cd .. 										-> To come out from the present directory.
cd DirectoryName 							-> To get inside directory.
cd ../DirectoryName 	  					-> To go directly from one direc to another direct.

ls 											-> List out all items excluding hidden files.
ls -a 										-> List out all items including hidden files
ls -l 										-> List out all items with more details.
ls -R	                                    -> List out all items and also sub-direc items.
ls -r 										-> List out all items in reverse order.
ls -t 										-> List out all items in recent modification.
ls -ltrh 									-> (Combining all above ls commands)

mkdir DirectoryName 						-> To create Directory.
mkdir DirecName/Sub-DirecName 				-> To create Sub-Direc.

cp Source-Path Destination-Path 			-> To copy items from one direc to another direc

pwd 										-> To chack current directory path.
xdg-open . 									-> To open current directory as GUI Mode.
xdg-open /usr/bin 							-> To open specified direc as GUI Mode.

which FileName 								-> To check path of specific item.

cat FileName.txt 							-> To read data from the file.
cat > FileName	                            -> To create new file and write content.
	content..
	content..
echo "content" > FileName					-> To override the content.
echo $PATH 									-> To display Path Environmental variable.

chmod +x FileName 							-> To provide permissions for executable files.

curl ifconfig.me -s 						-> To check IP Address.
hostname -I 								-> To check IP Address.

sudo netstat -tulpn | grep LISTEN 			-> List out all open network ports.
sudo kill -9 PortNumber 					-> To forcefully kill or terminate particular port.
sudo kill -9 $(sudo lsof -t -i:PortNumber) 	-> To forcefully kill or terminate particular port.

sudo apt update 							-> To update the Local Packages database.(New syntex after Ubuntu 16.04).
sudo apt update -y						    -> To update the Local Packages database.(Assumes "Yes" for any prompts).

sudo apt-get update 						-> To update the Local Packages database.(old syntex before Ubuntu 16.04).
sudo apt-get update -y  					-> To update the Local Packages database.(Assumes "Yes" for any prompts).

sudo apt upgrade 							-> To upgrade the installed packages to latest versions.(New syntex after Ubuntu 16.04).
sudo apt upgrade -y 						-> To upgrade the installed packages to latest versions.(Assumes "Yes" for any prompts).
sudo apt-get upgrade 						-> To upgrade the installed packages to latest versions.(old syntex before Ubuntu 16.04).
sudo apt-get upgrade -y 					-> To upgrade the installed packages to latest versions.(Assumes "Yes" for any prompts).

sudo apt-get install lshw       			-> Install "lshw" to see Hardware Information.
sudo lshw 									-> List out Hardware Components and details.
lscpu 										-> List out CPU details, architecture, cores, threads and more.
nproc 										-> To check number of CPU cores.
free -h 									-> To check System Memory Usage.

sudo apt install htop 						-> Install "htop" to see Memory usage and System matrics.
htop 										-> To see the Memory usage and System matrics in Visually.