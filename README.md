# Hi, I'm Gerrit 👋

**Senior Full-Stack Software Engineer | Pretoria, South Africa**

I design, build and run business-critical software end to end: desktop, web, mobile, database and the infrastructure underneath it. I have spent years as a one-person engineering department, which means I have been the architect, developer, DBA, DevOps team and help desk, usually before lunch.

## What I do

- **Legacy modernisation:** moving long-running VB.NET desktop systems to modern web platforms without breaking the business along the way
- **Full-stack web:** React front ends, Node.js, Python (FastAPI) and .NET back ends, containerised with Docker
- **Mobile:** native Android apps for rugged field handhelds and cross-platform staff apps in React Native
- **Database performance:** SQL Server tuning that makes queries faster while returning exactly the same results
- **Infrastructure:** DEV / TEST / PROD environments on Proxmox, network monitoring and internal tooling
- **Practical AI:** locally hosted LLMs (Ollama) for automated checks and day-to-day engineering tools

## Featured projects

### HydroSpec (Android)
Field data capture app running on rugged Zebra handheld scanners.
- Native Android (Java), supporting everything from Android 4.4 to 14, because field devices never retire
- Barcode and QR scanning, GPS trip tracking, photos, digital signatures and inspection workflows
- Works offline on local SQLite, then syncs back to SQL Server

### AQ Mobile (Android, iOS ready)
Company-wide staff app: push notifications, leave applications and approvals, schedules and a newsroom.
- React Native (Expo) front end with in-app updates
- .NET API and background worker, PostgreSQL, all running in Docker behind Caddy
- Keycloak sign-in with two-factor authentication
- Firebase Cloud Messaging for push, Cloudflare Workers relay so phones connect securely without a VPN

## Tech stack

| Area | Tools |
|---|---|
| Languages | VB.NET, C#, Python, Java, JavaScript, SQL, Natural |
| Front end | React, Windows Forms |
| Mobile | Android (native Java, Android Studio), React Native (Expo), Zebra EMDK, Firebase Cloud Messaging |
| Back end | Node.js, FastAPI, .NET Web API and workers |
| Data | SQL Server, PostgreSQL, SQLite, Adabas |
| Security | Keycloak (SSO, TOTP two-factor) |
| Platform | Docker, Proxmox, Caddy, Cloudflare Workers |
| AI | Ollama (local LLMs) |

## How I work

- Performance first, minimal dependencies
- If a good free tool already exists, I use it instead of rebuilding it
- Code should still make sense to whoever opens it in ten years (it is usually me)

## Outside of work

- Home Assistant and smart home automation
- Electronics tinkering
- Running local LLMs on a GPU that is doing its absolute best
- A string art portrait generator in Python: 272 nails and one greedy algorithm

## Fun facts

- My code reviews have a 100% approval rate. I am the only reviewer.
- I have written Natural on Adabas and React Native in the same career. Carbon dating is available on request.
- Yes, I still write VB.NET. No, I will not be taking questions.
