# domain settings configuration
please edit the domain file you want to go to

notes :
- [github.json](https://github.com/dee-al/domain.dee.al/blob/main/domain/dee.al/github.json) - DNS configuration for github static web
- [blogger.json](https://github.com/dee-al/domain.dee.al/blob/main/domain/dee.al/blogger.json) - DNS configuration for blogger.com
- [a.json](https://github.com/dee-al/domain.dee.al/blob/main/domain/dee.al/a.json) - redirect site to server e.g. vps etc
- [ns.json](https://github.com/dee-al/domain.dee.al/blob/main/domain/dee.al/ns.json) - redirect situs ke hosting dll dengan nama domain yang Anda inginkan


# Configuration
[github](#github)
[blogger](#blogger)
[a](#a)
[ns](#ns)

# github
This configuration is specifically for github, the domain will automatically be created according to the list below
    
**HOW TO USE**

please add a comma, after }
then fill it with the following command

~~~javascript
{
"koneksi": "CNAME",
"hostku": "yourdomain", // fill in the domain name you want
"target": "mr614ck.github.io" // your github web link
}
~~~

# blogger
This configuration is specifically for Blogger, the domain will automatically be created according to the list below

**HOW TO USE**

please add a comma, after }
first login to blogger.com then go to **settings** then select **custom domain**
then fill it with the following command
~~~javascript
{
"koneksi": "CNAME", 
"hostku": "www", // fill in the domain name you want
"target": "ghs.google.com" // fill according to google settings
},
{
"koneksi": "CNAME",
"hostku": "nm4khu54qqpe", // fill according to google settings
"target": "gv-36ozyecqkto6ku.dv.googlehosted.com" // fill according to google settings
}
~~~

each time you want to add a domain please separate it with a comma,
but if not please remove the comma,

# a
the domain will be directed according to the ip you are going to, for example to your vps or others

**HOW TO USE**

please add a comma, after }
then fill it with the following command
~~~javascript
{
"koneksi": "A",
"hostku": "blog", // fill in the domain name you want
"target": "47.250.39.97" // fill with destination target IP
}
~~~

each time you want to add a domain please separate it with a comma,
but if not please remove the comma,

# ns
redirect the domain to a private nameserver OR other service

**HOW TO USE**

please add a comma, after }
then fill it with the following command

~~~javascript

{
"koneksi": "NS",
"hostku": "blog", // fill in the domain name you want
"target": "ns1.firdausiregar.my.id" // fill with destination target NS
},
{
"koneksi": "NS",
"hostku": "blog", // fill in the domain name you want
"target": "ns1.firdausiregar.my.id" // fill with destination target NS
}
~~~~

each time you want to add a domain please separate it with a comma,
but if not please remove the comma,

