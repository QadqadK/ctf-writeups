![images](https://github.com/QadqadK/ctf-writeups/blob/356913384392cdee8548036bacc008aa05a28f11/Competition/Wargames2024/images/credQuest.png)

##WGMY{b6d180d9c302d8a8daad1f2174a0b212}

This challenge provided two files, passwd.txt and user.txt which are in Leak_staff.rar file.

![images](https://github.com/QadqadK/ctf-writeups/blob/356913384392cdee8548036bacc008aa05a28f11/Competition/Wargames2024/images/cred.png)

Apparently, I was supposed to search for the keyword "osman" in the user.txt file, but I tried to directly find the flag in the passwd.txt file by typing the keyword "wgmy", but that didn't work as the corresponding line is not the same format as the flag. 

![images](https://github.com/QadqadK/ctf-writeups/blob/356913384392cdee8548036bacc008aa05a28f11/Competition/Wargames2024/images/cred2.png)

Then, I searched for the keyword "{" to find the flag and yields two result. The correct one is the same format as the flag, but looks like it was encoded using Caesar Cipher

![images](https://github.com/QadqadK/ctf-writeups/blob/356913384392cdee8548036bacc008aa05a28f11/Competition/Wargames2024/images/cred3.png)

To decode the message, i simply use the website https://www.dcode.fr/caesar-cipher to brute force the answer. Thus the flag revealed. 

![images](https://github.com/QadqadK/ctf-writeups/blob/356913384392cdee8548036bacc008aa05a28f11/Competition/Wargames2024/images/cred4.png)
