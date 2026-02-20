![[Pasted image 20260219163716.png]]
## ==require(path of the file)===> 
>this  is how i can import the codes of the other file into the one file . 

![[Pasted image 20260219164628.png]]

>see the variable inside one module is protected by default , event require keyword , can not import the functions inside the other module . 

>this ids the reason we are getting error. 

## how to solve this issue ?


![[Pasted image 20260219170025.png]]

> now its working , i just expoet the module and import the module in the index.js ( main file ), then i call the function that i 
> written .
> 
 
## module.exports = calcSum ;
this is the syntax of how to export the function 


## now what if i have to sent the multiple functions and variable ?
 > we will just wrap the things inside the object and export the whole object .
![[Pasted image 20260220135742.png]]


#### for export => module.export ()
### for import => require(file path)
### default used in node js 
### non strict mode 
### this is the synchronous way to export module and execution 
# THIS IS HOW MODULE WORKS ON (COMMON JS MODULES)
---


# NOW WE WILL SEE HOW THE THINGS  WORKS IN 
(ES MODULES)
### import 
### export 
### strict  mode 
### used in react angular and all ..... 

### this is the  async way  to execution and import and export .  
![[Pasted image 20260220142109.png]]

