#Instruction for publishing web applications on aludra.usc.edu

In the following username refers to your USC ID, i.e., username@usc.edu.

To test you can connect with ssh and create an index.html. Use a terminal on a unix system or [Putty](http://www.putty.org) on Windows.

```{r, engine='bash', count_lines}
$ ssh username@aludra.usc.edu 
$ mkdir public_html  # automatically mapped by Apache to http://www-scf.usc.edu/~username
$ cd public_html
$ cat > index.html  # paste what follows into index.html; after paste command type Ctrl+D
<html>
   <head>
       <title>HTML Page Template</title>
   </head>
   <body>
       Hello!
   </body>
</html>
$ chmod -R 755 public_html  # make readable by www user for Apache to access 
```

You should be able to see the page by going to: http://www-scf.usc.edu/~username

To publish your website it is best to connect with a secure FTP client such as [Filezilla](https://filezilla-project.org) then drag and drop the files in public_html or a subfolder.

Here are references:
* http://www.putty.org
* https://itservices.usc.edu/scf/
* https://www.youtube.com/watch?v=yfDDw4v0bzY
* https://filezilla-project.org
