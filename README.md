# IPAS_Security_M_2026

# 課程內容
- 資訊安全規劃實務
- 資訊安全防護實務
# 資訊安全規劃實務
## 單元1:資訊安全管理系統規劃與建置
- CIA 
- ISMS 與 Security Controls
- NIST CSF 2.0
- 法規遵循
## 單元2:資訊安全規劃
- Secure design principle
- 應用1.資訊安全架構
- 應用2.網路架構規劃
- 應用3.實體安全規劃
- 密碼學
## 單元3:存取管理(Access management)
- IAM
- 身分認證(FIDO)
- 零信任架構
## 單元4:風險管理實務
## 單元5:BCM業務持續管理 
## 單元6:供應鏈安全管理與資訊委外安全管理
- 系統取得| 安全性
  - COTS | Commercial-off-the-shelf | commercially available off-the-shelf [IPAS_M_管理模擬考_6_1_A] 
    - Configuration management 與 Patch management
  - 自行開發 ==> 各種開發架構的安全性 ==> SSDLC vs  vs DevSecOps[IPAS_M_管理模擬考_6_2_A] 
  - 委外開發(custom software | 客製化軟體)安全管理與 供應鏈安全管理(Secure Software Supply Chain)
    - 資訊系統委外開發安全管理
    - 供應鏈安全管理 Secure Software Supply Chain

## 單元7:資訊安全營運
- 安全營運管理主題
- Configuration management 與 Patch management
- media management
- 日誌管理
- 安全監控與管理

## 單元8:資訊安全營運II


# 資訊安全防護實務 
## PART I: CyberSecurity Attacks & Defense: 攻擊分析|資安防護|資安應變
## 單元1:攻擊模式分析與防禦
#### 近期資安事件
#### SYSTEM系統威脅分析與防禦
- Windows Security
- Windows Subsystem for Linux (WSL)
#### Network網路攻擊與防禦
#### Web網站威脅分析與防禦
- [OWASP Top Ten Proactive Controls](OWASPTopTenProactiveControls.md)
- [HTTP security](HTTPsecurity.md)
- HTTPs security

#### 資料安全威脅與防護

## 單元2:威脅建模與MITRE ATT@CK
- 2-1.威脅建模(Threat Modelling)
  - [Threat Model Manifesto](https://www.threatmodelingmanifesto.org/)
  - [OWASP Threat Modeling Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Threat_Modeling_Cheat_Sheet.html)
- 2-2.MITRE ATT&CK
- 其他框架
  - MITRE Altas 

## 單元三:3:MITRE D3FEND與資安防護實務
- 3-1.MITRE D3FEND
- 3-2.`Defensive` security
  - 防毒軟體
  - 防火牆(Firewall)
  - `網站應用程式`防火牆(Web Application Firewall, WAF)
  - 入侵偵測系統(intrusion detection system)IDS vs IPS
  - UTM
  - 蜜罐|Honeypot|Honeywall
  - SOC資安監控中心/SIEM
    - EDR
    - SOAR  
- 專業主題

## 單元四:安全維運II與資安應變實務
- 課程主題
  - DFIR | Digital Forensics and Incident Response |數位鑑識與入侵應變
    - Digital Forensics |數位鑑識
    - Incident Response |入侵應變
  - Cyber Threat Intelligence(CTI) 威脅情資
  - Threat Hunting 威脅獵捕
- 事故處理與應變(Incident handling and response)
  - NIST《資安事故處理指引》(NIST SP 800-61)  Computer Security Incident Handling Guide
- 數位鑑識
  - NIST 四階段數位鑑識流程(Digital forensic process) 
  - 政府機關(構)資安事件數位證據保全標準作業程序(共有六大項)
- Cyber Threat Intelligence(CTI) 威脅情資
- Threat Hunting 威脅獵捕


# PART II.安全測試與評估
- Information Security Testing and Assessment
- [112 年共同供應契約資通安全服務品項採購規範]
- NIST SP 800-115 《資訊安全測試與評估技術指南》
  - Technical Guide to Information Security Testing and Assessment
  - NIST Four-Stage Penetration Testing Methodology 

## 單元五.原始碼檢測
- 程式安全(Application Security) VS 安全程式(Secure Coding)
  - 程式安全(Application Security)
    - 資安情境1:如何保護你的程式不被破解
    - 資安情境2:如何破解惡意程式 ==> 惡意程式分析(Malware analysis)
      - 靜態分析與逆向工程
      - 動態分析 
  - 安全程式(Secure Coding) ==> 如何撰寫具有高度安全性的程式與系統?
    - OWASP GUIDE
    - CERT 
    - SSLDC MS SDL 
- CODE REVIEW  vs SECURE CODE REVIEW
  - CODE REVIEW
  - SECURE CODE REVIEW

## 單元六.漏洞|弱點 掃描
- 漏洞與漏洞管理
- 漏洞檢測:檢測是否存在某一漏洞
  - 使用 nmap
  - 使用 metasploit
  - 其他
- 大量漏洞檢測:弱點掃描
  - 使用open source 弱點掃描器
    - 使用 OpenVAS進行`系統`弱點掃描
    - 使用 OWASP ZAP(Zed Attack Proxy )進行`網站`弱點掃描
    - 使用 Nitko進行`網站`弱點掃描
  - 使用商業版弱點掃描器(資安服務公司使用)
    - `系統`弱點掃描 ==> Nessus
    - `網站`弱點掃描(Web Application Security Scanner)
      - Acunetix | Fortify/HP WebInspect | HCL/IBM  AppScan
- 漏洞修補


## 單元七:滲透測試(Penetration Testing)與紅隊演練(Red Team Assessment) 
- ==> `Offensive` Security  ==> 整合 MITRE ATT&CK
- 滲透測試 | Penetration Testing | PT
- 滲透測試方法論(Penetration Testing::Standard|Framework)
- 常用滲透測試工具
- 滲透測試主題A
  - SMTP enumeration
  - DNS enumation 
- 滲透測試主題B:Windows AD
  - Windows AD
  - Windows AD滲透測試
  - [Covering Tracks and Tunneling](Tunneling.md)
  - Windows NTLM 認證: 攻擊手法
  - [Windows Kerberos authentication與攻擊手法](MITRE_ATTaCKT_1558.md)
- 滲透測試主題C:網站滲透測試
- [紅隊演練(Red Team Assessment)](Red_Team_Assessment.md)
- 常用滲透測試工具
  - nmap 進階技術
  - Windows Shell
    - [windows cmd 指令](Windows_Commands.md)
    - [Windows powershell](powershell.md)
  - [Windows Sysinternals工具](Windows_Sysinternals.md)
  - [SQLMAP](SQLMAP.md)
  - [mimikatz](mimikatz.md)

## 單元八:資安健檢
- 資安健檢
- 資安健檢_網路架構檢視
- 資安健檢_封包側錄與分析
- 資安健檢_日誌分析
- 資安健檢_目錄伺服器設定檢視

# 進階主題主題
- AI與安全
- OT security and management
  - OT
  - OT 威脅
  - 國際標準
- IOT Security
- Mobile Security
- [Cloud Security| 雲端安全

## 舊版
- https://github.com/8wingflying/IPAS_M_20250222
- https://github.com/8wingflying/IPAS_SECURITY_202512
- https://github.com/8wingflying/IPAS_M_202406_Taipei
