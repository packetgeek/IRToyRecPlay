# IRToyRecPlay

Utility for recording and playing IR codes with Dangerous Prototype's USB IR Toy

This is just a fork from https://github.com/myshen/IRToyRecPlay.  No major changes.  Here for my own use/entertainment.

To record: ./IRToy -d /dev/ttyACM0 -f fanpw -r
To send: ./IRToy -d /dev/ttyACM0 -f fanpw -p

where:
    -d + argument declares the device to use
    -f + argument declares file to record into/play from
    -r records into the file declared by -f
    -p plays from the file declared by -f
