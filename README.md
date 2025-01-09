
<h1>File And Directory Manipulation</h1>


<h2>Description</h2>
Project consists of a simple PowerShell script that walks the user through "zeroing out" (wiping) any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Bash</b> 


<h2>Environments Used </h2>

- <b>Kali Linux</b> (21H2)

<h2>Walk-Through:</h2>

<p align="left">
1) Create a file “file1” using nano editor with the following content (River is green)
  (use cat to show the content of the file):
 <br>
 <br/>
<img src="https://i.imgur.com/DUV6TF5.png" height="80%" width="80%" alt="File And Directory Manipulation Question 1"/>
<img src="https://i.imgur.com/HJFPaoc.png" height="80%" width="80%" alt="File And Directory Manipulation Question 1"/>
<img src="https://i.imgur.com/7LMcWAn.png" height="80%" width="80%" alt="File And Directory Manipulation Question 1"/>

<p align="left">
2) Create a file “file2” with the following content (stream is red) using echo command 
  (use cat to show the content):
 <br>
 <br/>
<img src="https://i.imgur.com/Q7jWpBJ.png" height="80%" width="80%" alt="File And Directory Manipulation Question 2"/>

<p align="left">
3) Combine file1 and file2 into file file3 using cat command
  (use cat to show the content of f3):
 <br>
 <br/>
<img src="https://i.imgur.com/LsgDD7W.png" height="80%" width="80%" alt="File And Directory Manipulation Question 3"/>

<p align="left">
4) Create a copy of file3 and name it as file4 using cp command:
 <br>
 <br/>
<img src="https://i.imgur.com/2w4YKBf.png" height="80%" width="80%" alt="File And Directory Manipulation Question 4"/>

<p align="left">
5) Create a directory “hello”:
 <br>
 <br/>
<img src="https://i.imgur.com/WaosfcJ.png" height="80%" width="80%" alt="File And Directory Manipulation Question 5"/>

<p align="left">
6) Move (not copy) file file4 to directory “hello”:
 <br>
 <br/>
<img src="https://i.imgur.com/D1GES3O.png" height="80%" width="80%" alt="File And Directory Manipulation Question 6"/>

<p align="left">
7) Delete file3 using rm command:
 <br>
 <br/>
<img src="https://i.imgur.com/K93RYPf.png" height="80%" width="80%" alt="File And Directory Manipulation Question 7"/>


<p align="left">
8) Delete directory hello using rm command:
 <br>
 <br/>
<img src="https://i.imgur.com/PpZtDBQ.png" height="80%" width="80%" alt="File And Directory Manipulation Question 8"/>
<img src="https://i.imgur.com/YRQCx5V.png" height="80%" width="80%" alt="File And Directory Manipulation Question 8"/>

