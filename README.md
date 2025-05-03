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

![424635383-deb7b61f-d18d-462b-a829-a5aaa3ea241c](https://github.com/user-attachments/assets/1ff6359f-910b-40e5-9094-822eebcbf54b)


It displays the following menu and select 2 for Website Attack Vectors:

![424635971-73ad3a4c-03e5-4bb1-993b-5b60c7591458](https://github.com/user-attachments/assets/e33a400a-5c56-48ec-b4e0-a4ae5205bc80)


The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![424636274-10d04651-ca85-41f4-83d9-168ebba93108](https://github.com/user-attachments/assets/27830754-20ee-4a8f-af4c-39e2c48daa81)


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![424636553-84e9d98c-d6a4-4968-b048-13e2e0782d53](https://github.com/user-attachments/assets/3a449d26-0125-44de-b02c-c344c99906d8)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![424637918-e95c8b4b-7fcf-4f07-af23-03e38596c054](https://github.com/user-attachments/assets/3a8a155c-f3b4-4c2a-8217-e97b777dace0)


It shows the following screen in which the option Google can be selected:

![424638278-18a611da-b225-4b2f-b8ca-bd24d98de46d](https://github.com/user-attachments/assets/c5a8c401-30d1-4e71-823d-0bbd9dd9793a)


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![Screenshot 2025-05-03 090816](https://github.com/user-attachments/assets/9ef8a81d-65c6-4bd1-8150-518afda9dd7b)


In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed.
The victim can enter the username and password

![424639082-9c6ef595-8656-479e-95c4-1bd90710e750](https://github.com/user-attachments/assets/50bee8b4-627d-4b73-afd6-d4605bf27a3a)

SET logs the information regarding the Google credentials:

![Screenshot 2025-05-03 090939](https://github.com/user-attachments/assets/f77a63df-d126-4d8d-80f4-73861dbcda38)


SET logs the information in the xml file under /root/.set directory:

![Screenshot 2025-05-03 091031](https://github.com/user-attachments/assets/cafb16be-7a83-4e09-878b-6c6ca32f8489)


## RESULT:
The Social Engineering Toolkit (SET) is used to create a backdoor and is examined successfully.

