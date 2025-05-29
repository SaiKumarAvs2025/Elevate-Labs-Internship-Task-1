Network Scanning Summary:

I conducted a network scan on my localhost using the Nmap tool to identify active services and potential vulnerabilities. The scan results revealed three open TCP ports:

Port 135/tcp – Used by Microsoft RPC (Remote Procedure Call), commonly seen in Windows environments.

Port 139/tcp – NetBIOS Session Service, typically associated with Windows file/printer sharing and SMB protocol.

Port 445/tcp – Microsoft-DS (Directory Services), used for SMB over TCP/IP for file and printer sharing.

The presence of these open ports indicates that Windows-based services are active and potentially accessible, which could pose security risks if not properly secured. This activity enhanced my hands-on experience with network enumeration, port scanning, and interpreting service behavior, which are critical skills for cybersecurity and SOC analysis.
