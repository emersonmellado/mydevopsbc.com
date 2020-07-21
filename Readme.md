# Project for students to get how to register a domain and use EB to manage the app pipeline

1. Register a domain in godaddy
    - mydevopsbc.com
2. Use Route 53 to configure the DNS
    - NS entries:
        ns-183.awsdns-22.com. 
        ns-1088.awsdns-08.org. 
        ns-1970.awsdns-54.co.uk. 
        ns-744.awsdns-29.net.
    - Run DNS Checker
    - Created an apex entry
    - Created an www entry
3. Use Elastic Beanstalk as the Pipeline management
    - Open the tutorial
    - Created the local app
    - Tested it locally
    - eb init
        - eb init -p python-3.6 mydevopsbc --region us-west-2
    - Installed EB cli
        - pip install awsebcli --upgrade
    - Deploy OK
4. Use git as the version control system
 - https://github.com/emersonmellado/mydevopsbc.com


 # Domains

For the web "Domain" we are talking about a website name.

apex domain (root domain): mydevopsbc.com

- www.mydevopsbc.com
- www = subdomain
- mydevopsbc.com = root

- app.mydevopsbc.com
- app = subdomain



# DNS - Domain Name System

You can think of DNS as a phone book.

Where your name or the phone holder name is the domain name (i.e: mydevopsbc.com)

And the phone number as the IP address:
i.e: 
- Domain Name Server: 52.32.147.154
- Domain Name Server: 35.163.176.199

- To figure out what is your domain NS (Name Server), you can navigate to whatismydns.com

- In case of a DNS change:

Before:
mydevopsbc.com - 52.32.147.154

After:
mydevopsbc.com - 44.44.44.44


codesenses.com -> ns1.site4now.net > 


# CDN - Content Delivery Network











