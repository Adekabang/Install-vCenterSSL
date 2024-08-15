# Install-vCenterSSL

## Installs Free SSL on vCenter
[Tutorial Link](https://web.archive.org/web/20240121212111/https://virtuallywired.io/2023/11/02/automate-free-lets-encrypt-ssl-certificate-replacement-for-vsphere-8/)

### Execution
0. Change Variable in the code
  ```ps1
  $vCenterURL = "vc.example.com"
  $CommonName = "vc.example.com"
  $EmailContact = "admin@example.com"
  ```
1. Run with Powershell
2. Type vCenter username and password
3. Wait some operational like install module
4. Set DNS for txt challenge
5. Press any key
6. Wait and Finish 
