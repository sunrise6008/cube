<p align="center"><img src="https://1.bp.blogspot.com/-HdlK19lFAKs/YHhOk94eyvI/AAAAAAAAAXc/fTl0XcUrHXQd4wnZqma2KwA3b1WqJiTbgCNcBGAsYHQ/w640-h416/IMG_20210415_200241.jpg"></p>


<p align="center">
  <a href="https://www.youtube.com/channel/UCVgFuT27u3-4yR1i0PrE3wQ"><b>YOUTUBE</b></a>
  <span> - </span>
  <a href="https://www.instagram.com/strix_21/?igshid=lqd87k2v6v4t"><b>INSTAGRAM</b></a>
  <span> - </span>
  <a href="https://chat.whatsapp.com/DceoeOn5fFF3y5Fr1C8NK0"><b>WHATSAPP GROUP</b></a>
  <span> - </span>
  <a href="https://t.me/Strixkingdom"><b>TELEGRAM</b></a>
  <span> - </span>
  <a href="https://strixkingdom.blogspot.com/?m=0"><b>STRIX.D WEBSITE</b></a>
</p>



**This tool is for Educational Purposes Only, Seeker can gather about your devices data and it generates a random links and ask to allows permission such as location, etc.**


##Seeker Hosts a fake website which asks for Location Permission and if the target allows it, we can get :

* Longitude
* Latitude
* Accuracy
* Altitude - Not always available
* Direction - Only available if user is moving
* Speed - Only available if user is moving


## Tested On :

* Kali Linux
* Ubuntu
* Kali Nethunter
* Termux
* Parrot OS

## Installation

### Kali Linux / Ubuntu / Parrot OS

```bash
git clone https://github.com/Strix2109/seeker.git
cd seeker/
apt update
apt install python3 python3-pip php
pip3 install requests
```


### Termux

```bash
pkg update
pkg upgrade -y
pkg install python php
git clone https://github.com/Strix2109/seeker.git
pip3 install requests
cd seeker/
```


## Usage

```bash
python3 seeker.py -h

usage: seeker.py [-h] [-s SUBDOMAIN]

optional arguments:
  -h, --help            show this help message and exit
  -k KML, --kml         Provide KML Filename ( Optional )
  -p PORT, --port       Port for Web Server [ Default : 8080 ]
  -t TUNNEL, --tunnel   Specify Tunnel Mode [ Available : manual ]

##################
# Usage Examples #
##################

# Step 1 : In first terminal
$ python3 seeker.py -t manual

# Step 2 : In second terminal start a tunnel service such as ngrok
$ ./ngrok http 8080

THANKS FOR VISITING.....
