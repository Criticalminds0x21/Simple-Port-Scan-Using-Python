# Simple-Python-Port-Scanner


Python TCP port scanner Scan single hosts or a /24 network for open ports  


Scan host Usage: python3 portscanner.py [IP address] [start port] [end port]


Example: python3 portscanner.py 192.168.1.10 1 65535  


Scan network Usage: python3 portscanner.py [network] [start port] [end port] -n 


Example: python3 portscanner.py 192.168.1 1 65535 -n
