Lab 04 - July 21st 2026

Basic Device Security

Jeremy's IT Labs on YouTube

--------------

Comprehension: The fourth video from Jeremy largely entails familarity with Cisco's IOS CLI.  The command line interface (CLI) system that's available on Cisco devices, is proprietary software made to modify Cisco devices (routers and switches). One would connect a rollover cable from your laptop to the Cisco device. I learned about the different levels of availability within Cisco IOS, such as User Exec Mode, which is very limited, and usually where most people start. One would gain privileges to make modifications by using the `enable` command, to enter Privileged Exec Mode. To start making configurations, simply type `configure terminal`. To save updates whilst still in P.E.M, you can use one of three commands: `write`, `write memory`, or `copy running-config startup-config`. Jeremy goes through the rest of the video talking about what other commands are available that could be of use, and puts more emphasis towards the lab, as it is a better way to demonstrate the theory in a hands-on type setting.

----------------

Lab: This description references the screenshots attached in this same directory. Within Cisco Packet Tracer, we're dealing with a very simple network `(Screenshot 1A)`. The first question asks us to configure the hostnames of the router and switch provided, to R1 and SW1, respectively. On each device, I entered Privileged Exec Mode (command: `en`), used commands `configure terminal`, `hostname R1` for the router or `hostname SW1` for the switch, `exit`. All demonstrated in `(Screenshot Q1_Router.png)` or `(Screenshot Q1_Switch.png)`. Question 2 asks to create an unecrypted enable password of "CCNA" for both, and Question 3 asks us to test the password. Simply be in PEM, use `enable password CCNA`, `exit`, to update each device with it (bottom of `(Screenshot Q1_Router.png)`) . In order to see if the password works, simply exit out of PEM so that you're back in User EXEC Mode, and type `en`. It will prompt the password `(Screenshot Q3)`. The following questions within Jeremy's IT Labs are numbered accordingly, but the entire lab's purpose is to get familiar with configuring Cisco devices via the CLI, such as changing hostnames, unencrypted passwords, updating the running-configuration to become what's on startup, types of encryption, and so forth.
