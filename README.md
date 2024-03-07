# Microsoft-TP-Link-Research-Team
Microsoft researcher discovered LPE vulnerability in TP-Link Omada ER605 V1.0.1 through (v2.6) 2.2.3, 


## Vulnerability description
In TP-Link Omada er605 1.0.1 through (v2.6) 2.2.3, a cloud-brd binary is susceptible to an integer overflow that leads to a heap-based 
buffer overflow. After heap shaping, an attacker can achieve code 
execution in the context of the cloud-brd binary that runs at the root 
level. This is fixed in ER605v2_un_2.2.3_20240102-rel63857_up_2024-01-03. 

## Vulnerability Type
Buffer Overflow 

## Affected Product version
TP-Link Omada er605 1.0.1 through (v2.6) 2.2.3 

## CVE-ID
CVE-2024-25139

## Patch for the vulnerability
[ER605(UN)_v2_2.2.4 Build 020240119.zip](https://static.tp-link.com/upload/firmware/2024/202401/20240124/ER605(UN)_v2_2.2.4%20Build%2020240119.zip)

## Affected Component
cloud-brd binary. 

## Reference
[TP-Link Omada](https://www.tp-link.com/us/omada-sdn/)

## Researchers
Vladimir Tokarev, Omri Ben-Bassat 
