# proxy-tester

A simple script to test your proxy(-ies)

![proxy-tester output preview](https://raw.githubusercontent.com/virtualdemon/proxy-tester/master/screenshot/screenshot.png)

![RepoSize](https://img.shields.io/github/repo-size/virtualdemon/proxy-tester.svg?style=flat-square) ![Contributors](https://img.shields.io/github/contributors/virtualdemon/proxy-tester.svg?style=flat-square)

# HOW TO USE

1. download the script with `curl` or `wget` : 
    
    `curl https://raw.githubusercontent.com/virtualdemon/proxy-tester/master/proxy-tester -o ~/proxy-tester`
    
    `wget curl https://raw.githubusercontent.com/virtualdemon/proxy-tester/master/proxy-tester -O ~/proxy-tester`

2. modify execute permission for proxy-tester : 
    
    `chmod +x ~/proxy-tester`
    
3. use it! :
    
    `~/proxy-tester -f YourLinksFile [-s socks5ProxyAddress] [-h httpProxyAddress] -u ProxyUserName -p PorxyUserPassword`
    
# MORE

* For usage help just run it : 
    
    `~/proxy-tester`

    or even :

    `~/proxy-tester --help`

* If you want the output that you can see when you're running the script just :
    
    `cat proxy-tester.log`

* Your LinksFile should be like this : 

> https://github.com

> https://www.google.com

> https://stackoverflow.com

> https://www.kernel.org

,...

* The screenshot? Just clone this repository!

    `git clone https://github.com/virtualdemon/proxy-tester`
    
    `cd proxy-tester`
    
    `./proxy-tester -f links -s localhost:9050`

I just used tor as my socks5 proxy server.
