## sh1ttyOOBE (formerly oobescape2)
**Unenrollment until next powerwash on 135-137**

1. Powerwash your Chromebook
2. On the "welcome to your Chromebook" screen wait until you see the quick set up with android button (DO NOT PRESS GET STARTED IF IT DOESN'T SHOW IMMEDIATELY), then press the button (this should be inferred, apparntly some people are to stupid for this :sob:)
3. Hit `CTRL`+`ALT`+`SHIFT`+`R` and click "cancel"
4. Click "Enter your google account email and password" it should say to connect to a network
5. Open quick settings from the bottom right and connect to a network

## Persistence method
After signing in you can sign out and you will be back on the welcome screen, progress through oobe as normal by clicking get started and next, you will be greeted with three options to sign in. Sign in with the same email and when you sign in it will hang on the please wait screen, simply restart or alt+volup+x and you will be placed on the lockscreen. After that you are done and can sign out/reboot and it will be persistent until next powerwash.
# Using this to obtain a root shell 
After you have done the persistence method, you can recover to modified recovery images in unverified recovery, because vpd is not blocking developer mode.  This can be used to obtain a root shell even on keyrolled devices via [badrecovery unverified](https://github.com/BinBashBanana/badrecovery#:~:text=unverified,-version), and can be used to remove fwmp when used with [badbr0ker](https://github.com/crosbreaker/badbr0ker)

# credits
 - Lxrd: Finding the vulnerability
 - HarryJarry1: finding the vpd vulnerability
 - crossjbly: testing, persistence method
 - all other members of crosbreaker: uhh idk think of something
