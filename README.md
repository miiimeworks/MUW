# MIIIME Universal Wrapper (MUW™)

MIIIMEWrapper · 미메랩퍼

![OS](https://img.shields.io/badge/Platform-Windows-0078D4?logo=windows&style=flat-square)
[![Language](https://img.shields.io/badge/Language-AutoIt-orange?logo=autoit&style=flat-square)](https://www.autoitscript.com/site/)
![License](https://img.shields.io/badge/License-Freeware-lightgrey?style=flat-square)

<br>
<img width="559" height="136" alt="001" src="https://github.com/miiimeworks/M4T/blob/main/4bit_Enhanced/Id/Neon/4b_136_1_G.png?raw=true" style="margin-top: 20px; margin-bottom: 20px;">
<br>

MIIIME Universal Wrapper is an auxiliary tool for portable launchers.
Handles traces remaining after execution ends.

미매래퍼는 포터블 런처의 보조도구입니다.
실행 종료후 남는 흔적을 처리합니다.


---

### File Organization

```text
MIIIMEUniWrapper.exe     # [Run] Wrapper executable file / 래퍼 실행 파일
MIIIMEUniWrapper.ini     # [Settings] Cleanup target and rules / 정리 대상 및 규칙
```

---

## Process

01. RealShortcutGuard Backup (Protect Start Menu Shortcuts)
02. AppData Backup
03. Registry Backup
04. Injection (Parameter Injection)
05. UserFile Injection
06. Run Parent Launcher (PortableExeName) → Wait for Termination
07. CleanupExclude / CleanupDelete
08. Restore RealShortcutGuard
09. Restore UserFile
10. Restore AppData
11. Restore Registry

---

## 🛡️ Security & Anti-virus Info

### [✅ VirusTotal Analysis Report](https://www.virustotal.com/gui/file/e47275b15d702e396a6822eac227626e4aaad39c2b46c7839f4ea47251418695?nocache=1)

| Status             | Details                                                                        |
|:------------------ |:------------------------------------------------------------------------------ |
| **Major Vendors**  | **Clean** (Passed by AhnLab V3, Kaspersky, Microsoft, Avast, ESET, etc.)       |
| **Detection Rate** | **7 / 70** (Mostly Heuristic/Generic/Trojan-type flags)                        |
| **Integrity**      | The source is private, and the distribution files can be verified using hashes and VirusTotal results. |

> This Program was created with AutoIt. Some antivirus programs may incorrectly detect it as a virus.  
> 본 프로그램은 AutoIt으로 제작되었습니다. 일부 백신이 바이러스로 오진 할 수 있습니다. 

**File Checksum (SHA-256) :** `e47275b15d702e396a6822eac227626e4aaad39c2b46c7839f4ea47251418695`

---

## Disclaimer

Provided **“AS IS”**, without warranty.  
This is a **private project**. No technical support is provided.

본 프로그램은 **“있는 그대로”** 제공되며, 사용 중 발생하는 문제에 대해 제작자는 책임을 지지 않습니다.  
기술 지원은 제공되지 않습니다.

---

## Project Information

**Developer** : MIIIME  
**Website** : https://www.miiime.com  
**GitHub** : [@miiimeworks](https://github.com/miiimeworks)  
**Last Update** : 2026-10-09   

<br>
<img width="64" height="64" alt="002" src="https://github.com/miiimeworks/M4T/blob/main/4bit_Brutal/Logo/Neon/4b_Mium_64_0_G.png?raw=true">  
<br>
<br>
<br>
