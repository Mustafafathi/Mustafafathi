 <div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:10172A,50:164E63,100:2563EB&height=210&section=header&text=Mustafa%20Fathi&fontSize=52&fontColor=FFFFFF&fontAlignY=38&desc=INFORMATION%20SYSTEMS%20ENGINEER%20%7C%20SOFTWARE%20DEVELOPER&descSize=13&descAlignY=60&animation=fadeIn" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=17&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=700&lines=Systems+Analyst+%7C+Software+Engineer;Designing+and+Building+Information+Systems;Database+Engineering+%7C+System+Integration;Turning+Business+Requirements+into+Solutions" />

<p>
<img src="https://komarev.com/ghpvc/?username=Mustafafathi&style=for-the-badge&color=2563EB&label=PROFILE+VIEWS" />
<img src="https://img.shields.io/github/followers/Mustafafathi?style=for-the-badge&color=0E7490&label=FOLLOWERS" />
</p>

</div>

---

## About Me

I am an Information Systems Engineer focused on systems analysis, software architecture, backend development, and database engineering.

I approach software development from a systems perspective: understanding business requirements, analyzing operational workflows, designing technical solutions, and implementing reliable information systems.

My engineering interests include:

- Systems Analysis & Requirements Engineering
- Software Architecture & Backend Development
- Database Engineering & Business Logic
- System Integration & Process Automation
- Infrastructure Administration & Reliability

---

## Technical Skills

### Programming Languages

<p>
<img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=databricks&logoColor=white"/>
</p>

### Database Engineering

<p>
<img src="https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white"/>
<img src="https://img.shields.io/badge/T--SQL-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white"/>
<img src="https://img.shields.io/badge/IndexedDB-315A75?style=for-the-badge"/>
</p>

### Web Development

<p>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
<img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
</p>

### Systems & Development Tools

<p>
<img src="https://img.shields.io/badge/Windows-0078D4?style=for-the-badge&logo=windows&logoColor=white"/>
<img src="https://img.shields.io/badge/Windows%20Server-0078D4?style=for-the-badge&logo=windows&logoColor=white"/>
<img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/Apache-D22128?style=for-the-badge&logo=apache&logoColor=white"/>
</p>

### Integration & Security

<p>
<img src="https://img.shields.io/badge/REST%20APIs-009688?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Webhooks-2563EB?style=for-the-badge"/>
<img src="https://img.shields.io/badge/HMAC-Security-475569?style=for-the-badge"/>
<img src="https://img.shields.io/badge/SHA--256-Data%20Integrity-475569?style=for-the-badge"/>
</p>

---

## Featured Project

### AIS — Student Attendance Information System

<p align="center">
<strong>STI NUST MISIS</strong>
</p>

A web-based student attendance management system developed to automate academic attendance workflows, improve data consistency, and integrate with existing university infrastructure.

**Key Engineering Features**

| Component | Implementation |
|---|---|
| Attendance | QR-based session validation |
| Offline Mode | IndexedDB browser storage |
| Synchronization | SHA-256 idempotency keys |
| Authentication | Role-based access control |
| Integration | HMAC-secured webhooks |
| University ERP | CSV exchange with 1C:University |
| Backend | PHP |
| Database | Microsoft SQL Server |

**Database Engineering**

<p>
<img src="https://img.shields.io/badge/42-Tables-2563EB?style=for-the-badge"/>
<img src="https://img.shields.io/badge/125-Stored%20Procedures-0E7490?style=for-the-badge"/>
<img src="https://img.shields.io/badge/17-Triggers-7C3AED?style=for-the-badge"/>
</p>

**Source Code**

<p>
<a href="https://github.com/Mustafafathi/ais-system-en">
<img src="https://img.shields.io/badge/English%20Repository-181717?style=for-the-badge&logo=github"/>
</a>
<a href="https://github.com/Mustafafathi/ais-system-ru">
<img src="https://img.shields.io/badge/Russian%20Repository-181717?style=for-the-badge&logo=github"/>
</a>
</p>

### Architecture Overview

```mermaid
flowchart LR
    subgraph Browser
        UI["Role workspaces<br/>HTML, CSS, JavaScript"]
        IDB[("IndexedDB<br/>offline queue")]
    end
    subgraph PHP["PHP application"]
        API["API gateway<br/>sessions, validation, routing"]
    end
    subgraph SQL["Microsoft SQL Server"]
        SP["Stored procedures<br/>business rules"]
        TBL[("Domain tables")]
        AUD[("Audit log")]
        TRG["Triggers"]
    end
    ACS["Access-control system"] -- "HMAC-signed webhook" --> API
    ERP["1C:University"] <-- "CSV import / export" --> API
    UI --> API
    IDB -. "sync with idempotency keys" .-> API
    API --> SP
    SP --> TBL
    SP --> AUD
    TRG --> AUD
```

## Engineering Focus

| Discipline | Practical Application |
|---|---|
| Systems Analysis | Requirements and workflow modeling |
| Software Architecture | Application and database design |
| Backend Engineering | Server-side business logic |
| Database Engineering | Relational modeling and SQL optimization |
| System Integration | Webhooks and external data exchange |
| Reliability | Validation and duplicate prevention |
| Automation | Academic workflow automation |

---

## GitHub Analytics

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Mustafafathi&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&rank_icon=github"/>

<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mustafafathi&layout=compact&theme=tokyonight&hide_border=true&langs_count=8"/>

</div>

<div align="center">

<img width="75%" src="https://streak-stats.demolab.com?user=Mustafafathi&theme=tokyonight&hide_border=true"/>

</div>

## Contribution Activity

<div align="center">

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=Mustafafathi&theme=tokyo-night&hide_border=true&area=true"/>

</div>

---

<div align="center">

### Engineering reliable systems through analysis, architecture, and implementation.

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2563EB,100:10172A&height=110&section=footer"/>

</div>
