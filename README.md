# [TabChi v4](https://t.me/MemberPlus_tm)

[![https://github.com/sajjad-021/Tabchi](https://img.shields.io/badge/license-AGPL-blue.svg)](https://github.com/sajjad-021/Tabchi)
[![http://t.me/sajjad_021](https://img.shields.io/badge/Telegram-sajjad__021-blue.svg)](http://t.me/sajjad_021)
[![https://github.com/sajjad-021/Tabchi](https://img.shields.io/badge/%F0%9F%92%AC_GitHub-Tabchi-green.svg)](https://github.com/sajjad-021/Tabchi)
[![http://tgmember.cf](https://img.shields.io/badge/webpage-tgMember-ff69b4.svg)](http://tgmember.cf)

[![https://t.me/MemberPlus_TM](https://img.shields.io/badge/%F0%9F%92%AC_Telegram-MemberPlus_TM-blue.svg)](https://t.me/MemberPlus_TM)
[![https://github.com/vysheng](https://img.shields.io/badge/%F0%9F%92%AC_GitHub-vysheng-green.svg)](https://github.com/vysheng)

<p align="center"> ![http://member-adder.ir/img/member+.png](http://member-adder.ir/img/member+.png)

TG-CLI based broadcasting bot!

****

##Install
```
git clone https://github.com/sajjad-021/TabChi.git -b Tabchi
cd TabChi
chmod 777 install.sh
./install.sh
```
 
##Create a bot
```
lua creator.lua
```         

Enter Tabchi ID : 111
Enter id of tabchi in "ID" part (it can be anything but should be unique)

Enter Full Sudo ID : 123456    
Enter your telegram Id in "Full Sudo ID" part
---you can see your account Id Number in [@UserInfoBot](https://t.me/userinfobot)---

Then

```sh
./tabchi-111.sh           # Enter a phone number & confirmation code.
```
         
##Anti crash
```
tmux new-session -s script "bash tabchi-111.sh -t"
```

##Stay Online
after run bot, you must send messege from the bot in the [@TgMessengerBot](https://t.me/TgMessengerBot)
This is for stay online your bot and dely result 


##Run agin
You can stop the script by pressing Control+C in the script session. Alternatively, you can tmux kill-session -t script or also killing all tmux processes killall tmux

```
killall tmux -u xxx
tmux new-session -s script "bash tabchi-111.sh -t"
```
you shoud enter user name of account server replace in the xxx

### Two command
To install everything in one command (useful for VPS deployment) on Debian-based distros, use:
```sh
sudo apt-get update; sudo apt-get upgrade -y --force-yes; sudo apt-get dist-upgrade -y --force-yes; sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev libjansson* libpython-dev make unzip git redis-server g++ autoconf -y --force-yes && git clone https://github.com/sajjad-021/TabChi.git -b Tabchi && cd TabChi && chmod 777 install.sh && ./install.sh -y --force-yes; lua creator.lua
```
Enter Full Sudo ID : xxxxxx    
[@UserInfoBot](https://t.me/userinfobot)
Then
```sh
tmux new-session -s script "bash tabchi-0.sh -t"    # Enter a phone number & confirmation code.
```
***

##Instruction and commands 
in the 
# [MemberPlus_TM](https://t.me/MemberPlus_TM)

***

##Developers


###[open by (sajjad_021)](https://t.me/sajjad_021)
###[channel (MemberPlus_TM)](https://t.me/MemberPlus_TM)

#Powered by [iTeam](https://telegram.me/iTeam_IR)

Enjoy Your New Bot!
