Hello All ,   This is Project Based Educational Tool only Developed for Educational Purpose.



With all things like Domain Enumeration , port Scanning whether its  WHOIS Lookup or its Banner Grabbing; Using a different Tool for Each time is quite irritating.

For the solution We introduce you to :

                    █████╗ ████████╗ ██████╗ ███╗   ███╗██╗ ██████╗     ███████╗  ██████╗  █████╗ ███╗   ██╗
                   ██╔══██╗╚══██╔══╝██╔═══██╗████╗ ████║██║██╔════╝     ██╔════╝ ██╔════╝ ██╔══██╗████╗  ██║
                   ███████║   ██║   ██║   ██║██╔████╔██║██║██║          ███████║ ██║      ███████║██╔██╗ ██║
                   ██╔══██║   ██║   ██║   ██║██║╚██╔╝██║██║██║   ██║    ╔══╝  ██ ██║   ██║██╔══██║██║╚██╗██║
                   ██║  ██║   ██║   ╚██████╔╝██║ ╚═╝ ██║██║╚██████╔╝    ███████╗╚ ██████╔╝██║  ██║██║ ╚████║
                   ╚═╝  ╚═╝   ╚═╝    ╚═════╝ ╚═╝     ╚═╝╚═╝ ╚═════╝      ╚══════╝ ╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═══╝
               
                                              ⚡ Fast • Modular • Recon Toolkit ⚡
    Which can perfomr:
    => WHOIS LOOKUP
    => DNS ENUMERATION
    => SUBDOMAIN ENUMERATION USING CRT.SH 
    => SIMPLE PORT SCANNING
    => BANNER GRABBING
    => WAPPALYZER LOOKUP
    => Sub Directory Enumeration
                                                                                                                   
                                                                                                                   
  Dependencis:
    
    pip install python-Wappalyzer
  
  Usage details:

       python3   atomic.py   <domain name>    <flags>

flags Details:

      Usage details: <example.com> flag1  flag2   ......... 

      Flags:  
      --whois     Perform basic WHOIS search
      --dnsenum   for DNS Enumeration
      --crtenum   for Subdomain Enumeration Using CRT.SH API
      --direnum   for Subdirectories Enumeration 
      --portscan  for Scanning Ports
      --V         for Banner Grabbing
      --W         for Wapplayzer search using Wappalyzer API
      --all       for all of the above
Example Usage:

      python3 example.com   --whois --dnsenum --V
