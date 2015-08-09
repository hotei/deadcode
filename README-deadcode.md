<center>
# deadcode
</center>

## OVERVIEW

A fork of deadcode.go by Remy Oudompheng.  It's still useful even though there
are a few broken bits now that go has evolved to 1.4.2 (at time of writing).
See the godoc portion below for a list of changes I made to code.

### Installation

If you have a working go installation on a Unix-like OS:

> ```go get github.com/hotei/deadcode```

That will copy github.com/hotei/deadcode to the first entry of your $GOPATH

or if go is not installed yet :

> ```cd DestinationDirectory```

> ```git clone https://github.com/hotei/deadcode.git```

### Features
* simple
* works as intended
* friendly to markdown (new feature)
* works well in Makefile  (new feature)

### Limitations

* deadcode will ignore build tags that might be present in the programs being checked
	* [ed. Hotei] in time I hope to correct this but it's not urgent

### Usage

```
cd to the directory of the program you wish to check and run it

$ cd progDir
$ deadcode

or

$ deadcode someDirectory
```

### BUGS
* none known

### Change Log
* 2015-08-09 compiled with 1.5rc1
* 2015-06-12 compiled with 1.4
* 2014-xx-xx Started

 
### Resources

* [go language reference] [1] 
* [go standard library package docs] [2]
* [Source for deadcode] [3]

[1]: http://golang.org/ref/spec/ "go reference spec"
[2]: http://golang.org/pkg/ "go package docs"
[3]: http://github.com/hotei/deadcode "github.com/hotei/deadcode"

Comments can be sent to <hotei1352@gmail.com> or to user "hotei" at github.com.
License is BSD-two-clause, in file "LICENSE"

### License

The original source I found was copyrighted with BSD-3 license 

Documentation (c) 2014-2015 David Rook 
