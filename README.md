<h1 align="center">E aí! Eu sou o Elvis 👋</h1>

<p align="center">
  <b>IT Infrastructure Manager</b> · redes, segurança e a mania de automatizar tudo que dá
</p>

<p align="center">
  <i>Se eu precisei fazer duas vezes na mão, na terceira já virou script.</i>
</p>

<p align="center">
  <a href="https://linkedin.com/in/elvisfalmeida"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://ebyte.net.br"><img src="https://img.shields.io/badge/Site-0d9488?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Site"/></a>
  <a href="mailto:elvis@ebyte.net.br"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

## 🎬 O que eu ando aprontando

### 🛡️ [JellyDirectGuard](https://github.com/elvisfalmeida/JellyDirectGuard) &nbsp;<sub>· recém-saído do forno</sub>

<a href="https://github.com/elvisfalmeida/JellyDirectGuard/releases/latest"><img src="https://img.shields.io/github/v/release/elvisfalmeida/JellyDirectGuard?style=flat-square&label=release&color=8b5cf6&labelColor=0d1117" alt="Release"/></a>
<img src="https://img.shields.io/badge/Jellyfin-10.11%2B-8b5cf6?style=flat-square&logo=jellyfin&logoColor=white&labelColor=0d1117" alt="Jellyfin 10.11+"/>
<img src="https://img.shields.io/github/license/elvisfalmeida/JellyDirectGuard?style=flat-square&color=64748b&labelColor=0d1117" alt="Licença"/>

Plugin pro **Jellyfin** que força **direct play**: transcodificação de vídeo, aqui não. Nasceu da minha VPS sem GPU, onde dois transcodes já sentavam a CPU — com direct play, streaming vira só I/O de rede e a mesma máquina atende uma multidão.

O pulo do gato: a política é clampada **no segundo em que o usuário é criado** — inclusive contas geradas pelo Wizarr, que adora reescrever a própria política logo depois (tem uma segunda passada esperando por ele). E se alguém liberar transcode na mão, a varredura periódica desfaz sozinha. Tabela de status por usuário e botão "Aplicar agora" direto no Dashboard.

<sub>`C#` · `Jellyfin 10.11+` · `GPL-3.0` · instalável direto pelo catálogo de plugins</sub>

<br/>

### 🔔 [JellyWahaNotify](https://github.com/elvisfalmeida/JellyWahaNotify) &nbsp;<sub>· o meu xodó</sub>

<a href="https://github.com/elvisfalmeida/JellyWahaNotify/releases/latest"><img src="https://img.shields.io/github/v/release/elvisfalmeida/JellyWahaNotify?style=flat-square&label=release&color=8b5cf6&labelColor=0d1117" alt="Release"/></a>
<img src="https://img.shields.io/badge/Jellyfin-10.11%2B-8b5cf6?style=flat-square&logo=jellyfin&logoColor=white&labelColor=0d1117" alt="Jellyfin 10.11+"/>
<img src="https://img.shields.io/github/license/elvisfalmeida/JellyWahaNotify?style=flat-square&color=64748b&labelColor=0d1117" alt="Licença"/>

Plugin pro **Jellyfin** que te avisa no WhatsApp quando entra coisa nova na biblioteca. Filme, episódio ou álbum — chega com pôster e legenda bonitinha.

O pulo do gato: episódios vêm **agrupados por série**, então quando você joga uma temporada inteira lá dentro você recebe *uma* mensagem, não vinte e quatro. Ainda dá um toque pros admins sobre login novo, tentativa de login que falhou e quem começou a assistir o quê.

<sub>`C#` · `Jellyfin 10.11+` · `WAHA` · `GPL-3.0` · instalável direto pelo catálogo de plugins</sub>

<br/>

### 🛠️ Omega Tools &nbsp;<sub>· [canal de releases](https://github.com/elvisfalmeida/Omega-Tools-Updates)</sub>

<a href="https://github.com/elvisfalmeida/Omega-Tools-Updates/releases/latest"><img src="https://img.shields.io/github/v/release/elvisfalmeida/Omega-Tools-Updates?style=flat-square&label=release&color=f59e0b&labelColor=0d1117" alt="Release"/></a>
<img src="https://img.shields.io/badge/Python-Tkinter-f59e0b?style=flat-square&logo=python&logoColor=white&labelColor=0d1117" alt="Python/Tkinter"/>
<img src="https://img.shields.io/badge/Windows-desktop-f59e0b?style=flat-square&logo=windows&logoColor=white&labelColor=0d1117" alt="Windows"/>

Desktop app em **Python/Tkinter** que virou o canivete suíço do iGlobal por aqui: menu de acesso rápido aos módulos e auto-update embutido.

A parte que mais me orgulha é o reparo de Java — ele valida a instalação e aplica o patch no `java.security` **sem precisar travar ou atualizar a versão do Java**, que era exatamente a dor que fazia o chamado voltar toda semana.

<sub>`Python` · `Tkinter` · `PyInstaller` · `winget` · auto-update por `version.json`</sub>

<br/>

### 🔐 Omega Password Portal &nbsp;<sub>· projeto interno</sub>

Portal web pra galera do home office trocar a senha do AD sozinha, sem abrir chamado.

O detalhe que faz diferença: funciona **mesmo com a senha já expirada** — justamente o momento em que o usuário não consegue fazer mais nada e o help desk vira gargalo. Sincroniza com o Azure AD por Delta Sync e me manda um WhatsApp a cada troca.

<sub>`Python` · `Flask` · `Active Directory` · `Azure AD` · `PowerShell` · rate limiting e proteção contra brute force</sub>

---

## ⚡ Com o que eu trabalho

<p>
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white" alt="PowerShell"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white" alt="Bash"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/VMware-607078?style=flat-square&logo=vmware&logoColor=white" alt="VMware"/>
  <img src="https://img.shields.io/badge/Windows_Server-0078D6?style=flat-square&logo=windows&logoColor=white" alt="Windows Server"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux"/>
</p>
<p>
  <img src="https://img.shields.io/badge/Active_Directory-0078D4?style=flat-square&logo=microsoft&logoColor=white" alt="Active Directory"/>
  <img src="https://img.shields.io/badge/Azure-0089D0?style=flat-square&logo=microsoft-azure&logoColor=white" alt="Azure"/>
  <img src="https://img.shields.io/badge/Microsoft_365-D83B01?style=flat-square&logo=microsoft-office&logoColor=white" alt="Microsoft 365"/>
  <img src="https://img.shields.io/badge/pfSense-212121?style=flat-square&logo=pfsense&logoColor=white" alt="pfSense"/>
  <img src="https://img.shields.io/badge/FortiGate-EE3124?style=flat-square&logo=fortinet&logoColor=white" alt="FortiGate"/>
  <img src="https://img.shields.io/badge/Zabbix-CC0000?style=flat-square&logo=zabbix&logoColor=white" alt="Zabbix"/>
  <img src="https://img.shields.io/badge/Veeam-00B336?style=flat-square&logo=veeam&logoColor=white" alt="Veeam"/>
</p>

---

## 💬 Bora trocar ideia

Curto conversar sobre infra, automação, homelab e sobre aquele problema chato que ninguém consegue resolver. Chama aí:

📧 [elvis@ebyte.net.br](mailto:elvis@ebyte.net.br) &nbsp;·&nbsp; 💼 [LinkedIn](https://linkedin.com/in/elvisfalmeida) &nbsp;·&nbsp; 🌐 [ebyte.net.br](https://ebyte.net.br)

<br/>

<div align="center">
  <sub>☕ movido a café e a <code>Ctrl+S</code></sub>
  <br/><br/>
  <img src="https://komarev.com/ghpvc/?username=elvisfalmeida&color=0d9488&style=flat-square&label=Visualizações+do+perfil" alt="Views"/>
</div>
