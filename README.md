# CamPhish
Grab cam shots from target's phone front camera or PC webcam just sending a link.
![cheese](https://1.bp.blogspot.com/-f3geEj7jPKM/XPnMl8Q7O1I/AAAAAAAABQc/FRMfjWD_vwEeCXcWL5FjClHggv3lem0_QCLcBGAs/s1600/uploads%25252Fcard%25252Fimage%25252F851047%25252F7b1a3ea3-c5ff-4ca9-a8e8-bdd988baa384.jpg%25252F950x534__filters%25253Aquality%25252890%252529.jpg)

# What is CamPhish?
<p>CamPhish is techniques to take cam shots of target's phone fornt camera or PC webcam. CamPhish Hosts a fake website on in built PHP server and uses ngrok & serveo to generate a link which we will forward to the target, which can be used on over internet. website asks for camera permission and if the target allows it, this tool grab camshots of target's device</p>

## Features
<p>In this tool I added two automatic webpage templates for engaged target on webpage to get more picture of cam</p>
<ul>
  <li>Festival Wishing</li>
  <li>Live YouTube TV</li>
</ul>
<p>simply enter festival name or youtube's video ID</p>

## This Tool Tested On :
<ul>
  <li>Kali Linux</li>
  <li>Termux</li>
  <li>MacOS</li>
  <li>Ubuntu</li>
  <li>Perrot Sec OS</li>
</ul>

# Installing and requirements
<p>This tool require PHP for webserver, SSH or serveo link. First run following command on your terminal</p>

```
apt-get -y install php openssh git wget
```

## Installing (Kali Linux/Termux):

```
git clone https://github.com/DarkKnightSafe/CamPhish-By-Dark_Knight
cd CamPhish
bash camphish.sh
```
