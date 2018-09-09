# CVE_Assessment_04_2018

The Prezi Next is a software used to create presentations. However, it brings also vulnerabilities such as: (i) the ability to invocate tools capable to modify the registry and (ii) mechanisms of persistence through an extensive use of functions in the kernel32.dll. Additional red flags were also identified as associated with those vulnerabilities.

Antivirus tools did not detect suspicious contents in the software and in one instance a suspicious file was detected. The software has a compressed file inside another compressed file, in which it shows data after the end of the payload data that prevented to unpack the software.

The software has an extensive internet traffic through subdomains of prezi.com and the Amazon CloudFront.net which could increase the security risks related to remote access and process injection.
