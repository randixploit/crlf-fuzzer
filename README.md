# CRLFuzzer
<a href="https://www.python.org/"><img src="https://img.shields.io/badge/python-3.x-blue.svg"></a>
<a href="https://opensource.org/license/MIT"><img src="https://img.shields.io/badge/license-MIT-green.svg"></a>

CRLFuzzer is a tool for scanning CRLF vulnerabilities using threadpool, so that the scanning process can run quickly and accurately. This tool is equipped with a built-in payload to check vulnerabilities on targeted websites, so you don't need to provide an additional payload.

# Disclaimer

This tool is intended **only for ethical purposes** such as bug bounty programs and vulnerability reporting on authorized platforms.  
Misuse of this tool is strictly prohibited and is the sole responsibility of the user.  
Use it only on systems you own or have explicit permission to test.

# Screenshots

<img src="https://raw.githubusercontent.com/randixploit/crlfuzzer/refs/heads/main/images/Screenshot_20250127-183928.jpg">

# Help

```
usage: crlfuzzer [-h] [-u <URL> | -l <FILE>]

options:
  -h, --help            show this help message and exit
  -u <URL>, --url <URL>
                        target
  -l <FILE>, --list <FILE>
                        file
```

# Installation

```
$ git clone https://github.com/randixploit/crlfuzzer
$ cd crlfuzzer
$ pip3 install -r requirements.txt
$ python3 setup.py install
```

# Usage

Single Scanning:
```
$ crlfuzzer -u http://example.com
```

Mass Scanning:
```
$ crlfuzzer -l file.txt
```

𝙸 𝚑𝚘𝚙𝚎 𝚖𝚢 𝚙𝚛𝚘𝚓𝚎𝚌𝚝 𝚌𝚊𝚗 𝚋𝚎 𝚞𝚜𝚎𝚏𝚞𝚕 𝚏𝚘𝚛
𝚎𝚟𝚎𝚛𝚢𝚘𝚗𝚎, 𝚝𝚑𝚊𝚗𝚔𝚜 𝚏𝚘𝚛 𝚞𝚜𝚒𝚗𝚐 𝚝𝚑𝚎 𝚝𝚘𝚘𝚕𝚜 𝙸 𝚖𝚊𝚍𝚎. 𝚃𝚑𝚒𝚜 𝚝𝚘𝚘𝚕𝚜 𝚒𝚗 𝚒𝚗𝚜𝚙𝚒𝚛𝚎𝚍 𝚋𝚢 <a ahref="https://github.com/dwisiswant0/crlfuzz">𝙲𝚁𝙻𝙵𝚞𝚣𝚣</a>.
