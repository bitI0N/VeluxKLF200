[![Version](https://img.shields.io/badge/Symcon-PHPModul-red.svg?style=flat-square)](https://www.symcon.de/service/dokumentation/entwicklerbereich/sdk-tools/sdk-php/)
[![Version](https://img.shields.io/badge/Modul%20Version-0.70-blue.svg?style=flat-square)]()
[![Version](https://img.shields.io/badge/Symcon%20Version-5.5%20%3E-green.svg?style=flat-square)](https://www.symcon.de/service/dokumentation/installation/migrationen/v54-v55-q4-2020/)  
[![License](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-green.svg?style=flat-square)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![Check Style](https://github.com/Nall-chan/VeluxKLF200/workflows/Check%20Style/badge.svg)](https://github.com/Nall-chan/VeluxKLF200/actions) [![Run Tests](https://github.com/Nall-chan/VeluxKLF200/workflows/Run%20Tests/badge.svg)](https://github.com/Nall-chan/VeluxKLF200/actions)  

# VeluxKLF200 <!-- omit in toc -->

Diese Implementierung der API von dem Velux KLF200 Gateway
ermöglicht die Einbindung von allen io-homecontrol® Geräten, welche von diesem Gateway unterstützt werden.  


## Dokumentation <!-- omit in toc -->

**Inhaltsverzeichnis**

- [1. Funktionsumfang](#1-funktionsumfang)
  - [KLF200 Configurator:](#klf200-configurator)
  - [KLF200 Gateway:](#klf200-gateway)
  - [KLF200 Node:](#klf200-node)
- [2. Voraussetzungen](#2-voraussetzungen)
- [3. Software-Installation](#3-software-installation)
- [4. Einrichten der Instanzen in IP-Symcon](#4-einrichten-der-instanzen-in-ip-symcon)
- [5. Anhang](#5-anhang)
  - [1. GUID der Module](#1-guid-der-module)
  - [2. Changelog](#2-changelog)
  - [3. Spenden](#3-spenden)
- [6. Lizenz](#6-lizenz)

## 1. Funktionsumfang

### [KLF200 Configurator:](KLF200Configurator/)  
### [KLF200 Gateway:](KLF200Gateway/)  
### [KLF200 Node:](KLF200Node/)  

## 2. Voraussetzungen

 - IPS 5.5 (beta Release) oder neuer  
 - KLF200 io-homecontrol® Gateway  
    - KLF muss per LAN angeschlossen sein  
    - KLF Firmware 2.0.0.71 oder neuer   

## 3. Software-Installation

   Über den 'Module-Store' in IPS das Modul 'VELUX KLF200' hinzufügen.   
   **Bei kommerzieller Nutzung (z.B. als Errichter oder Integrator) wenden Sie sich bitte an den Autor.**  

## 4. Einrichten der Instanzen in IP-Symcon

Ist direkt in der Dokumentation der jeweiligen Module beschrieben.  
Es wird empfohlen die Einrichtung mit der Konfigurator-Instanz zu starten ([KLF200 Configurator:](KLF200Configurator/)).  

## 5. Anhang

###  1. GUID der Module
 
 
| Modul               | Typ          |Prefix  | GUID                                   |
| :-----------------: | :----------: | :----: | :------------------------------------: |
| KLF200 Configurator | Configurator | KLF200 | {38724E6E-8202-4D37-9FA7-BDD2EDA79520} |
| KLF200 Gateway      | Splitter     | KLF200 | {725D4DF6-C8FC-463C-823A-D3481A3D7003} |
| KLF200 Node         | Device       | KLF200 | {4EBD07B1-2962-4531-AC5F-7944789A9CE5} |

### 2. Changelog

 Version 0.7:
 - PTLS entfernt.  
  
 Version 0.6:
 - Button im Splitter für das Lesen der Firmwareversion war ohne Funktion.  
 - Fehler im Konfigurator, wenn Namen der Geräte einen Umlaut enthielt.  
 - Der Konfigurator hat eine neuen Button, um im laufenden Betrieb die Geräteliste neu zu laden.  

 Version 0.5:  
 - Öffentliche Betaversion  
 - Dokumentation erstellt  

 Version 0.1:  
 - Testversion  


### 3. Spenden  
  
  Die Library ist für die nicht kommerzielle Nutzung kostenlos, Schenkungen als Unterstützung für den Autor werden hier akzeptiert:  

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=G2SLW2MEMQZH2" target="_blank"><img src="https://www.paypalobjects.com/de_DE/DE/i/btn/btn_donate_LG.gif" border="0" /></a>

## 6. Lizenz

  [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)  