# 🛡️ GitHub Verification Codes Manager

A secure, centralized repository for storing, tracking, and managing GitHub verification codes, 2FA backup codes, and device authorization tokens.

---

## ⚠️ Security Notice

> **IMPORTANT:** Verification codes, two-factor authentication (2FA) tokens, and backup recovery codes grant access to GitHub accounts. 
> * **Private Repository:** Ensure this repository remains **Private** at all times to prevent unauthorized access.
> * **Token Expiration:** GitHub verification codes and one-time passwords (OTPs) have a very short lifespan (typically 30–60 seconds). Ensure expired codes are cleared regularly.
> * **Secret Scanning:** Be cautious not to commit personal access tokens (PATs), SSH keys, or plain-text passwords alongside your verification codes.

---

## 📁 Repository Structure

```text
├── .github/              # Issue templates and workflows
├── codes/                # Stored verification codes & logs
│   ├── backup_codes.txt  # GitHub 2FA recovery codes (Encrypted/Secure)
│   └── recent_logins.md  # Log of authorized device verifications
├── .gitignore            # Excludes sensitive local configs & temp files
└── README.md             # Project documentation
