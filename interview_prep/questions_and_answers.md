# 🧠 Interview Questions & Answers: Browser Extension Security

## 1. How can browser extensions pose security risks?
Browser extensions can:
- Inject malicious scripts into web pages
- Steal sensitive data like passwords or cookies
- Track user behavior and browsing history
- Open backdoors for remote access or data exfiltration

## 2. What permissions should raise suspicion?
Be cautious of extensions requesting:
- Access to all websites (`Read and change all your data`)
- Clipboard access
- File system access
- Browsing history
- Webcam or microphone access (if not essential)

## 3. How to safely install browser extensions?
- Only use official browser stores (Chrome Web Store, Firefox Add-ons)
- Check reviews and ratings
- Review permissions before installing
- Avoid extensions with vague descriptions or no developer info

## 4. What is extension sandboxing?
Sandboxing isolates an extension’s code from the rest of the browser and system. It limits what the extension can access, reducing the risk of it affecting other tabs, processes, or user data.

## 5. Can extensions steal passwords?
Yes, if an extension has access to page content or form data, it can potentially capture passwords. Malicious extensions may use this to log keystrokes or intercept login forms.

## 6. How to update extensions securely?
- Enable automatic updates in browser settings
- Monitor extension changelogs for suspicious changes
- Re-review permissions after updates
- Remove extensions that suddenly request new, unnecessary access

## 7. Difference between extensions and plugins?
- **Extensions**: Lightweight scripts that modify browser behavior (e.g., ad blockers, translators)
- **Plugins**: External software components (e.g., Flash, Java) that run inside the browser—less common today due to security risks

## 8. How to report malicious extensions?
- Chrome: Use the “Report Abuse” link on the extension’s store page
- Firefox: Click “Report” in the Add-ons Manager
- You can also notify browser support teams or cybersecurity forums
