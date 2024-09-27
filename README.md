# gpo_disable_windows_ssl_tls
Disable Windows SSL and TLS using GPO

This is an XML formatted file that you can just copy the XML text and paste into the registry settings editor to create a policy. Settings created from https://learn.microsoft.com/en-us/windows-server/identity/ad-fs/operations/manage-ssl-protocols-in-ad-fs

Additional file for disabling some legacy ciphers also per instructions from https://learn.microsoft.com/en-us/troubleshoot/windows-server/active-directory/disable-and-replace-tls-1dot0

Also added additional ciphers to remove per https://learn.microsoft.com/en-us/troubleshoot/windows-server/certificates-and-public-key-infrastructure-pki/restrict-cryptographic-algorithms-protocols-schannel
