# CyberPath

![HTML5](https://img.shields.io/badge/HTML5-single%20file-orange?style=flat-square&logo=html5&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-3D%20scene-black?style=flat-square&logo=three.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-vanilla-f7df1e?style=flat-square&logo=javascript&logoColor=black)
![Bilingual](https://img.shields.io/badge/Language-ES%20%2F%20EN-00ff88?style=flat-square)
![PDF Viewer](https://img.shields.io/badge/PDF-embedded%20viewer-e11d48?style=flat-square)
![Cybersecurity](https://img.shields.io/badge/Focus-cybersecurity-0ea5e9?style=flat-square)

CyberPath is an interactive cybersecurity roadmap built as a single-page web experience. It combines a 3D visual journey, curated learning platforms, built-in practice labs, bilingual language switching, and an embedded PDF viewer for the companion guide.

Public demo:
[https://devcop95.github.io/cyberpath](https://devcop95.github.io/cyberpath)

## Tags

`cybersecurity` `ethical-hacking` `pentesting` `ctf` `threejs` `javascript` `interactive-roadmap` `bilingual-ui` `pdf-viewer` `learning-platforms`

## Overview

CyberPath organizes 18 recommended platforms into three skill tiers:

- Beginner
- Intermediate
- Advanced

The interface is designed to feel like a living roadmap instead of a static list. Users can rotate the scene, inspect platforms, switch between Spanish and English, launch labs, and open the PDF without leaving the website.

## Main Features

- Interactive 3D roadmap with 18 cybersecurity platforms
- ES / EN language toggle
- Embedded PDF preview inside the site
- Platform detail modal with description, level reasoning, features, and technical metadata
- Built-in challenge lab with guided exercises
- Progress persistence through `localStorage`

## Roadmap Platforms

### Beginner

- TryHackMe
- PicoCTF
- OverTheWire
- OWASP Juice Shop
- Hacker101
- CryptoHack

### Intermediate

- Hack The Box
- PortSwigger
- Root Me
- PentesterLab
- CTFChallenge
- YesWeHack DOJO

### Advanced

- VulnHub
- crAPI
- Metasploitable 3
- APIsec University
- Google CTF
- Hacking Hub

## Built-in Labs

CyberPath includes 5 guided labs:

1. Nmap Reconnaissance
2. Linux Fundamentals: Find the Flag
3. SQL Injection: Bypass Login
4. Hash Cracking: John the Ripper
5. Privilege Escalation: SUID Abuse

Each lab includes theory, objectives, hints, a simulated terminal, and saved progress in the browser.

## PDF Companion

The project includes `assets/CyberPath_Dragon_Edition.pdf` as a visual companion to the interactive roadmap. The PDF can be opened directly from the website through the built-in viewer or downloaded separately.

## Project Structure

- `index.html`: main application, styles, data, and JavaScript logic
- `README.md`: project documentation
- `assets/CyberPath_Dragon_Edition.pdf`: companion PDF

## Local Usage

1. Open `index.html` in a modern browser.
2. Use the `ES / EN` toggle to switch language.
3. Open the control menu to access the PDF viewer, reset view, auto-rotate, dragon toggle, and lab shortcut.
4. Click any platform to inspect its details.
5. Launch the lab mode from the terminal button.

## Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Three.js

## Notes

- The README is based on the current information available in `index.html` and the bundled PDF.
- The project is designed as a compact, self-contained front-end experience.
