<p align="center">
  <img src="https://miro.medium.com/max/960/0*41QVp-R2iEIvv06Z.jpg" />
  </p>

# Minecraft Server Tutorial
A tutorial on how to make minecraft servers!

# Getting started
you need:

any version of java (java16 recommended), 
ability to port forward, 
somewhat good internet, 
a somewhat good PC

# Setting up the server
Download a server.jar file, PaperMC is the best one. Link: https://papermc.io/downloads, 
make a run.txt file, and open it. Paste the code below. 

# java -Xmx1G -jar minecraft_server.jar --nogui

^ The code above will create a server with 1GB ram. 
Change the file's name to run.bat, 
doubleclick run.bat. 
Some files will start to pop up, 
after it says "You need to agree to EULA" or something, close the command prompt, 
go to eula.txt, 
and set it from "false" to "true". 
Doubleclick run.bat again, 
now it should turn on your server. 
Go to minecraft, and add a server with the IP "localhost" (without the "),
if you can log into it, you've done everything right. 

# Port forwarding
Go to https://portforward.com/ and follow the instructions, 
you'll need to forward the port 25565. 

# IP
Giving you IP to random strangers on the internet is a bad idea, so I will show you how to make your own domain. 
Go to https://freedns.afraid.org/ and make a account, 
select a domain, 
and open a command prompt. 
Type "ipconfig", 
copy and paste the IPV4 into the "Destination" field. 
Type the name of your server into the Subdomain field (example: gamecraft.uk.to) and 
complete the chapta. 
Done!

# Plugins
You should get most of your plugins from https://spigotmc.org/ or my Github page, 
download the plugin, locate the plugins directory, and put them into there.

# Done
Now you can advertise your server anywhere you want, if I've written something wrong, or you need help, open a issue!

Here's a better tutorial, use it if you dont know how to do something: https://minecraft.fandom.com/wiki/Tutorials/Setting_up_a_server
