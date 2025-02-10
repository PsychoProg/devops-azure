## Private key
deploy your private key in azure dashboard -> pipelines -> library

from azure pipe line ready tasks, choose **Download Secure File**, insert name of your private key file
in secure file, 

only file owner can have access to this private key
```bash
chmod 400 $(sshKey.secureFilePath)
```

