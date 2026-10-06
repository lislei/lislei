## Hi there 👋, I'm Leif Lislegard
![Software Engineer](https://img.shields.io/badge/Software%20Engineer-blue) 
![Full Stack Developer](https://img.shields.io/badge/Full%20Stack%20Developer-blue)
![Security Champion](https://img.shields.io/badge/Security%20Champion-red)
![Hits](https://hits.sh/github.com/lislei/hits.svg?label=Hits&extraCount=100)

## 🚀 About Me
- 🎓 Computer Engineering graduate with a passion for **secure coding** and **software delivery pipeline**
- 🔭 Currently working on: **The Norwegian Cadastre (Matrikkelen)**
- 🌱 Learning: **GCP/Kubernetes, GitHub, and advanced system design**
- 💼 Open to opportunities in **full stack / backend engineering / data science**


## 🛠️ Tech Stack

**Languages**  
![Java](https://img.shields.io/badge/-Java-007396?logo=java&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-blue?style=flat&logo=oracle&logoColor=black)
![PL/SQL](https://img.shields.io/badge/PL--SQL-orange?style=flat&logo=oracle&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-blue?style=flat&logo=postgresql&logoColor=black)
![Groovy](https://img.shields.io/badge/Groovy-E69F0D?style=flat&logo=apachegroovy)
![Kotlin](https://img.shields.io/badge/Kotlin-black?style=flat&logo=kotlin)
![Shell Script](https://img.shields.io/badge/-Shell_Script-4EAA25?logo=gnu-bash&logoColor=black)
![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=green)
![Markdown](https://img.shields.io/badge/Markdown-%230077B5?style=flat&logo=markdown&logoColor=black)

**Frameworks**  
![Jakarta EE](https://img.shields.io/badge/-Jakarta%20EE-232F3E?logo=eclipse&logoColor=black)
![Hibernate](https://img.shields.io/badge/-Hibernate-59666C?logo=hibernate&logoColor=black)  
![Spring](https://img.shields.io/badge/-Spring-6DB33F?logo=spring&logoColor=black)

**Cloud & DevOps**  
![Google Cloud](https://img.shields.io/badge/-Google%20Cloud-4285F4?logo=google-cloud&logoColor=black)
![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=black)  
![Jenkins](https://img.shields.io/badge/-Jenkins-D24939?logo=jenkins&logoColor=black)
![ArgoCD](https://img.shields.io/badge/-ArgoCD-FE4B00?logo=argo&logoColor=black)


**API**
![SoapUI](https://img.shields.io/badge/SoapUI-black?logo=soapui&logoColor=black)
![OWASP ZAP](https://img.shields.io/badge/OWASP%20ZAP-black?logo=owasp&logoColor=black)

<!--
**lislei/lislei** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

💻 Current tools:
  - Ubuntu noble - 24.04
  - `sudo apt update & apt upgrade`
  - `sudo apt install openjdk-17-jdk -y`
  - `sudo apt install openjdk-25-jdk -y`
  - `sudo apt install git -y`
  - `sudo apt-get install git-lfs && git lfs install`
  - IntelliJ IDEA Ultimate (App center)
  - JetBrains Toolbox App ~ https://jetbrains.kartverket.dev
  - [SOAP UI](https://www.soapui.org/getting-started/installing-soapui/installing-on-linux-or-unix/)
  - DBeaver CE (App center ~ Apache License 2.0)
  - Slack (App center ~ Proprietary)
  - Teams-for-linux (App center ~ GPL-3.0)
  - [Docker Engine](https://docs.docker.com/engine/install/ubuntu/) (APT ~ Apache License 2.0)
  - Others:
    - `sudo apt-get install -y ffmpeg` (to watch videos in browser)
      
💾 Git config
```
FULLNAME="Leif Lislegard"
sudo apt-get install git -y
git config --global user.name "$FULLNAME"
git config --global user.email "$USERNAME@kartverket.no"
echo "git config:" && git config --list
```
💾 Git signed commits
```
gpg --quick-generate-key "$(git config user.name) <$(git config user.email)>" RSA default never
echo "☝️Copy name of generated key; i.e 3AA5C3437156XXXX" 

git config --global user.signingkey 3AA5C3437156XXXX
git config --global commit.gpgsign true   # always sign (automatically)

gpg --armor --export "$(git config user.name)"

echo "☝️Add above signature to GitHub profile etc."
```

