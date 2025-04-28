# 🛡️ Roadmap de Cybersecurity para Iniciantes
**Foco em Redes, Linux e Python**

Este roadmap foi criado para orientar quem está começando na área de Cybersegurança, com um foco especial nos fundamentos essenciais de Redes, Linux e Python.

---

## 1. Fundamentos de Redes (Networking Básico)

**Objetivo**: Entender como funciona uma rede (TCP/IP, DNS, HTTP, Firewalls).

- 📚 Curso Grátis: [Computer Networking - Stanford](https://cs144.github.io/)
- 📚 Curso Básico: [Networking Fundamentals - TryHackMe](https://tryhackme.com/room/networkfundamentals)
- 📖 Material de Apoio: [RFC 2616 - HTTP 1.1 Specification](https://www.w3.org/Protocols/rfc2616/rfc2616.html)
- 🎯 Laboratório Prático: [Wireshark Labs - HTTP Analysis](https://wiki.wireshark.org/SampleCaptures)

**Tópicos para aprender:**
- Modelos OSI e TCP/IP
- Conceitos de DNS, DHCP, HTTP, SSL/TLS
- Funcionamento de roteadores, switches e firewalls
- Redes públicas e privadas
- Diferenças entre TCP e UDP (handshake, confiabilidade)

---

## 2. Linux Básico a Intermediário

**Objetivo**: Trabalhar confortavelmente no terminal Linux, entender permissões, processos e configurações de rede.

- 📚 Curso Grátis: [Linux Essentials for Cybersecurity - Cisco Networking Academy](https://skillsforall.com/course/linux-essentials-for-cybersecurity)
- 📚 Curso Prático: [Linux Fundamentals - TryHackMe](https://tryhackme.com/room/linuxfundamentals2)
- 📖 Cheatsheet de Comandos Linux: [OverTheWire Wargames + Comandos Linux](https://overthewire.org/wargames/bandit/)
- 🎯 Laboratórios: [OverTheWire: Bandit](https://overthewire.org/wargames/bandit/)

**Tópicos para aprender:**
- Comandos básicos (`cd`, `ls`, `cat`, `grep`, `find`, `awk`, `sed`)
- Permissões de arquivos e gerenciamento de usuários (`chmod`, `chown`, `sudo`, `/etc/passwd`)
- Gerenciamento de pacotes (apt, yum, dnf)
- Controle de processos (`ps`, `top`, `kill`)
- Comandos de rede (`netstat`, `ss`, `iptables`, `ufw`)
- Scripts básicos com Bash e agendamentos com `cron`

---

## 3. Python para Cybersecurity

**Objetivo**: Automatizar tarefas de rede, manipulação de arquivos e criação de ferramentas simples.

- 📚 Curso Grátis: [Python for Beginners - Microsoft (YouTube)](https://www.youtube.com/watch?v=rfscVS0vtbw)
- 📚 Curso de Python focado em Segurança: [Python for Pentesters - TryHackMe](https://tryhackme.com/room/pythonforpentesting)
- 📖 Cheatsheet Python: [Python Cheatsheet for Beginners](https://github.com/gto76/python-cheatsheet)

**Tópicos para aprender:**
- Variáveis, estruturas de decisão e repetição
- Funções e módulos
- Manipulação de arquivos
- Trabalhar com redes usando módulos como `socket`, `requests`, `scapy`
- Uso de expressões regulares (`re`)
- Noções básicas de orientação a objetos

**Projetos sugeridos:**
- Scanner de portas TCP
- Script de automação de login SSH (usando Paramiko)
- Analisador de logs
- Web scraper básico

---

## 4. Primeiros Projetos Práticos

**Objetivo**: Consolidar o conhecimento adquirido através de pequenos projetos.

**Projetos sugeridos:**
- Criar um scanner de portas TCP simples
- Criar um monitor de disponibilidade (ping automático)
- Automatizar backups de diretórios
- Criar um servidor TCP básico em Python
- Ler e extrair informações úteis de arquivos de log

---

## 5. Ambiente de Estudo e Ferramentas

**Objetivo**: Criar um ambiente seguro para aprendizado prático.

- 📚 Instalação de Máquina Virtual Linux:
  - [Guia para instalar Ubuntu usando VirtualBox](https://ubuntu.com/tutorials/how-to-run-ubuntu-desktop-on-a-virtual-machine-using-virtualbox#1-overview)
- 📚 Ferramentas essenciais:
  - Wireshark (analisador de pacotes)
  - Nmap (scanner de redes)
  - Burp Suite (analisador de tráfego web)
  - Netcat (ferramenta de rede)

---

# 📈 Evolução Sugerida

Após dominar os fundamentos:

- Avançar em laboratórios do [TryHackMe - Complete Beginner Path](https://tryhackme.com/path/outline/complete-beginner)
- Iniciar desafios no [HackTheBox - Starting Point](https://app.hackthebox.com/starting-point)
- Aprofundar em:
  - Segurança de Redes (firewalls, VPN, proxies)
  - Exploração básica de vulnerabilidades (web, SSH, FTP)

---

# 🌟 Dicas Importantes

- Mantenha suas anotações organizadas (Notion, Obsidian ou Markdown).
- Pratique diariamente, mesmo que por apenas 30 minutos.
- Priorize a prática: estude e aplique.
- Não pule os fundamentos de Redes e Linux: eles são a base de tudo.

---

**Bons estudos! 🚀**
