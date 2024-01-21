# Build Zimbra on centos
Build full zimbra 8.8.15 on CentOS 7
- Zimbra version: 8.8.15 GA
- OS: Linux
- Config:
  - Verify: SPF, DMARC, DKIM
  - SSL
  - Config add new disk Data for Email Server
## I. Setup Zimbra onf CentOS
Model Setup:
Ext-> (IP Publib) pfsense -> (Nat Forware IP Local) vps
#### On Pfsense need Nat open port:
Port need to open: `25,80,110,143,443,465,587,993,995,5222,5223,9071,7071`
## II. Config SPF, DMARC, DKIM

## III. Config SSL

## IIII. Config new volume Data for Zimbra Server

## V. Recheck and complete.



