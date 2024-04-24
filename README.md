# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:

![output1](https://github.com/kiruthika512/creating-a-backdoor-with-SET/assets/135616605/82b3bb5a-3653-47bd-b4df-1af8a5f66630)

It displays the following menu and select 2 for Website Attack Vectors:

![output2](https://github.com/kiruthika512/creating-a-backdoor-with-SET/assets/135616605/7c313ba7-7732-440a-a98c-54dd762db518)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![output3](https://github.com/kiruthika512/creating-a-backdoor-with-SET/assets/135616605/899dbbc6-662f-4494-adf4-129ae20ccbdf)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![output4](https://github.com/kiruthika512/creating-a-backdoor-with-SET/assets/135616605/e86cee7c-7ed6-493d-b46f-708b1a7d9b14)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![output5](https://github.com/kiruthika512/creating-a-backdoor-with-SET/assets/135616605/21c143bd-d2fc-4531-803b-f145d9b178c9)

It shows the following screen in which the option Google can be selected:

![output6](https://github.com/kiruthika512/creating-a-backdoor-with-SET/assets/135616605/1958ca7c-f27e-42a2-a019-f9550ec63c15)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![output7](https://github.com/kiruthika512/creating-a-backdoor-with-SET/assets/135616605/ef633918-da67-43e6-8202-5ed1f93cf718)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![output8](https://github.com/kiruthika512/creating-a-backdoor-with-SET/assets/135616605/bd2ed841-f0a7-4528-aad6-8f6fedea953b)

SET logs the information regarding the Google credentials:

![output9](https://github.com/kiruthika512/creating-a-backdoor-with-SET/assets/135616605/39832c1a-3553-4f7a-bb23-1dee3476c052)

SET logs the information in the xml file under /root/.set directory:

![output10](https://github.com/kiruthika512/creating-a-backdoor-with-SET/assets/135616605/ee5d51f8-c25b-4b8e-9e67-9caefce4a0c3)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
