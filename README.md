<h1>VM-Provisioning</h1>



<h2>Description</h2>
This project outlines the step-by-step process to provision Virtual Environment using vagrant.<br />


<h2>Languages and Utilities Used</h2>

- <b>BashShell</b> 
- <b>Vagrant</b>
- <b>VirtualBox</b>

<h2>Environments Used </h2>

- <b>Ubuntu</b>

<h2>Program walk-through:</h2>

<p align="center">
Launch the vagrantfile: <br/>
After the installation of the VirtualBox and Vagrant on my system, I proceeded with the setup of the development environment. I created a directory "vagrant_project" and created a file "Vagrantfile".
 
<img src="https://i.imgur.com/KRCymP5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Inside the Vagrantfile:  <br/>
I wrote the following lines of code into vagrantfile
Vagrant.configure("2") do |config|
config.vm.box = "base"
config.vm.box = "kalilinux/rolling"

<img src="https://i.imgur.com/xZWOOQR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Using vagrant up to provision the VM: <br/>
After the inputting the above following lines. of code, I save and run the configuration file for creating a vagrant machine

<img src="https://i.imgur.com/qSeHTh4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
connecting to to the VM via ssh:  <br/>
I try to connect to the Vagrant VM using ssh. "vagrant ssh"

<img src="https://i.imgur.com/WIdiOqf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
