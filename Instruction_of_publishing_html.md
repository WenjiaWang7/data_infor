#Instruction of publishing html file on USC aludra server

###Open terminal, and type following command:
```{r, engine='bash', count_lines}
$ ssh <your USC web ID>@aludra.usc.edu       e.g. ssh wenjiawa@aludra.usc.edu
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

###Then, open browser. The website will then be visible at http://www-scf.usc.edu/~username. e.g. http://www-scf.usc.edu/~wenjiawa

####This Instruction is based on OSX environment.
####Here are references:
(https://itservices.usc.edu/scf/)
(aludra.usc.edu)
(https://www.youtube.com/watch?v=yfDDw4v0bzY)
(https://filezilla-project.org)
