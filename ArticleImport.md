

# Importing data into R #

Since there are many tutorial written to import and export data, we will refer to pages that do a good job in describing that process (below).

However we have some tips for users:

  * 1. Know your working directory

> Your working directory is the first place R looks for reading and writing files, so your life will be a lot easier if you know where this directory is. Working directory can be looked up with R via the command:
```
   getwd()
```

> To reassign your working directory, put your directory path in quotes (single or double):
```
    setwd("C:/temp")
```

> or in Linux and Mac
```
   setwd("~/temp")
```

> Once you know your work directory, you can supply a filename of the files residing in the working directory without specifying the exact path, e.g.
```
   read.csv("mydata.csv")
```

> instead of
```
   read.csv("C:/temp/mydata.csv")
```

  * 2. Use a single forward slash for directory path (think Linux/ Mac) or use double backslash in Windows:
```
   setwd("C:\\temp")
```

  * 3. Make sure you use the correctly capitalized file names. This process is easily accomplished with "auto-complete as you type" feature via the "Tab" button across different platforms.  Or in Windows, drag-and-drop the file into the R main session window, and the full path of that file will be exposed.

# R tutorials on import and export #

  1. [UCLA R Import Tutorial](http://www.ats.ucla.edu/stat/r/modules/raw_data.htm)
  1. [UCLA R Subsetting Data](http://www.ats.ucla.edu/stat/R/modules/subsetting.htm)
  1. [Quick-R On Importing Data](http://www.statmethods.net/input/importingdata.html)
  1. [Quick-R On Exporting Data](http://www.statmethods.net/input/exportingdata.html)