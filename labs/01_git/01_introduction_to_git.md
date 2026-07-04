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

### Configure tools

git config --global user.name "[name]" -> set the name associated with the commits  
git config --global usar.emal "[email]" -> set the email associated with the commits   

---

### Create repositories

git init [project-name] -> Create a local repository with the assigned name  
git clone [url] -> Download a project and its version history  
