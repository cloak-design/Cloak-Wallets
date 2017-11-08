# Cloak-Wallets
<h3>Overview</h3>
<p>Cloakcoin 2.0.2.1 'DEFENDER' for Windows, Linux, MacOS and Raspberry Pi</p>
 
We are very pleased to present to you the latest update to the CloakCoin core software.
 
Version 2.0.2.1 as indicated by the 'DEFENDER' codename focuses on security enhancements. This release brings added security improvements to the Enigma and CloakShield communication layer, full details can be found on the list of improvements and enhancements.  Also arriving with this release are the translation sets for French and Russian as well some minor bug fixes, the QT GUI received some functionality and cosmetic touches.

<b>Windows Wallet</b><br />
INSERT GITHUB DOWNLOAD LINK

<b>Mac OSX Wallet</b><br />
INSERT GITHUB DOWNLOAD LINK

<b>Linux Wallet</b><br />
INSERT GITHUB DOWNLOAD LINK

<h3>Instructions</h3>

<b>Windows installation</b><br />
<li>If you have installed a previous version, please stop the running wallet.</li>
<li>Backup your wallet.dat</li>
<li>If your previous version is CloakCoin 1.x, please make a deinstallation!!!</li>
<li>If your previous version is CloakCoin 2.x, you can make an update and dont need to make a deinstallation.</li>
<li>Unzip the download.</li>
<li>Now start the downloaded exe file and run it as an administrator.</li>
<li>Follow the instructions from the installer.</li>
<li>Say yes to the 'auto blockchain downloader' this will be the fastest way!</li>
<li>Start your new Cloakcoin 2.0 wallet and let it find other nodes and sync the blockchain</li>
Enjoy CloakCoin!!

<b>Mac OSX installation</b><br />
Download Mac Wallet
Extract zip file and start cloakCoin-qt.xxxx.dmg
Drag & Drop the cloakCoin-qt App in the Application Folder
Start cloakCoin-qt App in Application Folder -> you will get a warning that the app is from a unidentified developer
Choose Apple menu > System Preferences, then click Security & Privacy. Read more.
You need to unblock the app by clicking the 'Open Anyway' in Security & Privacy
the cloakCoin-qt app will continue with the instalation.
You will get a warning: 'Cant find local blockchain…..Would you like to auto-download it?'
Click 'Yes'
when the blockchain finnishes downloading cloakCoin-qt app will be running and in full sync!
Always remember  -> to Encrypt your wallet via password Keyphrase! + backup your wallet.dat on a USB Stick or External Harddrive. Just to be sure!

<b>Linux installation</b><br />
If you have installed a previous version, please stop the running wallet.
Backup your wallet.dat
Remove the old installation
Open a terminal as user
cd
mv .CloakCoin .CloakCoin_backup
Unzip the download.
Open a terminal with root rights
cd /opt
mkdir -vp cloakcoin/2.0.2.1_defender
cd !$
mv /path/to/unzipped/cloakcoin* .
chmod +x cloakcoin*
ln -s /opt/cloakcoin/2.0.2.1_defender/cloakcoin-qt /usr/local/bin/cloakcoin
On some debian/ubuntu distributions you need to installing missing libs as with root privileges:
apt-get update
apt-get install libcurl3 libcurl3-gnutls
run cloakcoin with your user account
Follow the instructions from the installer.
Say yes to the 'auto blockchain downloader' this will be the faster way!
Let your wallet find other nodes and sync the blockchain
Enjoy CloakCoin!!
 

If cloakcoin doesnt start, please post the output of

dd cloakcoin-qt | grep found
to the comments with your distribution name and version.
