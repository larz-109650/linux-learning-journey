## Install Git

I use Kali Linux. For install Git on Debian-based distributions:
```bash
apt-get install git
```
To check if Git was installed correctly and to see its version:
```bash
git --version
```
```output
git version 2.53.0
```

---

### Set up my identity

Set username and email address:
```bash
git config --global user.name "[name]"
git config --global usar.emal "[email]"
```
To view the configuration:
```bash
git config --list
```
---

### Create repositories

git init [project-name] -> Create a local repository with the assigned name  
git clone [url] -> Download a project and its version history  
