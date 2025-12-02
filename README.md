# **ip2domain**

Automated: IP → PTR → HTTP reconnaissance.

```
 _      ______     _                   _       
(_)    (_____ \   | |                 (_)      
 _ ____  ____) )_ | | ___  ____   ____ _ ____  
| |  _ \/_____// || |/ _ \|    \ / _  | |  _ \ 
| | | | |_____( (_| | |_| | | | ( ( | | | | | |
|_| ||_(_______)____|\___/|_|_|_|\_||_|_|_| |_|
  |_|                                          
```

## **Description**

Feed a list of IPs → resolve PTR records → probe HTTP/HTTPS → identify live hosts.
Fast, silent, and ideal for pentesters, bug bounty hunters, and reconnaissance workflows.

---

## **Requirements**

* `dnsx` (PTR lookup)
* `httpx` (HTTP probing)
* Bash (Linux/macOS)

---

## **Usage**

```bash
./ip2domain <ips.txt>
./ip2domain -h
```

---

## **Output**

```
ip2domain-result/
 ├── ptr-output.txt   # Resolved domains
 └── http-output.txt  # Live HTTP/HTTPS hosts
```

---

## **Highlights**

* End-to-end automation for IP → domain → live HTTP discovery
* Minimal, fast, script-friendly, silent operation
* Ideal for large-scale infrastructure recon

---


Do you want me to do that version too?
