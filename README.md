# Host-Header-Injection-Detector
_(I developed this code this morning after pray Subuh)_.

This super simple tool is used to check whether the URL (main or subdomain) is vuln to inject with **X-Forwarded-Host**. In this code, i wrote `X-Forwarded-Host: google.com`, feel free to modify it.

Wishes be useful for all.

# How to download
```
git clone https://github.com/santiko/Host-Header-Injection-Detector.git
cd Host-Header-Injection-Detector
chmod +x hhi
mv hhi /usr/local/bin
```
# Note
Make sure `figlet` is available in storage. If it's not available, download it `apt install figlet`
# How to use
`hhi --d domain` (main domain or subdomain in file)

# Example
```
hhi --d subdomain.txt
```
