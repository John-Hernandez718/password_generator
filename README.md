# Password_Generator




<h1>Automation Script</h1>

 ### [YouTube Demonstration Coming Soon]()

<h2>Description</h2>
In this project, I utilized the Python programming language to develop a sophisticated password generator featuring a distinctive logo crafted using Canvas. The generator incorporates a randomization algorithm for creating secure passwords, encompassing numbers, symbols, and letter characters. Furthermore, a user-friendly graphical user interface (GUI) was implemented to facilitate seamless interaction, allowing users to input and manage data for websites, emails, and passwords. Additionally, a text file was created to serve as a secure log for storing the generated data.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Powershell</b>
- <b>Terminal</b>
- PyCharm Community Edition 2023.2.1
  

<h2>Environments Used </h2>

- <b>Windows 11</b> 

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://imgur.com/g43HMYR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Use the list command:  <br/>
<img src="https://imgur.com/hudxKlL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Open up the project :  <br/>
<img src="https://imgur.com/F6ayYlt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
A sophisticated interface features a dialog box prompting users to input essential data, preventing bypass attempts and ensuring data integrity:  <br/>
<img src="https://imgur.com/Ip0aM6u.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
I ran a command to read a text file and no data is on the file:  <br/>
<img src="https://imgur.com/QcYlMwe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
I imported data via the graphical user interface, which was then persisted into a text file, and upon rerunning the command, the system intelligently retrieved and processed the updated information from the file. :  <br/>
<img src="https://imgur.com/MGZxd8r.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
I used Tkinter to build a graphical interface, included message boxes, implemented a password generator using randomization, and integrated clipboard functionality with pyperclip in my Python script. : <br/>
<img src="https://imgur.com/lWOMSCq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
The function generate_password() creates a random password consisting of letters (both uppercase and lowercase), numbers, and symbols, with varying lengths for each category, then shuffles and combines them into a unique password, which is displayed in a graphical user interface entry field and copied to the clipboard.: <br/>
<img src="https://imgur.com/2zLsx7Q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The save() function validates and ensures non-empty entries for website, email, and password, displaying an error if necessary. Upon user confirmation, it appends the entered details to a "data.txt" file and clears the input fields for further use.: <br/>
<img src="https://imgur.com/pxauCS8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
This Python code utilizes Tkinter to build a simple password manager GUI with labeled entry fields for website details, email/username, and passwords. It includes buttons for generating passwords and saving entries, each linked to corresponding functions in the code.: <br/>
<img src="https://imgur.com/m1gk6u2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
