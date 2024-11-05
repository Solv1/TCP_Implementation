Starter code for CS4254/5565 Project 3.

This contains two separate environments -- one Docker based intended for both x86 and M1 OSX host systems, the other Virtualbox based for x86 Windows systems. If you're a Linux user, either one will work -- we'd recommend using the VM. To launch your environment, `cd` into the appropriate subdirectory to launch your environment according to the directions in each folder's README.md.
  

***BEFORE CLONING***: git config --global core.autocrlf input  

vagrant up  
vagrant ssh   
cd cs4254  
infra/testall  
infra/nettest  
exit  
vagrant suspend  
  
***STARTER CODE STATS***  
testall: passes all basic tests except the last one (large 0.1 Mb/s 500 ms latency)  
nettest: default time = 600ms, medium size time = 820ms  

***PRIMARY TODO***: dropped, corrupt, check integrity(checksum?), delayed, duplicated, out of order  
***SECONDARY TODO***: fast(use more bandwidth?), efficient
