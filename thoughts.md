# big thoughts once over
initialized starts as false

ierc20 oz token. probably pooltoken

initialize function uses a password, that can be found in goerli contract 0xA45aC53E355161f33fB00d3c9485C77be3c808ae

deposit function uses a modifier that reequires initialization

transferfrom share is checking code size, but this can be bypassed with calling from constructor. this function is a little fishy

withdrawall function uses onlyinitializing modifier


## Objective of CTF
Your objective is to have a greater token balance than your initial balance.

### steps
i think 
1. hack password
2. get more shares