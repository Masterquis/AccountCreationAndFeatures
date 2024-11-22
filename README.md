<h1>Active Directory Search, Advanced Features, and Account Creation</h1>

<!-- ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo) -->

<h2>Description</h2>
This lab will demonstrate how to use active directory to Search for users when their user group is unknown and determine what group a user is a part of by enabling advanced features. It will also demonstrate how to enable "Recycling Bin" via Windows Administrator Center. It will demonstrate how to create a new user from scratch, but most importantly it will demonstrate how to AUTOMATE user creation with appropriate roles and abilities already intact.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Virtual Box</b> 
- <b>Windows Server 2016</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>

<h2>Program walk-through:</h2>

<p align="center">
Start by navigating to "Users and Computers" in the Tools menu: <br/>
<img src="https://i.imgur.com/4B55FMg.png" height="80%" width="80%" alt="VM and Server 2016 Steps"/>
<br />
<br />
This will allow us to add a user the traditional way (We'll add a user a more efficient way a little later in the lab):  <br/>
<img src="https://i.imgur.com/ips2tPr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
When Searching for a user its important to Search the "Entire Directory" so we don't accidentally miss: <br/>
<img src="https://i.imgur.com/bNPYbL1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
If we want to know what folder a user is a part of we can do this too. First, enable Advanced Features: <br/>
<img src="https://i.imgur.com/clcsyjs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> 
We know Advanced Features are enabled by looking at the updated navigation pane:  <br/>
<img src="https://i.imgur.com/dA72oMz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
By using the Object Tab when a user is found, we can see exactly where the account lives:  <br/>
<img src="https://i.imgur.com/EVdohE9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Next, lets setup the Recycling Bin, First we have to go to the Adminstrative Center:  <br/>
<img src="https://i.imgur.com/KNPAZEe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Once in the Administrative Center, we can Enable Recycling Bin.  <br/>
<img src="https://i.imgur.com/kUXeQLP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
We know the Recylng Bin is enabled when we can see an entry for "Deleted Objects":  <br/>
<img src="https://i.imgur.com/c32vt1i.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Next, setup a Helpdesk Super Account, but this time THE EASY WAY! First Copy the Admin Account:  <br/>
<img src="https://i.imgur.com/wVcmaeh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
We'll set it up as Helpdesk...:  <br/>
<img src="https://i.imgur.com/UobFcGD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Set the password, and make sure it never expires..:  <br/>
<img src="https://i.imgur.com/V3w4nb4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Finalize and Finish up the operation...:  <br/>
<img src="https://i.imgur.com/mCB9C0K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
We now have a Hepdesk account with Administrative Power. This can be done with any level of account easily and efficiently:  <br/>
<img src="https://i.imgur.com/5AbjvDT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
