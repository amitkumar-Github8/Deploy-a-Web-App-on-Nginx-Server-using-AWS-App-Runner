# Create a Container Image
* create a new folder called **nginx-web-app**, and navigate to the folder.
``` 
    mkdir nginx-web-app
    cd nginx-web-app 
```
* Select the **+New file** icon, and enter index.html for the file name.
![](image)

* Select the *index.html* file, and **update** it with the following code. Then, **save** the file.
  * [HTML code](index.html)

* Create another file named *Dockerfile*, and **update** it with the following code.
* Then **save** the file.
  * [Docker code](dockerfile)

* Open terminal window, **run** the following command to create conatiner image.
  ```
  Bash
  
  docker build -t nginx-web-app .
  ```
