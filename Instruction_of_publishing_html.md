#Instruction of publishing html file on USC aludra server
###Open terminal, and type following command:
```{r, engine='bash', count_lines}
$ ssh <your USC web ID>@aludra.usc.edu
$ mkdir public_html
$ chmod 755 public_html
$ cd public_html
$ cat > index.html
<your html file>
e.g. 
<html>
   <head>
       <title>HTML Page Template</title>
   </head>
   <body>
       <!-- Add HTML elements here -->
   </body>
</html>

$ chmod 755 index.html 
```


