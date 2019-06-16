# Entropy Exploit (CNVD-2017-02776)

        _______   ____________  ____  ______  __
       / ____/ | / /_  __/ __ \/ __ \/ __ \ \/ /
      / __/ /  |/ / / / / /_/ / / / / /_/ /\  / 
     / /___/ /|  / / / / _, _/ /_/ / ____/ / / 
    /_____/_/ |_/ /_/ /_/ |_|\____/_/     /_/ 

<p align="center">
  <a href="http://entynetproject.simplesite.com/">
    <img src="https://img.shields.io/badge/entynetproject-Ivan%20Nikolsky-blue.svg">
  </a>
  <a href="https://github.com/entynetproject/entropy/releases">
    <img src="https://img.shields.io/github/release/entynetproject/entropy.svg">
  </a>
  <a href="https://ru.m.wikipedia.org/wiki/Python">
    <img src="https://img.shields.io/badge/language-python-blue.svg">
 </a>
  <a href="https://exploit-db.com/">
      <img src="https://img.shields.io/badge/exploit-CNVD-red.svg?maxAge=2592000">
 </a>
  <a href="https://github.com/entynetproject/entropy/issues?q=is%3Aissue+is%3Aclosed">
      <img src="https://img.shields.io/github/issues/entynetproject/entropy.svg">
  </a>
  <a href="https://github.com/entynetproject/entropy/wiki">
      <img src="https://img.shields.io/badge/wiki%20-entropy-lightgrey.svg">
 </a>
  <a href="https://mobile.twitter.com/entynetproject">
    <img src="https://img.shields.io/badge/twitter-entynetproject-blue.svg">
 </a>
</p>

# Entropy credits

    Name    : Entropy Exploit
    Writer  : Entynetproject
    Version : 1.0 (first release)
    Exploit : CNVD-2017-02776
    Github  : https://github.com/entynetproject
    Site    : http://entynetproject.simplesite.com/

# About entropy exploit

    INFO: Entropy Exploit is an IP webcamera 
    exploit also named CNVD-2017-02776, this is 
    powerful exploitation tool for webcams testing!

# How to install entropy

    INFO: Entropy Exploit will be installed into /bin and 
    /usr/local/bin as /bin/entropy and /usr/local/bin/entropy!

> cd entropy

> chmod +x install.sh

> ./install.sh

# How to uninstall entropy

> cd entropy

> chmod +x uninstall.sh

> ./uninstall.sh

# How to execute entropy (command)

> entropy -h

# How to execute entropy (python3)

> cd entropy

> python3 entropy.py -h

# Entropy global usage

    usage: entropy [-h] [-b {1,2}] [-o OUTPUTFILE] [-T TIMEOUT] [-t TASKS]
                   [-c COUNT] [-q | -v]
                   [-i IP | -l INPUTFILE | --shodan SHODAN | --zoomeye ZOOMEYE]

    Please use CNVD-2017-02776 exploit just in educational purposes!

    optional arguments:
      -h, --help            show this help message and exit
      -b {1,2}, --brand {1,2}
                            Choose the brand of IP Camera. 1 - represents Netwave,
                            2 - represents GoAhead.
      -o OUTPUTFILE, --output OUTPUTFILE
                            Output into path you input. The default path in dir
                            /tmp
      -T TIMEOUT, --timeout TIMEOUT
                            The default timeout for netwave is 300s.
      -t TASKS, --task TASKS
                            Run TASKS number of connects in parallel, default is
                            10.
      -c COUNT, --count COUNT
                            The number of IP you want to get from ZoomEye. The
                            maximum is 2000. Default is 100.
      -q, --quiet           Quiet mode.
      -v, --verbose         Show more informations.
      -i IP, --ip IP        The camera's IP and port. Example: 192.168.1.100:80
      -l INPUTFILE, --list INPUTFILE
                            The camera's IP:port address file. The file's format
                            like this 192.168.1.100:80 in a line.
      --shodan SHODAN       Your Shodan API Key. You can get help from
                            https://www.shodan.io/
      --zoomeye ZOOMEYE     Your ZoomEye API Key. You can get help from
                            https://www.zoomeye.org/api

# Entropy exploit examples

> If you want to exploit a local camera, run
    
    entropy -b 1 -i 192.168.1.100:80 -v  
    
> If you want to exploit cameras from list, run

    entropy -b 2 -l iplist.txt -v
    
> If you want to exploit cameras from database, run

    entropy -b 2 -v --shodan [API key]

# Terms of use

    This tool is only for educational purposes only.
    Use this tool wisely and never without permission.
    I am not responsible for anything you do with this tool.

# Entropy MIT license

    MIT License

    Copyright (C) 2019, Entynetproject. All Rights Reserved.

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.

# Thats all!
