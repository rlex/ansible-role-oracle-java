##### Ansible role for installing oracle java

Installs and sets oracle java as default JDK/JRE in system.  
By default it will install oracle java 8 and set it as default.  
Depending on version it will pick either linuxuprising (jre 10 and up) or webupd8 (jre 8) PPAs for installation.  
This works for any debian-based linux distribution.

##### Parameters

You can choose oracle java version (8, 10 and 11 are supported, however 10 is already EOL) and if you want to set it as default:

```
oracle_java_version: 8
oracle_java_set_default: true
```
