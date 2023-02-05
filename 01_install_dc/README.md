# 01 Installing the Domain Controller

1. Use 'sconfig to:
    - Change the Hostname
    - Change the IP address tp static
    - Change the DNS server to our own IP address

2. Install the Active Directory Winodows Feature

Install-WindowsFeature AD- Domain-Service -IncludeManagmentTools
