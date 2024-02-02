# palera1n-c-bypass
I have no idea anymore i think this is a tutorial (done on macOS 14.1)

# THIS ASSUMES YOU HAVE EVERYTHING INSTALLED!!
restore the iphone with itunes before doing any of this or it probably wont work

https://raw.githubusercontent.com/kitty915/palera1n-mod/main/other/mobileactivationd download this
https://ios.cfw.guide/installing-palera1n/#running-palera1n-1 except run `palera1n -c -f` (grab palera1n c beta 7 binary for your system)

once your now jailbroken iphone has booted, run iproxy 2222 44 in a seperate terminal then (assuming you're in the same folder as where you downloaded mobileactivationd) run `ssh -oHostKeyAlgorithms=+ssh-dss -p 2222 root@127.0.0.1 "cat > /usr/libexec/mobileactivationd" < ./mobileactivationd` then reboot (password for root should always be `alpine` until you change it in the palera1n app!!!)
and keep your phone connected to the pc during this

credits here https://github.com/kitty915/palera1n-mod#credits
