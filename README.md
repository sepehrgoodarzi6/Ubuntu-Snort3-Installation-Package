# Ubuntu-Snort3-Installation-Package
---------------------------------------------------------------------------------------
Gathered by, Sepehr Goodarzi
Computer Engineering Student at A.Borujerdi University
Email: sepehrgoodarzi6@gmail.com
---------------------------------------------------------------------------------------
At the very first step, you need to download the updated ruleset. In order to do that, you should go to "http://www.snort.com/" and download a ruleset (registerd one is recommended, you do not need to pay for it, you just sign up to their website and then you are going to be able to download it) and save it to the "snort-src" folder. Then run the commands down bellow. Also you should download Splunk from the official website "http://www.splunk.com/", then save the installer to the "snort-src" folder.
Now we got all the prequestics and we can start the installation. By following the instructions you are going to have Snort and its ruleset, OpenAppID, Splunk and an example plugin (to go on for the next ones) installed and also configured (for further results, you should config the files manually). Just run the mentioned commands in order(just have in mind, that it is going to take a while, so relax and grab a cup of coffee!). You are going to have your pc rebooted after the proccesses located at the lines 14 and 16, so do not worry about it:

sepehr@ubuntu-20.04:~$ sudo apt install -y git
sepehr@ubuntu-20.04:~$ git clone https://github.com/sepehrgoodarzi6/Ubuntu-Snort3-Installation-Package/
sepehr@ubuntu-20.04:~$ cd Snort3-Installation-Package
sepehr@ubuntu-20.04:~$ chmod +x Dist-Upgrade.sh
sepehr@ubuntu-20.04:~$ ./Dist-Upgrade.sh
sepehr@ubuntu-20.04:~$ chmod +x Installation-Script.sh
sepehr@ubuntu-20.04:~$ ./Installation-Script.sh
