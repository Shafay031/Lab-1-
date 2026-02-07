**Digital Forensics**

**Lab 1**


1.If we wanted to list all the .txt files in the current directory, what command would we want to use?

Ans.we can use "ls *.txt" command to list all txt files.

<img width="277" height="62" alt="image" src="https://github.com/user-attachments/assets/43adf293-11a4-458f-8e71-091deacfa3aa" />


2.What command can we use to read the contents of the file /etc/passwd?

Ans.we can use "cat /etc/passwd" command to read content of files.

<img width="272" height="53" alt="image" src="https://github.com/user-attachments/assets/ab1eec35-5469-4d95-82c9-0dbbcb4fc71c" />

3.If we wanted to search for the string Error in all files in the /var/log directory, what would our command be?

Ans.use "grep "strig" file name" to search the string in the file.

<img width="362" height="65" alt="Screenshot 2026-02-07 120848" src="https://github.com/user-attachments/assets/8a2304e2-bcb3-45bb-866b-8d7e4049b059" />

4.What would be the commands to calculate MD5 and SHA1 hashes of the file /etc/passwd?

Ans.use "md5sum file name" to make a md5 hash of the file.

<img width="393" height="70" alt="Screenshot 2026-02-07 121116" src="https://github.com/user-attachments/assets/45edba74-827d-48e5-a71b-41d5a21704f7" />

5.What command can we use to display all printable strings of length ≥ 8 in the file /bin/bash?

Ans.use "strings -n 8 filename" to see all printable strings that are 8 characters or longer.

<img width="325" height="67" alt="Screenshot 2026-02-07 133526" src="https://github.com/user-attachments/assets/a3d3a849-e84f-44fa-a2de-ace6d2b6a5f2" />

6.If we wanted to look for files modified in the last 30 minutes in /home directory, what command would we want to use?

Ans.to see the files that modified in the last 30 minutes in home directory use this command "find /directoryname -type f -mmin -30" or to get some more details use "find /home -type f -mmin -30 -ls".

<img width="841" height="163" alt="image" src="https://github.com/user-attachments/assets/208c7f29-aad4-4801-8d16-af81bfa5835c" />

7.What command can we use to display information about all active TCP connections on the system?

Ans.To see the information about network connections on a system use command "netstat".

8.Given this corrupted image file, can you find a way to recover and view its contents?

Ans.With the help of hexedit i recovered the image and now the image is not corrupted anymore.

<img width="616" height="44" alt="Screenshot 2026-02-07 140541" src="https://github.com/user-attachments/assets/9cf0b1fd-524c-43f3-9e8e-0626f693961c" />



<img width="220" height="52" alt="Screenshot 2026-02-07 140630" src="https://github.com/user-attachments/assets/16c4c88a-07ff-4e92-bbae-7ffe72391a37" />

Here is the image

<img width="561" height="424" alt="Screenshot 2026-02-07 140716" src="https://github.com/user-attachments/assets/b5f8091e-4eda-4a4c-a948-7dfeaf6764bc" />
















