# Privacy Policy

**Effective Date:** July 18, 2025

This Custom GPT assistant helps a user (typically an entrepreneur) securely access, read, and summarize their Google Drive files using authenticated access. It is designed to operate in a professional, privacy-respecting manner and does not store or share personal information.

---

## 1. What This Assistant Does

- Reads the contents of files in the user's **Google Drive (My Drive and Shared Drives)**.
- Summarizes files, extracts key insights, and helps locate and organize files.
- Only works with content that the user explicitly authorizes through secure Google OAuth 2.0 login.

---

## 2. Data Handling and Storage

- No file content is stored permanently. All processing is done **in-memory**.
- Files are accessed **temporarily**, only to generate a response to the user's request.
- **Nothing is logged or saved**, and no content is transmitted to third-party services.

---

## 3. Access and Limitations

This assistant will **not**:
- Upload or replace file content
- Download non-Google file formats
- Access or display trashed items (unless explicitly asked)
- Display file IDs unless absolutely necessary

Only files under the following limits are processed:
- **Docs/Sheets/Slides/PDFs**: max 50MB
- **Images**: max 10MB (OCR only)

---

## 4. Token & Security

- Google OAuth tokens are securely handled using **Google Cloud services**.
- Refresh tokens are stored only in the user’s **Google Workspace environment**, not by third-party databases.
- Tokens are used to maintain sessions only, and never shared or sold.

---

## 5. Third-Party Sharing

- This assistant **does not share data** with any third parties.
- It does not access the web or use external APIs unless explicitly instructed by the user.

---

---

*This policy may be updated from time to time to reflect improvements and security best practices.*
