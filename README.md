# CrawlBox | <img src="https://img.shields.io/badge/Crawl-Box-red.svg">
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub forks](https://img.shields.io/github/forks/abaykan/CrawlBox.svg)](https://github.com/abaykan/CrawlBox/network)
[![GitHub stars](https://img.shields.io/github/stars/abaykan/CrawlBox.svg)](https://github.com/abaykan/CrawlBox/stargazers)
[![HitCount](http://hits.dwyl.io/abaykan/crawlbox.svg)](http://hits.dwyl.io/abaykan/crawlbox)
[![GitHub license](https://img.shields.io/github/license/abaykan/CrawlBox.svg)](https://github.com/abaykan/CrawlBox/blob/master/LICENSE)
[![TypeScript](https://badges.frapsoft.com/typescript/love/typescript.png?v=101)](https://github.com/ellerbrock/typescript-badges/)
<br>
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![bitHound](https://img.shields.io/bithound/code/github/rexxars/sse-channel.svg)](https://github.com/abaykan/CrawlBox/)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/Django.svg?style=plastic)](https://github.com/abaykan/CrawlBox/)
[![Build Status](https://semaphoreci.com/api/v1/abaykan/crawlbox-2/branches/add-license-1/shields_badge.svg)](https://semaphoreci.com/abaykan/crawlbox-2)

Easy way to brute-force web directory.<br>

<a href="https://asciinema.org/a/keUhurPa1dzABWvVxBwhBu4Yp"><img src="https://asciinema.org/a/keUhurPa1dzABWvVxBwhBu4Yp.png" width="836"/></a>

<br>

# Operating Systems Tested
- MacOSX
- Kali Linux
- Ubuntu 16.04

# Usage
<pre>python crawlbox.py [-h] [-v] [-w WORDLIST] url</pre>
positional arguments:

  <pre>url            specific target url, like domain.com</pre>
optional arguments:

<pre>  -h, --help     show this help message and exit
  -v, --version  show program's version number and exit
  -w WORDLIST    specific path to wordlist file
  -d DELAY       add delay between requests</pre>

# Example
web site scan with internal wordlist

<pre>python crawlbox.py www.domain.com</pre>
web site scan with external wordlist

<pre>python crawlbox.py www.domain.com -w wordlist.txt</pre>

# Install
(as root)
  <pre>
  git clone https://github.com/abaykan/crawlbox.git
  cd crawlbox/
  pip install -r requirements.txt
  python crawlbox.py -h</pre>
  
note: tested with python 2.7.6

# Media Review
- Seucurity Training Share : <a href="https://securityonline.info/crawlbox-brute-force-web-directory/">https://securityonline.info/crawlbox-brute-force-web-directory/</a>
- PentestTools : <a href="https://pentesttoolz.com/2018/03/02/crawlbox-easy-way-to-brute-force-web-directory/">https://pentesttoolz.com/2018/03/02/crawlbox-easy-way-to-brute-force-web-directory/</a>
- Hacking Reviews : <a href="https://www.hacking.reviews/2018/03/crawlbox-easy-way-to-brute-force-web.html">https://www.hacking.reviews/2018/03/crawlbox-easy-way-to-brute-force-web.html</a>
- KitPloit : <a href="https://www.kitploit.com/2018/03/crawlbox-easy-way-to-brute-force-web.html">https://www.kitploit.com/2018/03/crawlbox-easy-way-to-brute-force-web.html</a>
