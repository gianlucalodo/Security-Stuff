# WAF
check: wafw00f www.test.com

nmap --script=http-waf-fingerprint www.test.com -p 80
