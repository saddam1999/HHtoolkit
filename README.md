# Hertz Hacker Toolkit

                
<p align="center">
  <a href="https://twitter.com/takadymp">
    <img src="https://img.shields.io/badge/Created%20By-The%20Hertz%20Project-blue">
  </a> 
  <a href="https://wikipedia.org/wiki/Shell_script">
    <img src="https://img.shields.io/badge/language-shell-green.svg">
 </a>
<a href="https://github.com/entynetproject/ehtools">
<img src="https://img.shields.io/badge/Based%20On-ehtools-red"></a>
</p>

***

# About hhtools Framework

```
The Hertz Hacker Toolkit (HHToolkit) is a suite of tools written by the Hertz Project to aid in ethical hacking and security research. The HHtoolkit contains several easy to use tools which will allow an ethical hacker to test wireless access points (grabbing WPA handshake, etc), perform basic system management (such as interacting with wlan0), automate several popular security tools (note, these are not built nor maintained by the Hertz Project) and more! Additionally, it is very easy to install and use!
```

***

# Getting started

## hhtools installation

hhtoolkit doesnt need to be installed. Simply download and run it from anywhere!

## hhtools uninstallation

As hhtoolkit isnt installed, simply delete the folder!

***

# hhtools Framework execution

```
To run hhtools Framework you should 
execute the following command.
```

> hhtools

***



# UX/UI impruvements for beginners

```
The hhtoolkit starts by merely typing the letter hhtools into a terminal window, 
then it asks for the name of your network interfaces after the first run. It uses the names 
you supply to connect to the tools needed to execute any attacks you select. Aside from that 
initial input, the majority of the possible attacks can be performed merely by choosing the 
option number from the menu. This means you can grab a network handshake or download a 
new hacking tool like Pupy by just selecting from one of the menu options.
```

***

# Basic networking tools

> (hhtools)> if

```
Runs ifconfig and gives the names and 
information about all network devices.
```

> (hhtools)> 1

```
Enable wlan0. 
(d1 disables it)
```

> (hhtools)> 2

```
Enable wlan0mon. 
(d2 disables it)
```

> (hhtools)> 3    

```
Randomize or set the MAC 
address to a specific value.
```

> (hhtools)> 7     

```
View the public IP address your 
computer is leaving on sites you visit.
```

> (hhtools)> 19    

```
Look up the physical address of a given IP 
address to determine it's relative location.
```

> (hhtools)> scan   

```
Start an ARP scan on the network 
to discover nearby devices.
```

> (hhtools)> start  

```
Start monitor mode on the 
wireless network adapter.
```

> (hhtools)> stop

```
Stop wireless monitor mode 
on the network adapter.
```

***

# Installing new tools

```
Part of the fun of hhtools Framework is how easy it is to add new tools to our arsenal. 
We can select option 9 to access the list of tools in hhtools Framework. From the next 
menu, the tools are broken down into major categories, with options for managing the 
installation of scripts. The options presented are:
```

**1.** Wi-Fi tools (tools for attacking wireless networks).

```
Wi-Fi options this is tools for attacking 
wireless networks and network databases.
```

**2.** Remote access (tools for getting remote access to other devices and remotely managing them).

```
Remote access means tools for getting access 
to other devices and remotely managing them.
```

**3.** Information gathering (collecting intelligence on people or website).

```
Information gathering tools, tools for 
collecting intelligence on peaple or website.
```

**4.** Website tools (tools for exploiting or attacking sites).

```
Website tools, tools for exploiting or 
attacking sites and network databases.
```

**5.** Other (a miscellaneous collection of other hacking tools)

```
Other tools this is collection 
of miscellaneous hacking tools.
```

 * You can also manage your installed tools by accessing option 6.

# hhtools Framework application 

```
hhtools application is an hhtools Framework shortcut 
that allows users to run hhtools Framework just selecting 
hhtools in the applications and clicking on it! I mean hhtools 
application allows users to run hhtools via the application!
```

 * There are two ways how to setup hhtools application.

## Using the installer

```
The hhtools install.sh allows 
you to create hhtools application.
```

## Using the hhtapp

```
There is an hhtools utility named hhtapp 
(read more in hhtools Utilities) that allows 
users to configure hhtools application.
```

> hhtapp -c

***

# Why hhtools Framework

* More than 58 tools for pentesting installed by default.

```
More than 58 options installed by default 
you can find in hhtools, this is tools such 
as MetaSploit, Pupy and other tools!
```

* Password protection and config encryption.

```
In version 2.1.6 we added pasword protection, we added 
it for users who think that his/her friend or parents will 
turn into hhtools and will remove or destroy it. Only for this 
people we created hhtools Framework password protection.
```

* UX/UI impruvements for beginners.

```
It uses the names you supply to connect to the tools needed to 
execute any attacks you select! Aside from that initial input, the majority 
of the possible attacks can be performed merely by choosing the option number 
from the menu. This means you can grab a network handshake or download a new 
hacking tool like Pupy by just selecting from one of the menu options!
```



***

# hhtools Framework utilities

## hhtmod | <img src="https://img.shields.io/badge/utility-hhtmod-blue.svg">

* hhtmod (hhtools modules) is an utility that adds permissions or the ability to control the hhtools Framework modules.
 
> hhtmod -h

```
Usage: hhtmod [option] <arguments>

  -i, --install         Install hhtools modules.
  -t, --take    <name>  Take a new hhtools modules snapshot.
  -r, --restore <name>  Restore saved hhtools modules snapshot.
  -d, --delete  <name>  Delete saved hhtools modules snapshot.
  -u, --uninstall       Uninstall hhtools modules.
  -h, --help            Give this help list.
```
         
* To install hhtools modules you need to execute the following command.

```
The hhtools install.sh will ask you to "install" or "not 
install" hhtools modules and if you answered "not install" and 
want to install them, run the following command!
```

> hhtmod -i

### hhtools Modules Snapshot (EMS) 

```
EMS is a saved hhtools modules data, you can 
take it using the hhtmod utility and restore it.
```

* To take hhtools modules snapshot you need to execute the following command. You need to enter the name of the hhtools modules snapshot you want to take (example: snapshot1).

> hhtmod -t snapshot1

### hhtools Modules Restoration (EMR) 

```
EMR is an operation that removing modules and restoring it from 
the saved hhtools modules snapshot, you can restore it using the 
hhtmod utility but ESR will remove all your old hhtools modules data!
```

* To restore hhtools modules snapshot you need to execute the following command. You need to enter the name of the saved hhtools modules snapshot (example: snapshot1).

> hhtmod -r snapshot1
    
## hhtkey | <img src="https://img.shields.io/badge/utility-hhtkey-brown.svg">

* hhtkey (hhtools key) is an utility that allows you to change your hhtools config key (hhtools config/boot key) and rewrite /etc/hhtools/.config.

> hhtkey

```
Usage: hhtkey [option] <arguments>

  -c, --change <old_key> <new_key>  Change hhtools config key.
  -h, --help                        Give this help list.
```

* To change hhtools config key you need to execute the following command. You need to enter your old hhtools config key (example: 1001) and after this enter your new hhtools config key (example: 2002).

> hhtkey -c 1001 2002

## hhtapp | <img src="https://img.shields.io/badge/utility-hhtapp-red.svg">

* hhtapp (hhtools application) is an utility that allows you to configure hhtools application, for example creating hhtools desktop application.
 
> hhtapp -h
 
```
Usage: hhtapp [option] <arguments>

  -c, --create               Create hhtools application.
  -d, --desktop <operation>  Create/remove hhtools desktop application.
  -r, --remove               Remove hhtools application.
  -h, --help                 Give this help list.
```

* To create hhtools application you need to execute the following command.

```
The hhtools install.sh will ask you to "create" or 
"not create" hhtools application and if you answered "not 
create" and want to create it, run the following command!
```

> hhtapp -c

* To create hhtools desktop application you need to execute the following command.

> hhtapp -d create

## epasswd | <img src="https://img.shields.io/badge/utility-epasswd-green.svg">

* epasswd (hhtools password changer) is an utility that allows you to change your hhtools login and password or hhtools root password.

### Changing hhtools login and password

> epasswd

* To change hhtools login and password enter your old hhtools login (example: hhtools) and your old hhtools password (example: sloothe).

> (login)> hhtools

> (password)> sloothe

* After this enter your new hhtools login (example: admin) and your new hhtools password (example: 1234).

> ((new)login)> admin

> ((new)password)> 1234

* Congratulations, you have successfully changed hhtools login and password!

```
In no case do not forget this password, it will not 
be restored and you will need to reinstall hhtools!
```

### Changing hhtools root password

* To cange root password, login to epasswd as hhtools root.

> epasswd

> (login)> root

* After this enter your old hhtools root password (default: toor).
 
> (password)> toor

* After this enter your new hhtools root password (example: 1234).

> ((new)password)> 1234

* Congratulations, you have successfully changed hhtools root password!

```
In no case do not forget this password, it will not 
be restored and you will have to reinstall hhtools!
``` 
***
    

# hhtools Framework disclaimer

```
Usage of the hhtools Framework for attacking targets without prior mutual consent is illegal.
It is the end user's responsibility to obey all applicable local, state, federal, and international laws.
Developers assume no liability and are not responsible for any misuse or damage caused by this program.
```
