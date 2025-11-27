# OSINT-Company-Runbook
The OSINT Company Screening Runbook is a fully interactive, zero-cost, browser-based worksheet designed for doing OSINT checks on businesses.

📌 Overview
The OSINT Company Screening Runbook is a fully interactive, zero-cost, browser-based worksheet designed for:
	• Vendor due diligence
	• Corporate background checks
	• Fraud investigations
	• Attack surface discovery
	• Executive exposure analysis
	• Pre-engagement intelligence collection
	• Enterprise cyber-risk assessments
	
This project requires no backend, uses no external databases, and stores all investigator notes locally in the browser only.

The HTML worksheet is portable, offline-friendly, and designed for real-world analysts performing structured corporate OSINT investigations.

Embedded OSINT Tool Links (Guided Workflow)
One of the most powerful features of this runbook is the inclusion of embedded, one-click links that launch the exact OSINT tools needed at each stage of your investigation.
This transforms the worksheet from a passive form into an active, guided investigation console.

Categories of tools included:

Domain & Infrastructure Intelligence
	• WHOIS lookups
	• DNS enumeration
	• Certificate Transparency (CT logs)
	• Subdomain discovery
	• Hosting/CDN fingerprinting
Cyber Risk & Security Hygiene
	• Shodan
	• Censys
	• Onyphe
	• Pulsedive
	• SSL Labs
	• SecurityHeaders
	• Mozilla Observatory
Reputation & Scam Detection
	• Scamadviser
	• Cisco Talos Intelligence
	• AlienVault OTX
	• PhishTank
People & Corporate OSINT
	• LinkedIn
	• Hunter.io
	• GitHub
	• Pastebin search
	• Google Dorks
Threat Intelligence & Malware
	• VirusTotal
	• URLScan
	• AbuseIPDB
	• BreachDirectory
	• HaveIBeenPwned


🚀 Features
✅ 1. Fully Interactive Sections
Every module expands/collapses and includes data-entry fields:
	• Company identity & domain footprint
	• DNS, WHOIS, CT logs
	• Cyber hygiene & attack surface
	• People OSINT
	• Reputation & sentiment
	• Local scanning guidance
	• Risk scoring model

✅ 2. Per-Section Notes With Local Storage
Every section includes a “Notes” panel:
	• Auto-saves in browser localStorage
	• Never leaves the device
	• Notes persist between sessions
	• Clear or export notes at any time

✅ 3. Red-Flag Panels (Expandable)
Each module contains collapsible “🚩 Red Flags” identifying:
	• Fraud indicators
	• Cybersecurity misconfigurations
	• Infrastructure anomalies
	• Reputation concerns
These help analysts quickly identify risk patterns.

✅ 4. Sidebar Navigation with Live Search
The left sidebar includes:
	• Full navigation tree
	• Global search bar
	• Expand all / collapse all
	• Export notes
	• Clear notes

✅ 5. Operational Security (OPSEC) Checklist
The OPSEC module includes:
	• VPN/Tor configuration
	• Persona management
	• Secure browser setups
	• Device/VM choices
	• Legal & ethical guidelines
This makes the runbook safe for sensitive investigations.


✅ 6. Zero External Dependencies
The file:
	• Runs locally
	• Loads in any browser
	• Does not call APIs
	• Does not collect telemetry
	• Does not require an internet connection (except to use linked OSINT tools)

✅ 7. Professional Investigator-Level Workflow
Built as a full methodology, including:
	• Purpose & scoping
	• Pre-engagement planning
	• Corporate footprint mapping
	• CT log review
	• DNS enumeration
	• Breach exposure analysis
	• Social & executive OSINT
	• Automated local scanning
	• Risk scoring

🛠️ How to Use
Step 1 — Open the HTML File
Just double-click:

OSINT Corp Background Check Worksheet.html
It will open in your browser automatically.
Recommended browsers:
	• Chrome
	• Firefox
	• Edge
	• Brave
(Safari works but has stricter localStorage quirks.)

Step 2 — Start at Section 0 (Purpose)
Fill out:
	• Client
	• Scope
	• What you are evaluating
	• Hypotheses

Step 3 — Move Through Each Module
Each module expands/collapses:
	1. OPSEC Setup
	2. Pre-Engagement Target Discovery
	3. Corporate Footprint
	4. Cyber Risk & Hygiene
	5. Legitimacy & Financial Context
	6. People OSINT
	7. Reputation & Sentiment
	8. Local Scanning Guidance
	9. Risk Scoring
Fill out inputs as you go.
Use the red-flag sections to assess risk severity.

Step 4 — Store Notes While You Work
Each section contains a notes box that:
	• Saves automatically
	• Stores locally
	• Never uploads or transmits anything
	• Can be cleared or exported

Step 5 — Export Notes (Recommended Before Final Report)
Use the sidebar button:
📤 Export All Notes
This produces a text file containing your structured findings.

Step 6 — Generate Your Report
Your exported notes + screenshots + structured findings feed directly into:
	• Consulting reports
	• Risk assessments
	• Due diligence summaries
	• Internal memos
	• Intelligence briefs

🧠 Technical Architecture & Explanation
This project is intentionally simple, secure, and offline-first.
### 🏗️ Project Structure

/OSINT-Company-Screening-Runbook/
│── README.md
│── LICENSE
│── CONTRIBUTING.md
│── SECURITY.md
│── .github/
│   ├── ISSUE_TEMPLATE.md
│   ├── BUG_REPORT.md
│   └── PULL_REQUEST_TEMPLATE.md
└── OSINT Corp Background Check Worksheet.html


⚙️ Under the Hood
1. Pure HTML + CSS + JS
No frameworks, no build steps.
2. Persistent Notes (localStorage)
Each notes box is bound to:

data-section="sec-XYZ"
JS loads & saves notes based on this key.
3. Expand/Collapse Logic
Controlled using:
	• <details> blocks
	• JS functions to open/close all at once
4. Live Search
The search bar scans all section titles and highlights matches.
5. No Back-End / No Network Calls
The worksheet does not:
	• send analytics
	• fetch remote resources
	• require a server
Everything is client-side only.

🔒 Security & Privacy Notes
	• Works fully offline
	• No data ever leaves the browser
	• No cookies
	• No external JS
	• Does not store PII anywhere except your device
	• Recommended to clear browser storage when done
Ideal for sensitive investigations.
<img width="720" height="4224" alt="image" src="https://github.com/user-attachments/assets/f9ed0afe-0443-4ab5-9a32-6d9a4c4c907f" />
