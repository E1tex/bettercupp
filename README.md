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

usage: bettercupp.py [-h] [-i] [-ni] [-fn FIRSTNAME] [-ln LASTNAME]
                     [-n NICKNAME] [-bd BIRTHDATE] [-pfn PARTNERS_FIRSTNAME]
                     [-pn PARTNERS_NICKNAME] [-pbd PARTNERS_BIRTHDATE]
                     [-cn CHILDS_NAME] [-cni CHILDS_NICKNAME]
                     [-cbd CHILDS_BIRTHDATE] [-petn PETS_NAME]
                     [-cin COMPANY_NAME] [-kw KEYWORDS] [-sc] [-rn] [-lm]
                     [-pf PROFILE_FILE] [-ofn OUTPUT_FILE] [-w FILENAME] [-l]
                     [-a] [-v] [-q]

Better Common User Passwords Profiler

optional arguments:
```
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
  -pf PROFILE_FILE, --profile_file PROFILE_FILE
                        Profile File Example: bettercupp.py -ni -fn 0 -ln 2
                        -bd 1 -pf test.txt File Content Example:
                        Ivan:12122012:Pupkin
  -ofn OUTPUT_FILE, --output_file OUTPUT_FILE
                        Specify value that will be used in output file name
                        Example: bettercupp.py -ni -fn 0 -ln 2 -bd 1 -pf
                        test.txt -ofn nickname
  -w FILENAME           Use this option to improve existing dictionary, or
                        WyD.pl output to make some pwnsauce
  -l                    Download huge wordlists from repository
  -a                    Parse default usernames and passwords directly from
                        Alecto DB. Project Alecto uses purified databases of
                        Phenoelit and CIRT which were merged and enhanced
  -v, --version         Show the version of this program.
  -q, --quiet           Quiet mode (don't print banner)
  ```

## Non-Interactive Mode Example
Command:
```
python3 ./bettercupp.py -ni -ofn pet_name -pf profiletest.txt -n 0 -fn 1 -ln 2
```
profiletest.txt:
```
nick1:Ivan:Spiridonov
nick2:Vasya:Pupkin
...
nickname:Name:Surname
```

## Configuration

CUPP has configuration file cupp.cfg with instructions.
