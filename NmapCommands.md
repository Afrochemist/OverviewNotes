List of Nmap commands


nmap <site>

*in verbose mode*
nmap -v scanme.org

*enumerating a single port*
nmap -p 80 scanme.org

*enumerating between port 1-30*
nmap -p1-30 scanme.nmap.org #scan specific ports(between port 1-30)

*enumerating versions on different ports*
nmap -sV scanme.org


*Enumerating UDP ports*
nmap -sU scanme.org

*Enumerating TCP ports*
nmap -sT scanme.org

*Half-open syn  scan*
nmap -sS scanme.org

*TCP null scan(need to explain what a null scan is )*
nmap -sN scanme.org

*TCP fin scan(need to explain what a fin scan is )*
nmap -sF scanme.org

*TCP Xmas scan(need to explain what a Xmas scan is )*
nmap -sX scanme.org
