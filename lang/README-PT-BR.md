<h1 align="center">
  <br>
  <a href="https://github.com/ranjanbug/reconweb"><img src="https://github.com/ranjanbug/reconweb/blob/main/images/banner.png" alt="reconweb"></a>
  <br>
  reconWEB
  <br>
</h1>


<p align="center">
  <a href="https://github.com/ranjanbug/reconweb/releases/tag/v2.1.1">
    <img src="https://img.shields.io/badge/release-v2.1.1-green">
  </a>
   </a>
  <a href="https://www.gnu.org/licenses/gpl-3.0.en.html">
      <img src="https://img.shields.io/badge/license-GPL3-_red.svg">
  </a>
  <a href="https://twitter.com/ranjanbug1">
    <img src="https://img.shields.io/badge/twitter-%40ranjanbug1-blue">
  </a>
    <a href="https://github.com/ranjanbug/reconweb/issues?q=is%3Aissue+is%3Aclosed">
    <img src="https://img.shields.io/github/issues-closed-raw/ranjanbug/reconweb.svg">
  </a>
  <a href="https://github.com/ranjanbug/reconweb/wiki">
    <img src="https://img.shields.io/badge/doc-wiki-blue.svg">
  </a>
  <a href="https://t.me/joinchat/H5bAaw3YbzzmI5co">
    <img src="https://img.shields.io/badge/telegram-@reconWEB-blue.svg">
  </a>
  <a href="https://hub.docker.com/r/ranjanbug/reconweb">
    <img alt="Docker Cloud Build Status" src="https://img.shields.io/docker/cloud/build/ranjanbug/reconweb">
  </a>
</p>

 
<h3 align="center">Sumário</h3>

**ReconWEB** automatiza todo o processo de reconhecimento para você. Realiza o trabalho de enumeração de subdomínios, junto com diversos checks de várias vulnerabilidades e
e o máximo de informação possível do seu alvo.

O ReconWEB utiliza de várias técnicas (passive, bruteforce, permutations, certificate transparency, source code scraping, analytics, DNS records...) na enumeração
dos subdomínios que ajudam você a selecionar os subdomínios mais interesantes para você saia na frente da competição

O mesmo também realiza vários checks de vulnerabilidades como XSS, Open Redirects, SSRF, CRLF, LFI, SQLi, testes de SSL, DNS Zone Transfers e muito mais. Além disso
é perfomado diversas técnicas de OSINT, fuzzing de diretórios, dorking, escaneamento de portan e scan do nuclei no seu alvo.

Então, o que está esperando? Bora! Bora! Bora! :boom:

📔 Tabela de Conteúdos
-----------------
- [💿 Instalação:](#-installation)
  - [a) No seu PC/VPS/VM](#a-in-your-pcvpsvm)
  - [b) Docker container 🐳 (2 options)](#b-docker-container--2-options)
    - [1) Pelo DockerHub](#1-from-dockerhub)
    - [2) Pelo repositório](#2-from-repository)
- [⚙️ Arquivo de configuração:](#️-config-file)
- [Uso:](#usage)
- [Exemplos de uso:](#example-usage)
- [Suporte ao Axiom: :cloud:](#axiom-support-cloud)
- [Suporte ao BBRF: :computer:](#bbrf-support-computer)
- [Vídeo de Demonstração:](#sample-video)
- [:fire: Características :fire:](#fire-features-fire)
  - [Osint](#osint)
  - [Subdomains](#subdomains)
  - [Hosts](#hosts)
  - [Webs](#webs)
  - [Extras](#extras)
- [Mindmap/Workflow](#mindmapworkflow)
  - [Data Keep](#data-keep)
    - [Comandos principais:](#main-commands)
  - [Como contribuir:](#how-to-contribute)
  - [Precisa de ajuda? :information_source:](#need-help-information_source)
  - [Dê suporte ao projeto me comprando um café:](#you-can-support-this-work-buying-me-a-coffee)
- [Patrocinadores ❤️](#sponsors-️)
- [Agradecimentos :pray:](#thanks-pray)
- [Isenção de responsabilidade](#disclaimer)
