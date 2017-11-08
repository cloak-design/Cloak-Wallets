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

## Instructions

### Windows installation
1. If you have installed a previous version, please stop the running wallet.
2. Backup your wallet.dat
3. If your previous version is CloakCoin 1.x, please make a deinstallation!!!
4. If your previous version is CloakCoin 2.x, you can make an update and dont need to make a deinstallation.
5. Unzip the download.
6. Now start the downloaded exe file and run it as an administrator.
7. Follow the instructions from the installer.
8. Say yes to the 'auto blockchain downloader' this will be the fastest way!
9. Start your new Cloakcoin 2.0 wallet and let it find other nodes and sync the blockchain
<br />
<b>Mac OSX installation</b><br />
<li>Download Mac Wallet</li>
<li>Extract zip file and start cloakCoin-qt.xxxx.dmg</li>
<li>Drag & Drop the cloakCoin-qt App in the Application Folder</li>
<li>Start cloakCoin-qt App in Application Folder -> you will get a warning that the app is from a unidentified developer</li>
<li>Choose Apple menu > System Preferences, then click Security & Privacy. Read more.</li>
<li>You need to unblock the app by clicking the 'Open Anyway' in Security & Privacy</li>
<li>The cloakCoin-qt app will continue with the installation.</li>
<li>You will get a warning: 'Cant find local blockchain…..Would you like to auto-download it?'</li>
<li>Click 'Yes'</li>
<li>When the blockchain finnishes downloading cloakCoin-qt app will be running and in full sync!</li>
<li>Always remember  -> to Encrypt your wallet via password Keyphrase! + backup your wallet.dat on a USB Stick or External Harddrive. Just to be sure!</li>
<br />
<b>Linux installation</b><br />
<li>If you have installed a previous version, please stop the running wallet.</li>
<li>Backup your wallet.dat</li>
<li>Remove the old installation</li>
<li>Open a terminal as user</li>
<li>cd</li>
<li>mv .CloakCoin .CloakCoin_backup</li>
<li>Unzip the download.</li>
<li><li>Open a terminal with root rights</li>
<li>cd /opt</li>
<li>mkdir -vp cloakcoin/2.0.2.1_defender</li>
<li>cd !$</li>
<li>mv /path/to/unzipped/cloakcoin* .</li>
<li>chmod +x cloakcoin*</li>
<li>ln -s /opt/cloakcoin/2.0.2.1_defender/cloakcoin-qt /usr/local/bin/cloakcoin</li>
On some debian/ubuntu distributions you need to installing missing libs as with root privileges:
apt-get update
apt-get install libcurl3 libcurl3-gnutls
run cloakcoin with your user account
Follow the instructions from the installer.
Say yes to the 'auto blockchain downloader' this will be the faster way!
Let your wallet find other nodes and sync the blockchain


If cloakcoin doesnt start, please post the output of

dd cloakcoin-qt | grep found
to the comments with your distribution name and version.

<br />
