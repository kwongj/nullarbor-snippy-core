# nullarbor-snippy-core
Runs snippy-core on a subset of isolates included in a Nullarbor run

##Author

Jason Kwong (@kwongjc)

##Usage

```
$ nullarbor-snippy-core -h
Name:
  nullarbor-snippy-core
Author:
  Jason Kwong <j.kwong1@student.unimelb.edu.au>
Usage:
  nullarbor-snippy-core [options] <isolate1> <isolate2> ... <isolateN>
Parameters:
  <isolateN>    Isolates to be analysed - must have Nullarbor folder with same name
Options:
  -h	        Show this help
  -n <dir>      Specify directory containing nullarbor output (default = current directory)
  -o <prefix>   Specify prefix for output (default = core)
  -r		    Include reference (default = no ref)
```

##Bugs

Please submit via the [GitHub issues page](https://github.com/kwongj/nullarbor-snippy-core/issues).  

##Software Licence

[GPLv3](https://github.com/kwongj/nullarbor-snippy-core/blob/master/LICENCE)

##Links
* [Nullarbor](https://github.com/tseemann/nullarbor)
* [Snippy](https://github.com/tseemann/snippy)
