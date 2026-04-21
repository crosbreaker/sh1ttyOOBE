## sh1ttyOOBE (formerly oobescape2)
**Unenrollment until next powerwash on 135-137**
# Support
If you need any kind of support, please join our [discord server](https://discord.gg/nrMVY29MUb) for help
1. Powerwash your Chromebook
2. On the "welcome to your Chromebook" screen, wait until you see the quick setup with Android button (DO NOT PRESS GET STARTED IF IT DOESN'T SHOW IMMEDIATELY), once it appears, press the button
3. Hit `CTRL`+`ALT`+`SHIFT`+`R` and click "cancel"
4. Click "Enter your Google account email and password." It should say to connect to a network
5. Open quick settings from the bottom right and connect to a network

## Persistence method
After signing in, you can sign out, and you will be back on the welcome screen. Progress through Oobe as normal by clicking get started, and next, you will be greeted with three options to sign in. Sign in with the same email, and when you sign in, it will hang on the please wait screen. Simply restart or Alt+VolumeUp + X, and you will be placed on the lockscreen. After that, you are done and can sign out/reboot, and it will be persistent until the  next powerwash.
# Using this to obtain a root shell 
After you have done the persistence method, you can recover to modified recovery images in unverified recovery, because VPD is not blocking developer mode.  This can be used to obtain a root shell even on keyrolled devices via [badrecovery unverified](https://github.com/BinBashBanana/badrecovery#:~:text=unverified,-version), and can be used to remove fwmp when used with [badbr0ker](https://github.com/crosbreaker/badbr0ker)

# Credits
 - [Lxrd/SPIRAME](https://github.com/SPIRAME): Finding the vulnerability
 - [HarryTarryJarry](http://github.com/HarryTarryJarry): reading logs to figure out sh1ttyOOBE disables enforced rootfs verification in developer mode recovery while enrolled, allowing [badrecovery unverified](https://github.com/BinBashBanana/badrecovery) to work. (leading to [badbr0ker](https://github.com/crosbreaker/badbr0ker))
 - [xz8f](https://github.com/xz8f): testing, persistence method
 - [all other members of crosbreaker](https://github.com/crosbreaker): uhh idk
