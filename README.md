# DesignOOP-Jenkins
Jenkins deployment configurations for DesignOOP project

## Env Files

```
// jenkins/jenkins.env

SYSTEM_MESSAGE=Jenkins configured automatically by JCasC
ADMIN_USERNAME=admin
ADMIN_PASSWORD=admin
JENKINS_EMAIL_ADDRESS=email
JENKINS_URL=jenkins.website.com
```

```
// jenkins/ssh-keys.env

JENKINS_AGENT_SSH_PUBKEY=ssh-rsa ...
AGENT_SSH_PASSPHRASE=...
VPS_SSH_PASSPHRASE=...
SSH_HOST=...
```

```
// jenkins/secrets/agent_ssh_key.txt
// jenkins/secrets/vps_ssh_key

-----BEGIN OPENSSH PRIVATE KEY-----
...
-----END OPENSSH PRIVATE KEY-----
```