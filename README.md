# AzureSubdomainHunter
A tool for finding vulnerable subdomains by subdomain takeover attack via misconfiguration of CNAME record
# Workflow of tool
1. Find subdomain with subfinder tool --> 2. Find subdomain appeared in CNAME records --> 3. Verify PoC
# Requirements
Install Azure CLI for Linux,
Install following modules for python: dnspython, colorama, win_unicode_console
# Usage
Enter target domains in list.txt file,
Run: ./AzureSubdomainHunter.sh for automatic attack

# Ref 
https://github.com/melbadry9/cname,
https://github.com/projectdiscovery/subfinder
