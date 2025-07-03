# Elevate-labs-task-7 - cybersecurity internship
# 🔐 Identify and Remove Suspicious Browser Extensions


## 🧠 Objective:
 A simple browser hygiene project focused on identifying and removing suspicious or potentially harmful extensions to improve browser security and performance.

The purpose of this project is to:

* Audit installed browser extensions
* Evaluate their safety based on permissions, reviews, and source
* Remove extensions that pose privacy, security, or performance risks

This exercise enhances user awareness about common threats hidden in browser add-ons and promotes better digital hygiene.

---

## 🛠️ Tools Used

* **Browser:** Google Chrome
  *(This guide also applies to Firefox with slight interface differences.)*
* **Other Resources:**

  * Chrome Web Store
  * Google Search (for reputation checks)
  * Extension permission details

---

## 📋 Steps Followed

### 1. Open Extension Manager

* Chrome: Navigate to `chrome://extensions/`
* Firefox: Navigate to `about:addons`

### 2. Review Installed Extensions

* Check each extension’s:

  * Name & Publisher
  * Purpose
  * Permissions
  * User reviews
  * Installation source

### 3. Identify Suspicious Extensions

Flagged extensions that:

* Have vague or no publisher information
* Request excessive permissions (e.g., read all data on websites)
* Cause pop-ups, redirects, or change browser settings
* Have poor or mixed user reviews

### 4. Remove Problematic Extensions

* Uninstalled suspicious or unused extensions
* Restarted browser to apply changes

---

## 🗃️ Extensions Review (Sample)

| Extension Name    | Publisher     | Purpose               | Permissions               | Status    |
| ----------------- | ------------- | --------------------- | ------------------------- | --------- |
| Grammarly         | grammarly.com | Writing assistant     | Access site data          | ✅ Kept    |
| uBlock Origin     | Raymond Hill  | Ad blocker            | Modify content            | ✅ Kept    |
| PDF Converter Pro | Unknown       | Converts files to PDF | Read all data on websites | ❌ Removed |
| Weather Live      | Unknown       | Local weather updates | Access tabs, location     | ❌ Removed |

---

## ✅ Results

* **Extensions Before:** 5
* **Extensions Removed:** 2
* **Extensions After:** 3

### Improvements:

* Better browser performance
* Reduced pop-ups and intrusive ads
* Higher confidence in privacy and security

---

## ⚠️ Why It Matters

Malicious browser extensions can:

* Steal sensitive data (passwords, browsing history)
* Inject ads or phishing content
* Track users across websites
* Slow down browser performance

---

## 💡 Recommendations

* Review extensions monthly
* Install only from trusted sources
* Check permissions before adding
* Remove unused extensions immediately
* Stay updated on browser security practices

---

## 📚 References

* [Google Chrome Extension Safety Tips](https://support.google.com/chrome_webstore/answer/2664769)
* [How to Check Browser Extension Permissions](https://developer.chrome.com/docs/extensions/mv3/permissions/)
* [Mozilla Add-ons Review Guidelines](https://extensionworkshop.com/documentation/publish/add-on-review-process/)
