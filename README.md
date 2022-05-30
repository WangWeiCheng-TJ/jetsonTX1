# jetsonTX1
deploy pretrained model on jetson tx1

## Change default download folder (cause the tx 1 itself has limited storage space)
change the cache to usb
### set up the backup apt/conf.d file
1. cd to etc/apt/apt.conf.d 
2. sudo touch 99_xxx <--name with 99 so it overrides others
3. sudo apt-get install nano
4. sudo nano 99_xxx
5. add the following line into the file: Dir::Cache::Archives "/path/you/want/"; <--/path/you/want/ in my case is /media/REDSTICK/tmp
6. save the file
###
