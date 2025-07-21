## pencil / pencil sharpener (adapted for badrecovery unverified)
1.  Do [sh1ttyOOBE](./README.md) and complete the persistence method
2.  Do the rest of pencil / pencil sharpener, until you reach the part where it asks for sh1mmer, then follow these steps again
3.  Make a 124 or older [badrecovery](https://github.com/BinBashBanana/badrecovery) unverified image
4.  Recover to it in developer mode
5.  run the commands below:  
```bash
flashrom --wp-disable
futility gbb -s --flash --flags=0x8090
flashrom --wp-enable
reboot -f
```
6.  Reboot, dev mode will now boot successfully
### Confused on if your device needs pencil or pencil sharpener? 
View the table on [code_execution.md](./code_execution.md) \
Please view the [web builder](https://binbashbanana.github.io/badrecovery/builder.html), it may be easier as there are no prebuilts.
