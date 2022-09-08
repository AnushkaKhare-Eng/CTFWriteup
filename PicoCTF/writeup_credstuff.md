## Challenge - Credstuff

The challenge included decrytping the password for the user cultiris.
I was given the following files leak.tar which included username.txt and passwords.txt

## Solving the challenge

I identified the line number for the username 'cultris' in the username.txt file and identifed the correspnding poassword on the same line number in the password.txt file.

I found that cultiris's password was cvpbPGS{P7e1S_54I35_71Z3}

I assumed that the password was using the ROT Cipher so applied ROT 13 Cipher from CyberChef

Therefore the flag was picoCTF{C7r1F_54V35_71M3}.
