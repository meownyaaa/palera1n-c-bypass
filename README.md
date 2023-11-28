# palera1n-c-bypass
I have no idea anymore i think this is a tutorial

THIS ASSUMES YOU HAVE EVERYTHING INSTALLED!!

restore the iphone with itunes before doing any of this or it probably wont work

https://raw.githubusercontent.com/kitty915/palera1n-mod/main/other/mobileactivationd download allat fr
https://ios.cfw.guide/installing-palera1n/#running-palera1n-1 except run `palera1n -c -f` (or just `palera1n -c` i forgor :alien: (install palera1n c beta 7)) 

once your now jailbroken iphone has booted, run iproxy 2222 22 in a seperate terminal then (assuming you're in the same folder as where you downloaded mobileactivationd) run

`ssh -oHostKeyAlgorithms=+ssh-dss -p 2222 root@127.0.0.1 "cat > /usr/libexec/mobileactivationd" < ./mobileactivationd`
then reboot
password for root should always be `alpine`!!!
and keep yo damn phone connected to the pc during all of this

credits here https://github.com/kitty915/palera1n-mod#credits
