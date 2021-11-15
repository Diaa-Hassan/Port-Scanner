### Port Scanner
This is a simple port scanner made using bash scripting.

> To  Run This Script simply give it permissions to be executed

``` chmod u+x PortScanner.sh ```
or
``` chmod 777 PortScanner.sh ```

after that you can simply run the script by typing
` ./PortScanner.sh `
this will run the script with some default parameters for testing 
>These parameters are:

```
########################################

   Target is -----------> google.com
   Begining Port -------> 1
   Ending Port ---------> 1000

########################################
```
>You Can Specify Your Own Target And Ports To Be Scanned As Follows

`./PortScanner.sh TARGET BEGINING_PORT ENDING_PORT`
for example:
`./PortScanner.sh kernel.org 440 445`
and the output should be something like this 

![Test.PNG](/_resources/Test.PNG)


