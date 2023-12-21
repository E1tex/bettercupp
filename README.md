# bettercupp

Better Version of Mebus/CUPP(https://github.com/Mebus/cupp). 

The ability to run the tool without interactive mode has been added, allowing large amounts of user input.

## Requirements

You need Python 3 to run betterCUPP.

## Quick start

```
$ python3 bettercupp.py -h
```


## Options

Usage: bettercupp.py [OPTIONS]

```
    -h      this menu

    -i      Interactive questions for user password profiling

    -ni     nonInteractive user password profiling

    -w      Use this option to profile existing dictionary,
            or WyD.pl output to make some pwnsauce :)

    -l      Download huge wordlists from repository

    -a      Parse default usernames and passwords directly from Alecto DB.
            Project Alecto uses purified databases of Phenoelit and CIRT which where merged and enhanced.

    -v      Version of the program
```


## Configuration

CUPP has configuration file cupp.cfg with instructions.
