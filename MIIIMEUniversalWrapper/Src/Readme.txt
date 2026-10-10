========================================================================
             MIIIME Universal Wrapper (MUW™)
========================================================================

MIIIME Universal Wrapper is an auxiliary tool for portable launchers.
Handles traces remaining after execution ends.

미매래퍼는 포터블 런처의 보조도구입니다.
실행 종료후 남는 흔적을 처리합니다.

========================================================================
Process
========================================================================

1. Open the MIIIMEUniWrapper.ini file and set the target to execute (TargetAppPortable) and the registry key to manage (Registry).
2. Run MIIIMEUniWrapper.exe.
3. When the target program terminates, it automatically erases traces and closes.

1. MIIIMEUniWrapper.ini 파일을 열어 실행할 대상(TargetAppPortable)과 관리할 레지스트리 키(Registry)를 설정합니다.
2. MIIIMEUniWrapper.exe를 실행합니다.
3. 대상 프로그램이 종료되면, 자동으로 흔적을 지우고 종료됩니다. 

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

========================================================================
Folder Structure
========================================================================

TargetAppPortable/
	│
	├─ MIIIMEUniWrapper.exe		래퍼 실행 파일		/ Wrapper executable
	├─ MIIIMEUniWrapper.ini		래퍼 설정 파일		/ Configuration file
	├─ MIIIMEUniWrapper.log		실행 로그				/ Runtime log
	│
	└─ MUW_Dat/                		사용자 데이터 저장소	/ Active user data
		└─ RegBakk/            		레지스트리 호스트 백업 임시 저장 (자동 생성) 	/ Registry Host Backup Temporary Storage (Automatically generated)

========================================================================
Macros
========================================================================

{Base}              	런처 최상위 폴더				/ Launcher root folder
{System32}		C:\Windows\System32
{SysWOW64}         C:\Windows\SysWOW64
{ProgramData}		C:\ProgramData
{UserProfile}		C:\Users\[UserName]
{Desktop}			바탕화면                			/ Desktop
{Local}         		%LocalAppData%
{Roaming}       	%AppData%
{LocalLow}      	%UserProfile%\AppData\LocalLow
{Temp}			임시 폴더						/ Temp folder
{Programs}		프로그램 목록 폴더       		/ Programs folder

______________________________________________________________________________________________________________________

This program was created with AutoIt. Some antivirus programs may incorrectly detect it as a virus.
본 프로그램은 AutoIt으로 제작되었습니다. 일부 백신이 바이러스로 오진 할 수 있습니다.

========================================================================
[Disclaimer]
========================================================================

Provided **"AS IS"**, without warranty.
This is a **private project**. No technical support is provided.
본 프로그램은 **"있는 그대로"** 제공되며, 사용 중 발생하는 문제에 대해 제작자는 책임을 지지 않습니다.
기술 지원은 제공되지 않습니다.

Developer	: MIIIME 
Website		: https://www.miiime.com 
GitHub		: @miiimeworks 
Update		: 2026.10.09
