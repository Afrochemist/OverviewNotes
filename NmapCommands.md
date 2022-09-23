List of Nmap commands


nmap <site>

nmap -v scanme.org

*enumerating between port 1-30*
nmap -p1-30 scanme.nmap.org #scan specific ports(between port 1-30)

*enumerating versions on different ports*
nmap -sV scanme.org


*Enumerating UDP ports*
nmap -sU scanme.org

*Enumerating TCP ports*
nmap -sT scanme.org

