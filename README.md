# Ubuntu Terminal Commands :-

## Table of Contents
- [Basic Ubuntu Commands.](#Basic-Ubuntu-Commands)
- [File System Commands.](#File-System-Commands)
- [File and Directory Listing.](#File-and-Directory-Listing)
- [File and Directory Management Commands.](#File-and-Directory-Management-Commands)
- [File Copying Commands.](#File-Copying-Commands)
- [Print Working Directory.](#Print-Working-Directory)
- [Default Application Opening Commands.](#Default-Application-Opening-Commands)
- [Executable Location Commands.](#Executable-Location-Commands)
- [File Content Display and Manipulation Commands.](#File-Content-Display-and-Manipulation-Commands)
- [File Access Permission Commands.](#File-Access-Permission-Commands)
- [Network Information Commands.](#Network-Information-Commands)
- [Process and Port Management Commands.](#Process-and-Port-Management-Commands)
- [Software Package Update and Upgrade Commands.](#Software-Package-Update-and-Upgrade-Commands)
- [System Resource Commands.](#System-Resource-Commands)
  - [To check Hardware Components and details.](*43.-To-List-out-Hardware-Components-and-details)
  - [To check CPU details, architecture, cores, threads and more.](*44.-To-List-out-CPU-details,-architecture,-cores,-threads-and-more)
  - [To check number of CPU cores.](*45.-To-check-number-of-CPU-cores)
  - [To check System Memory Usage.](*46.-To-check-System-Memory-Usage)
  - [To see the Memory usage and System matrics in Visually.](*48.-To-see-the-Memory-usage-and-System-matrics-in-Visually)
- [MongoDB Commands.](#MongoDB-Commands)
- [About Me](#Hi,-I'm-Manu-KM!-👋)

## Basic Ubuntu Commands.
***1. To open terminal in Ubuntu.***
```
Ctrl + Alt + T
```
***2. To know more about Linux Commands.***
```
man echo
```
## File System Commands.
***3. Current Directory.***
```
.
```
***4. Previous Directory.***
```
..
```
***5. To go directly to Home from anywhere.***
```
cd
```
or
```
cd~
```
***6. To come out from the Current directory.***
```
cd ..
```
***7. To get inside directory.***
```
cd DirectoryName
```
***8. To go directly from one directory to another directory.***
```
cd DirectoryName
```
***9. To go directly from one directory to another directory.***
```
cd DirectoryName
```
## File and Directory Listing.
***10. To List out all items excluding hidden files.***
```
ls
```
***11. To List out all items including hidden files.***
```
ls -a 
```	
***12. To List out all items with more details.***
```
ls -l
```	
***13. To List out all items along with Sub-Directory items.***
```
ls -R
```	
***14. To List out all items in reverse order.***
```
ls -r
```	
***15. To List out all items in recent modification.***
```
ls -t
```	
***16. Combining all above "ls" commands.***
```
ls -ltrh 
```	
## File and Directory Management Commands.
***17. To create Directory.***
```
mkdir DirectoryName
```	
***18. To create Sub-Direc.***
```
mkdir DirecName/Sub-DirecName
```	
## File Copying Commands.
***19. To copy items from one directory to another directory.***
```
cp Source-Path Destination-Path
```	
## Print Working Directory.
***20. To check current directory Path.***
```
pwd
```
## Default Application Opening Commands.
***21. To open current directory as GUI Mode.***
```
xdg-open .
```
***22. To open specified directory as GUI Mode.***
```
xdg-open /usr/bin
```
## Executable Location Commands.
***23. To check path of specific item.***
```
which FileName
```
## File Content Display and Manipulation Commands.
***24. To read data from the file.***
```
cat FileName.txt
```
***25. To create new file and write content.***
```
cat > FileName
	content..
	content..
```
***26. To override the content.***
```
echo "content" > FileName
```
***27. To display Path Environmental Variable.***
```
echo $PATH
```
## File Access Permission Commands.
***28. To provide permissions for executable files.***
```
chmod +x FileName 
```
## Network Information Commands.
***29. To check IP Address***
```
curl ifconfig.me -s
```
***30. To check IP Address***
```
hostname -I
```
## Process and Port Management Commands.
***31. To List out all open network ports which are used by system.***
```
sudo netstat -tulpn | grep LISTEN
```
***32. To forcefully kill or terminate particular port.***
```
sudo kill -9 PortNumber
```
***33. To forcefully kill or terminate particular port.***
```
sudo kill -9 $(sudo lsof -t -i:PortNumbe)
```
## Software Package Update and Upgrade Commands.
***34. To update the Local Packages database.(New syntex, from Ubuntu 16.04 and higher versions).***
```
sudo apt update
```
***35. To update the Local Packages database.(New syntex, from Ubuntu 16.04 and higher versions and Assumes "Yes" for any prompts.***
```
sudo apt update -y
```
***36. To update the Local Packages database.(old syntex upto Ubuntu 16.04 and lower versions).***
```
sudo apt-get update
```
***37. To update the Local Packages database.(old syntex upto Ubuntu 16.04 and lower versions and Assumes "Yes" for any prompts***
```
sudo apt-get update -y
```
***38. To upgrade the installed packages to latest versions.(New syntex, from Ubuntu 16.04 and higher versions).***
```
sudo apt upgrade
```
***39. To upgrade the installed packages to latest versions.(New syntex, from Ubuntu 16.04 and higher versions and Assumes "Yes" for any prompts).***
```
sudo apt upgrade -y
```
***40. To upgrade the installed packages to latest versions.(old syntex upto Ubuntu 16.04 and lower versions).***
```
sudo apt-get upgrade
```
***41. To upgrade the installed packages to latest versions.(old syntex upto Ubuntu 16.04 and lower versions and Assumes "Yes" for any prompts).***
```
sudo apt-get upgrade -y
```
## System Resource Commands.
***42. Install "lshw" to see Hardware Information.***
```
sudo apt-get install lshw
```
***43. To List out Hardware Components and details.***
```
sudo lshw
```
***44. To List out CPU details, architecture, cores, threads and more.***
```
lscpu
```
***45. To check number of CPU cores.***
```
nproc
```
***46. To check System Memory Usage.***
```
free -h
```
***47. Install "htop" to see Memory usage and System matrics.***
```
sudo apt install htop
```
***48. To see the Memory usage and System matrics in Visually.***
```
htop
```
## MongoDB Commands.
***49. To check the status of the MongoDB service.***
```
sudo systemctl status mongod
```
***50. To manually start the MongoDB service.***
```
sudo systemctl start mongod
```
***51. To manually stop the MongoDB service.***
```
sudo systemctl stop mongod
```
***52. To connect to a MongoDB server and initiate a connection to a replica set with the specified name "rs0".***
```
sudo mongod --replSet rs0
```



# Hi, I'm Manu KM! 👋
### 🚀 About Me
I'm a full stack Java developer... 
### 🛠 Skills
Java | SQL | HTML | CSS | JavaScript | React JS | JDBC | Servlets| JSP | Hibernate | Spring MVC | Spring Boot | Rest API | Mongo DB | J Meter | Android Development | Kotlin |
### 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://manukm2.github.io/Manu-KM-Portfolio/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manu-km-7ba832168/)
### Feedback
If you have any feedback, please reach out to me at manukm969@gmail.com
