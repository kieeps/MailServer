# MailServer
My attempt to create a secure mailserver suite with modern components.


## **Concept:**

- *Build with NixOS*
- *Use Docker for each component*

## **Components:**

- *[Cyrus](https://www.cyrusimap.org/) IMAP Server*
- *[Cypth](https://cypht.org/) Webmail client*
- *[Postfix](https://www.postfix.org/)* (maby replace with [Proxmox Mail Gateway](https://www.proxmox.com/en/proxmox-mail-gateway) and move alias to [LDAP](http://www.linux-admins.net/2010/09/routing-and-alias-management-with.html)?)
- *Decide AUTH* (leaning towards Cyrus SASL/LDAP)
- *Decide SMTP*
