```
C:\Users\raelu\lecture1
``` 
![Image](cd_no_arg.png)  
>The directory is moved back by 1 directory, so the working directory went from ```C:\Users\raelu\lecture1``` to ```C:\Users\raelu```.
  ***
  
```
C:\Users\raelu
``` 
![Image](cd_directory.png)  
>The directory moved into the specified directory, so this time the working directory went from ```C:\Users\raelu``` to ```C:\Users\raelu\lecture1```.
  ***
  
```
C:\Users\raelu\lecture1\messages
```
![Image](cd_file.png)  
>There was an error because ```cd``` moves directories, but ```Hello.java``` is not a directory, it is a file.
  ***
  
```
C:\Users\raelu\lecture1
``` 
![Image](ls_no_arg.png)  
>A list of the current directory is printed with whatever is in it.
  ***
  
```
C:\Users\raelu\lecture1
``` 
![Image](ls_directory.png)  
>A list of whatever is inside the specificed directory is printed.
  ***
  
```
C:\Users\raelu\lecture1
```  
![Image](ls_file.png)  
>The name of the specified file is repeated.  
  ***  
  
```
C:\Users\raelu\lecture1
```  
![Image](cat_no_arg.png)  
>Anything written after ```cat``` on its own is repeated. To quit the command, CTRL+D.
  ***
  
```
C:\Users\raelu\lecture1
```  
![Image](cat_directory.png)   
>A statement is printed, letting the user know that the directory specified is a directory.
  ***
  
```
C:\Users\raelu\lecture1
```  
![Image](cat_file.png)  
>Anything inside the specified file is printed.
