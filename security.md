# Security Policy

## 🚨 Zero-Tolerance Policy (CSAM)

DeepWare AI has an absolute zero-tolerance policy regarding the use of this tool for the creation, distribution, or facilitation of Child Sexual Abuse Material (CSAM) or any content that harms or sexualizes minors.

**The detection logic in this tool is designed to trigger an immediate and permanent lockout if such intent is identified.**

## 🛡️ Enforcement & Blacklisting

If a violation is detected:
* **HWID Blacklist:** Your Hardware ID will be permanently flagged, preventing the tool from running on your machine.
* **IP/MAC Blacklist:** Your network identifiers will be logged and blocked from accessing DeepWare update servers and model repositories.
* **Session Termination:** All current operations will cease immediately.

## ⚖️ Appeals Process

If you believe a blacklist was triggered in error (false positive), you must follow the official appeals process:
1. Join the official Telegram: **t.me/DeepWareAI**
2. Contact an administrator with your HWID and a detailed explanation of the session context.
3. Be prepared to provide logs if requested. 

**Note:** Appeals are reviewed manually. Hostile or deceptive behavior during the appeal will result in an immediate and final denial.

## 🔒 Reporting a Vulnerability

If you find a security flaw in the DeepWare CLI or GUI that could lead to unauthorized access or bypasses of our safety systems:
* Do **not** open a public GitHub Issue.
* Report the vulnerability privately via the Telegram group or to the Head Developer.
* We value responsible disclosure and will work to patch the issue before making it public.
