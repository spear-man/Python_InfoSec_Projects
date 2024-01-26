# DNSExploration

## Description
This script pulls DNS information of a website, providing details such as the domain associated with a website and its IP addresses. It's a simple tool for exploring the DNS records of a given domain.

## Usage

1. Open a terminal.
2. Run the script using the following command:
    ```bash
    python3 DNSExploration.py
    ```
3. Enter the domain name when prompted (e.g., `google.com`).

## Example
```bash
$ python3 DNSExploration.py
Enter the domain name: .google.com

Ouput:

www.google.com: ['lga15....net'] 172.217.X.X
blog.google.com: ['ord.....net'] 172.217.X.X

