 <div align="center">

# Mustafa Fathi

**INFORMATION SYSTEMS ENGINEER**

*Systems Analysis · Database Engineering · Software Development*

<br/>

I build information systems by connecting business processes, data architecture, and application logic.

<br/>

[GitHub](https://github.com/Mustafafathi) &nbsp; / &nbsp; [AIS — English](https://github.com/Mustafafathi/ais-system-en) &nbsp; / &nbsp; [AIS — Русский](https://github.com/Mustafafathi/ais-system-ru)

</div>

---

### 01 — Perspective

## Engineering from the system level.

My approach to software engineering starts before implementation: understanding how a process works, identifying its requirements, modelling its data, and translating that structure into a maintainable information system.

I am particularly interested in the relationship between **business logic, database architecture, and application behaviour** — especially in systems where data integrity and operational reliability matter.

My work brings together:

- **Systems analysis** — requirements, business workflows, roles, and process modelling.
- **Database engineering** — relational data models, SQL Server, and database-level logic.
- **Backend development** — PHP applications, server-side processing, and authentication.
- **System integration** — data exchange, webhooks, and connections with existing institutional systems.

---

### 02 — Selected Work

## AIS / Student Attendance Information System

**Graduation project · STI NUST MISIS**

A web-based information system designed to manage student attendance workflows within a university environment.

The system brings together students, teachers, administrators, curators, and methodists through role-based workflows and a shared database.

<div align="center">

[**English Repository ↗**](https://github.com/Mustafafathi/ais-system-en) &nbsp;&nbsp; · &nbsp;&nbsp; [**Russian Repository ↗**](https://github.com/Mustafafathi/ais-system-ru)

</div>

#### System design

| Component | Implementation |
|:--|:--|
| Web application | PHP, JavaScript, HTML, CSS |
| Database platform | Microsoft SQL Server 2022 |
| Data access | SQLSRV, ODBC |
| Business logic | T-SQL stored procedures and triggers |
| Offline capability | IndexedDB and synchronization |
| External integration | HMAC-secured webhooks, CSV / 1C:University |

#### Engineering decisions

**Attendance validation**

QR-based attendance sessions are validated on the server. The system checks session validity and prevents duplicate attendance records.

**Offline-first check-in**

Attendance records can be queued in the browser using IndexedDB and synchronized later. SHA-256 idempotency keys help prevent duplicate processing during synchronization.

**Database-centred business logic**

Core operations are implemented through SQL Server stored procedures and triggers, keeping important data operations close to the database.

**Integration and security**

HMAC-secured webhooks support integration with physical access-control systems. CSV exchange supports interaction with 1C:University.

**Role-based workflows**

The application supports five user groups: administrators, students, teachers, curators, and methodists.

#### Database at a glance

<div align="center">

| 42 | 125+ | 17 |
|:---:|:---:|:---:|
| Tables | Stored Procedures | Triggers |

</div>

The project was developed as my graduation project. AI coding tools assisted implementation under my architecture, specifications, and review process.

[AI collaboration documentation ↗](https://github.com/Mustafafathi/ais-system-en/blob/main/AI_COLLABORATION.md)

---

### 03 — Technical Foundation

## Technologies & tools

My primary implementation experience is centred on the technologies used to analyse, build, and maintain database-driven applications.

**Application development**

<p>
  <img src="https://skillicons.dev/icons?i=php,js,html,css" alt="PHP, JavaScript, HTML and CSS"/>
</p>

**Database engineering**

Microsoft SQL Server · T-SQL · SQLSRV · ODBC · Relational Data Modelling

**Additional development**

<p>
  <img src="https://skillicons.dev/icons?i=python,dotnet,nodejs" alt="Python, .NET and Node.js"/>
</p>

These are also present in my development environment; they are not all part of the AIS implementation.

---

### 04 — Working Environment

## A practical engineering toolkit.

The following is a selection of installed tools and development utilities from my current environment.

**IDEs & development environments**

Visual Studio Code · Visual Studio · XAMPP · Git · GitHub

**Databases & enterprise systems**

Microsoft SQL Server 2022 · SQL Server Management Studio 21 · ODBC Driver 17 / 18 · OLE DB Driver · 1C:Enterprise 8 (Training Version)

**Languages & runtimes**

PHP 8.3 · Python 3.12 · Node.js 24 · npm · .NET SDK 9 · PowerShell 7

**System & integration utilities**

Windows 11 · WSL · Oracle VirtualBox · Postman · ngrok · FileZilla · draw.io · Windows Terminal

**AI-assisted development**

Claude Code · OpenCode · OpenAI Codex · ChatGPT · Claude

**VS Code extensions**

PHP Intelephense · PHP Debug · Continue · Kilo Code · CodeRabbit · DSCodeGPT · Python / Pylance · C# Dev Kit · PowerShell · Prettier · YAML · Live Server

---

### 05 — Engineering Interests

## What I am developing further.

- Information systems architecture and requirements engineering.
- Relational database design and SQL Server performance.
- Backend development and enterprise application integration.
- Infrastructure fundamentals and software delivery.
- AI-assisted engineering workflows and implementation review.

I value software that is not only functional, but also understandable, consistent, and maintainable.

---

<div align="center">

*Understand the process. Structure the data. Engineer the system.*

<br/>

[GitHub Profile](https://github.com/Mustafafathi)

</div>
