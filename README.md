<center>
  <h1 align="center">Uncursus</h1>
  <h3 align="center">a installation script that allows Procursus as its bootstrap</h3>
  <br/>
  <h4 align="center">Note: It's not recommended by the Procursus maintainers to run this script, support will not be provided so please do not go contacting Diatrus.</h4>
</center>

### Installation:
***Disclaimer: I am not held responsible for any damage done to your device.***<br/>
***Note: you must have a computer to launch the script via SSH, you cannot use NewTerm.***<br/>
***Note: I recommend that you know what you're doing***<br/>
1) You don't need to restore rootfs anymore Tweaks/Apps Are saved<br/>
2) Refresh sources in Cydia and install `OpenSSH` and `Curl`<br/>
3) Find the IP of your iDevice and connect to it via SSH on your computer. Don't know what SSH is or how to use it? Refer to: https://www.hostinger.com/tutorials/ssh-tutorial-how-does-ssh-work<br/>
4) Use the following command in your SSH session for installation:<br/>
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Yaya48/Uncursus/new/installuncursus.sh)"`<br/>
5) Once your device resprings, launch Sileo and you're good to go.<br/>

***For All Users Cannot Have A Pc I Made a Non-Computer Version***<br/>
***Note: Disclimer This still in beta***<br/>
1) You don't need to restore rootfs anymore Tweaks/Apps Are saved
2) Add https://repo.yaya48.gq in cydia
3) Install Uncursus Installer
4) Enter In Terminal And Log In As Root With Default Passworld Type: su after alpine
5) Run uncursus-installer and wait
6) When Is Finished Your Device Will Respring After Open Sileo Do Update And Enjoy

### Questions & Support:
- Discord: Yaya4#1989
- Twitter: [@Yaya4_4](https://twitter.com/Yaya4_4)

***Note: The support is not made for install help but for bug reports or ask questions all install steps is here***<br/>

### Credits:
[Procursus Team](https://github.com/ProcursusTeam/) - for the bootstrap<br/>
[CoolStar](https://github.com/coolstar/) - for the deploy script<br/>
knuckles approver#1119 (on Discord) - for the testing and name of the project<br/>
