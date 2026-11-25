# thm_ctfs
Let's begin with the nmap scan and see if we find anything
<img width="472" height="261" alt="image" src="https://github.com/user-attachments/assets/cfdab8cd-0ca0-4289-b8a8-e4c8fabf4cc7" />

There is a webbrowser on this IP address lets go  to the address and see what we find.

<img width="959" height="371" alt="image" src="https://github.com/user-attachments/assets/1860bf93-2444-4fd9-a2a8-0a9a1aaccf2f" />

Well it is an admin dashboard lets explore this and see if  we find anything.

Nothing special on the website have checked all the button and tried different things but nothing so far.
Let's try subdomain enumeration.

<img width="466" height="295" alt="image" src="https://github.com/user-attachments/assets/9d94a9a1-681c-4aa2-9a22-e03eb91feed5" />
Noting on directory enumeration lets look further in the website.
<img width="942" height="271" alt="image" src="https://github.com/user-attachments/assets/27d077b4-a673-4463-980d-083a15ffcda1" />

Well I find something in the network request lets explore this further.
I did some exploring and found a link to the exploit https://www.exploit-db.com/exploits/49933
Lets create a file and try to execute this code.
<img width="472" height="325" alt="image" src="https://github.com/user-attachments/assets/f9770c60-75b2-4c85-a49d-a0db440aef10" />
well I got the root access
<img width="289" height="320" alt="image" src="https://github.com/user-attachments/assets/01aafbcb-011b-474a-93e1-7036e6f59ba2" />
Found a file  name flag.txt let see  what is inside 

<img width="319" height="75" alt="image" src="https://github.com/user-attachments/assets/4cb7eee0-adfc-4915-ba80-7fa529af891c" />
Yup! there's flag inside Bingo!!!
