#"cd" Change directory:  

1:![image](1lab1.png)  <br> Absolute Path: `C:/Users/theso/lecture1/messages`  <br> having nothing in the arugment would take us back to the home directory, in this case it is `theso`.  <br> `NOT` an error  <br>
2: ![image](2lab1.png)  <br> `Absolute Path: C:/Users/theso`  <br> There exists the directory named `messages` with the `lecture1` folder, therefore it directs there.  <br> `NOT` an error  <br>
3: ![image](3lab1.png)  <br> Absolute Path: `C:/Users/theso/lecture1/messages`  <br> a text file cannot be used as a directory for `cd`. 
  <br>  `error` because it doesn't move us to the specified file directory<br>

#"ls" list:  

1: ![image](4lab1.png)  <br> Absolute Path: `C:/Users/theso/lecture1 ` <br> `ls` lists everything in the `lecture1` folder(containing `Hello.class`, `Hello.java`...) and it does so sucessfully <br> `NOT` an error  <br>
2: ![image](5lab1.png)  <br> Absolute Path: `C:/Users/theso/lecture1`  <br> `ls` with provided path to `messages` folder, lists everything in the text folder(containing `en-us.txt`, `es-mx.txt`...) and does so exhaustively <br> `NOT` an error  <br>
3: ![image](6lab1.png)  <br> Absolute Path: `C:/Users/theso/lecture1` <br> `ls` provided a specific path lists everything at this specific file, in this case it is `en-us.txt`, because it is provided a specific file, `ls` lists the specific file <br> `NOT` an error  <br>


#"cat" :  

1: ![image](7lab1.png)  <br> Absolute Path: `C:/Users/theso/lecture1`  <br> `cat` with 0 arguments just returns any string you input <br> `not` exactly an error, `cat` will just run in an loop where it will return any standard input. <br>
2: ![image](8lab1.png)  <br> Absolute Path: `C:/Users/theso/lecture1`  <br>  a directory file cannot be read as a text file. <br> `error` because a directory file itself cannot be read. <br>
3: ![image](9lab1.png)  <br> Absolute Path: `C:/Users/theso/lecture1`  <br> `cat` sucessfuly reads the textfile and prints the string within the textfile `NOT` an error  <br>
