# Nice-netcat..
This script is used to solve the nice netcat.. problem on picoCTF. The challenge requires you to read from a network connection using netcat. The connection outputs ASCII code, this script reads the ASCII numbers from the file and converts to English text.  

After dumping the netcat output to a text file by utilising the command
````nc mercury.picoctf.net 43239 > ascii.txt```` you will be presented with a text file with similar contents:

![image](https://github.com/Mrlukerwilkinson/Nice-netcat../assets/140768032/c1278d0d-e4e6-4ae3-9b4e-8fcbeecd9ef3)

After editing the code snippet to include the text file as the input, and then running the script you should receive the new output displayed in English as per screenshot below. 

<img width="196" alt="image" src="https://github.com/Mrlukerwilkinson/Nice-netcat../assets/140768032/3cb80f33-2e79-4aec-9d7b-aa3353f7c2b9">


