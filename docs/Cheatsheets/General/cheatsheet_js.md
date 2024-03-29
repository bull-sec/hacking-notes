# Commands

| **Command**   | **Description**   |
| --------------|-------------------|
| `curl http:/SERVER_IP:PORT/` | cURL GET request |
| `curl -s http:/SERVER_IP:PORT/ -X POST` | cURL POST request |
| `curl -s http:/SERVER_IP:PORT/ -X POST -d "param1=sample"` | cURL POST request with data |
| `alias curlx="curl -x http://127.0.0.1:8080 "` | proxy a cURL request through Burp |
| `echo bullsec \| base64` | base64 encode |
| `echo ENCODED_B64 \| base64 -d` | base64 decode |
| `echo bullsec \| xxd -p` | hex encode |
| `echo ENCODED_HEX \| xxd -p -r` | hex decode |
| `echo bullsec \| tr 'A-Za-z' 'N-ZA-Mn-za-m'` | rot13 encode |
| `echo ENCODED_ROT13 \| tr 'A-Za-z' 'N-ZA-Mn-za-m'` | rot13 decode |

# Deobfuscation Websites

| **Website** |
| ----------------------------------|
| [JS Console](https://jsconsole.com) |
| [Prettier](https://prettier.io/playground/) |
| [Beautifier](https://beautifier.io/) |
| [JSNice](http://www.jsnice.org/) |

# Misc

| **Command**   | **Description**   |
| --------------|-------------------|
| `ctrl+u` | Show HTML source code in Firefox |