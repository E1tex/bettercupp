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
    Better Common User Passwords Profiler

optional arguments:
  -h, --help            show this help message and exit
  -i, --interactive     Interactive questions for user password profiling
  -ni, --noninteractive
                        Non Interactive mode for user password profiling
  -fn FIRSTNAME, --firstname FIRSTNAME
                        Target First Name for -ni(Non Interactive) mode
  -ln LASTNAME, --lastname LASTNAME
                        Target Last Name for -ni(Non Interactive) mode
  -n NICKNAME, --nickname NICKNAME
                        Target Nickname for -ni(Non Interactive) mode
  -bd BIRTHDATE, --birthdate BIRTHDATE
                        Target Birthdate for -ni(Non Interactive) mode
  -pfn PARTNERS_FIRSTNAME, --partners_firstname PARTNERS_FIRSTNAME
                        Partners First Name for -ni(Non Interactive) mode
  -pn PARTNERS_NICKNAME, --partners_nickname PARTNERS_NICKNAME
                        Partners Nickname:
  -pbd PARTNERS_BIRTHDATE, --partners_birthdate PARTNERS_BIRTHDATE
                        Partners birthdate (DDMMYYYY):
  -cn CHILDS_NAME, --childs_name CHILDS_NAME
                        Child's name
  -cni CHILDS_NICKNAME, --childs_nickname CHILDS_NICKNAME
                        Child's nickname
  -cbd CHILDS_BIRTHDATE, --childs_birthdate CHILDS_BIRTHDATE
                        Child's birthdate (DDMMYYYY)
  -petn PETS_NAME, --pets_name PETS_NAME
                        Pet's name
  -cin COMPANY_NAME, --company_name COMPANY_NAME
                        Company name
  -kw KEYWORDS, --keywords KEYWORDS
                        Any key words
  -sc, --special_chars  Add special chars
  -rn, --add_random_numbers
                        Random numbers at the end of words
  -lm, --leet_mode      Leet mode
  -w FILENAME           Use this option to improve existing dictionary, or
                        WyD.pl output to make some pwnsauce
  -l                    Download huge wordlists from repository
  -a                    Parse default usernames and passwords directly from
                        Alecto DB. Project Alecto uses purified databases of
                        Phenoelit and CIRT which were merged and enhanced
  -v, --version         Show the version of this program.
  -q, --quiet           Quiet mode (don't print banner)
```


## Configuration

CUPP has configuration file cupp.cfg with instructions.
