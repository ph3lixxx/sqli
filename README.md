# Install sqli

Bsqli requires **python3** to run successfully. Run the following command to install the latest version -

```sh
git clone https://github.com/bluediving/sqli.git
```

### Usage

```sh
python3 main.py -h
```

This will display help for the tool. Here are all the switches it supports.


```console
Bsqli is a fast Blind SQL LIKE CLAUSE Data Exfiltration Tool

Usage:
  python3 bsqli.py [flags]

Flags:
usage: main.py [-h] (-u URL | -l FILE) -p PAYLOADS [-t THREADS] [-o OUTPUT] [-hf] [-s]

Proof of Concept Blind SQL LIKE CLAUSE Data Exfiltration Tool

options:
  -h, --help            show this help message and exit
  -u URL, --url URL     Target URL
  -l FILE, --file FILE  URLs file
  -p PAYLOADS, --payloads PAYLOADS
                        Payloads file
  -t THREADS, --threads THREADS
                        Number of threads
  -o OUTPUT, --output OUTPUT
                        Output file for results
  -hf, --hide-fail, --hide-fails
                        Hide failed attempts
  -s, --no-ssl-verify   Disable SSL verification
```
