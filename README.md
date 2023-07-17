# iptohost
ip2host takes a list of IP addresses via file or stdin, then does a series of checks to return associated domain names only and can save as well.

** Its modified from Hakluke's tools <a href=https://github.com/hakluke/hakip2host> hakip2host </a>

# How to run 
cat target_ips.txt | go run iptohost.go -o target.txt
