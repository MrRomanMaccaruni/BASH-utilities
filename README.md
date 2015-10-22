# BASH-utilities
This repo contains some very simple but handy *BASH* scripts to make your IT life a bit easier.

#### Installation
Just copy the selected script to your script folder and create a link in ``/usr/bin/`` (requires root's privileges).

## Number Displayer
A nice tool to deal with numbers base conversion and arithmetic in the computer world.

**Usage**
```
numd.sh [ib] <arithmetic expression>
```
where
```
ib = h/o/d/b = "Input Base"
```
and
```
h = hexadecimal, base 16 (either lower or upper case for letteral digits)
o = octal, base 8
d = decimal, base 10
b = binary, base 2
```
**Sample Output**
```
# numd.sh h 1ff
h=1FF o=777 d=511 b=111111111
# numd.sh h 1+f
h=10 o=20 d=16 b=10000
# numd.sh b '1+10* 100'
h=1FF o=777 d=511 b=111111111
```

## MAC address changer
Quick way of changing, only for the current session, the MAC address of the ethernet card (requires ``root`` privileges)

**Usage and Sample Output**
```
# mac_changer.sh
[sudo] password for user:
Old MAC address
eth0      Link encap:Ethernet  HWaddr XX:XX:XX:XX:XX:XX
New MAC address
eth0      Link encap:Ethernet  HWaddr YY:YY:YY:YY:YY:YY
```
