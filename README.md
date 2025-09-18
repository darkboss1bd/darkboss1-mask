# darkboss1-mask
All in one Information gathering tool - OSINT

(![image](https://i.ibb.co.com/yzwJJr4/hk.png)


## darkboss1-mask

All in one Information gathering tool - OSINT

*For a full list of our tools, please visit our website https://www.serialkey.top/*
### Dependencies

* Python 3.x
* validators
* python-whois
* dnspython
* requests
* shodan
* censys
* mmap
* pprint


### Information Gathering

* ask
* bing
* crt
* censys.io
* dns
* dnsdumpster
* dogpile
* github
* google
* googleplus
* instagram
* linkedin
* netcraft
* shodan
* And More
---

### Dependencies

```
sudo pip3 install -r requirements.txt
```

---

### Usage

```
git clone https://github.com/darkboss1bd/darkboss1-mask.git
cd darkboss1-mask
python darkboss1-mask.py -d example.com -i basic

```

---

### Modes

* Basic Mode
  * Whois lookup
  * DNS queries
  * Reverse DNS Lookup
  * Bing Virtual Hosts

* Nongoogle Mode
  * Whois lookup
  * DNS queries
  * Reverse DNS Lookup
  * Bing Virtual Hosts
  * Search in Bing
  * Search in Yahoo
  * Search in ASK
  * Search in Dogpile
  * Search in Yandex
  * Search in Crt
  * Search in DNSdumpster
  * Search in Netcraft
  * Search in VirusTotal
  * Search in Spyse

---

### Usage Examples

```
python darkboss1-mask.py -d example.com -i basic

python darkboss1-mask.py -d example.com -i dnsdump

python darkboss1-mask.py -d example.com -i shodan -k xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

python darkboss1-mask.py -d example.com -i whois,dns,revdns

python darkboss1-mask.py -d example.com -i basic,yahoo,github -o myresults/example_com_search_results
```

### censys.io usage examples

```
python darkboss1-mask.py -i censys --Limit 10 nessus

python darkboss1-mask.py -i censys -I SAP --report location.country.raw --report_bucket 10

python darkboss1-mask.py -i censys --html-title "Hacked By" --Limit 10 --html

python darkboss1-mask.py -i censys --tags heartbleed --report location.country.raw

python darkboss1-mask.py -i censys -S NGINX --count

python darkboss1-mask.py -i censys -d example.com

python darkboss1-mask.py -i censys -t "Internal Server Error" -S Apache -m "HTTP 500" --Limit 15
```

### Read the API Keys usage example - e.g in censys.io

```
python darkboss1-mask.py -i censys -r

```

### Update the API Keys usage example - e.g in censys.io

```
python darkboss1-mask.py -i censys -u

```

---

### Credits

* [Hacker ](https://github.com/maldevel/darkboss1bd
* [Telegram id](https://t.me/darkvaiadmin)
* [Website](https://serialkey)

---
