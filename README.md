# Subdomain Finder Tool
## Overview

The Subdomain Finder Tool is a powerful utility designed to identify subdomains associated with a given domain. It utilizes various techniques and online resources to discover subdomains, providing valuable information for security assessments, penetration testing, and general domain reconnaissance.
Features

    Subdomain discovery: The tool scans the specified domain and uncovers associated subdomains.
    DNS resolution: It resolves the IP addresses of the discovered subdomains.
    Custom wordlists: The tool supports the use of custom wordlists to enhance the subdomain enumeration process.
    Recursive subdomain scanning: The tool recursively scans discovered subdomains to identify additional levels of subdomains.
    Output flexibility: It offers multiple output formats, such as plain text, CSV, or JSON, for easy integration with other tools and workflows.
    Multithreading: The tool leverages multithreading to optimize the subdomain scanning process and increase efficiency.
    Robustness: It handles various DNS-related scenarios, such as rate limiting and timeouts, to ensure reliable results.

### Requirements:

To use the Subdomain Finder Tool, the following requirements must be met:

    Python installed on the system.
    Internet connectivity to access online resources and perform DNS lookups.

## Installation

    Clone the repository or download the source code of the Subdomain Finder Tool.

    chmod +x SubdomainFinder
    

## Usage
     python SubdomainFinder.


    domain: The target domain to scan for subdomains.

Example:

python subdomain_finder.py example.com 

This command will scan the "example.com" domain using the "custom_wordlist.txt" file as the wordlist and save the results in the "results.txt" file.
Output


Wordlist Recommendations

To maximize the effectiveness of subdomain scanning, consider using comprehensive wordlists containing common subdomain names, keywords, and popular services. Numerous curated wordlists are available online, such as "SecLists" and "FuzzDB," which can be used to enhance the subdomain enumeration process.




## Sample Output:
![](https://github.com/karthickop6/Subdomain-Finder/blob/main/Screenshot%202023-07-05%20173115.png)







                                                                                                  THANKS FOR USING   :)
