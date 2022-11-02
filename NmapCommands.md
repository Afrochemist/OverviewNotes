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


*Ping sweep*
nmap -sn 192.168.0.1-254
or 
nmap -sn 192.168.1.0/24

*Maimon Scan(need to add an explanation)*
nmap -sM scanme.org

*ACK scan*
nmap -sA scanme.org

*Window Scan(need to add an explanation)*
nmap -sW scanme.org

*Fast scan(scans the most common ports)*
nmap -F scanme.org

*Verbose*
nmap -v scanme.org

*Nmap Basic Port Scans - States*

Open - A service is listening

Closed - no service listening

Filtered - cannot be determined usually due to a firewall

Unfiltered - port is accessible but cannot be determined if its open or closed

Open | Filtered - nmap cannot determine if port is open or not 

Closed | Filtered - cannot decide if port is open or closed
