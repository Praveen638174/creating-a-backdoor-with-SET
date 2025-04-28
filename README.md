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
![image](https://github.com/AsinVardhini/creating-a-backdoor-with-SET/assets/119417735/63777890-237e-48fc-8717-8a1dd35dceb3)

It displays the following menu and select 2 for Website Attack Vectors:
![image](https://github.com/AsinVardhini/creating-a-backdoor-with-SET/assets/119417735/861615c9-2315-48a9-b894-a3447223839a)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![image](https://github.com/AsinVardhini/creating-a-backdoor-with-SET/assets/119417735/bad25290-d542-42a2-a6c6-557e25bebec2)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
![image](https://github.com/AsinVardhini/creating-a-backdoor-with-SET/assets/119417735/069a27c5-c26c-4879-bb4b-1d33d34b8298)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![image](https://github.com/AsinVardhini/creating-a-backdoor-with-SET/assets/119417735/b4dd7564-de55-437b-94ae-d716800eb28d)

It shows the following screen in which the option Google can be selected:
![image](https://github.com/AsinVardhini/creating-a-backdoor-with-SET/assets/119417735/c274553b-8037-423c-b20d-a266f535941a)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
![image](https://github.com/AsinVardhini/creating-a-backdoor-with-SET/assets/119417735/559638dd-3271-4b4e-a44c-cff62000b67a)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed.
The victim can enter the username and password
![image](https://github.com/AsinVardhini/creating-a-backdoor-with-SET/assets/119417735/cdff94c7-af85-4bd4-b076-26cf1651a673)

SET logs the information regarding the Google credentials:
![image](https://github.com/AsinVardhini/creating-a-backdoor-with-SET/assets/119417735/9b08b886-8601-43db-a8db-2debbbfb66ff)

SET logs the information in the xml file under /root/.set directory:
![image](https://github.com/AsinVardhini/creating-a-backdoor-with-SET/assets/119417735/8195f72c-c634-4d50-b1a7-bd1f6675b893)



## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
