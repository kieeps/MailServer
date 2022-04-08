# MailServer
My attempt to create a secure mailserver suite with modern components.


## **Concept:**

- *Build with NixOS*
- *Use Docker for each component*

## **Components:**

- *[Cyrus](https://www.cyrusimap.org/) IMAP Server*
- *[Cypth](https://cypht.org/) Webmail client*
- *[Postfix](https://www.postfix.org/)* (maby replace with Proxmox Mail Gateway and move aslias to LDAP?)
- *Decide AUTH*
- *Decide SMTP*
