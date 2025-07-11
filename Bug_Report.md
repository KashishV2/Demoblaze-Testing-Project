# 🐞 Bug Reports – Demoblaze E-commerce Website

All valid bugs discovered during manual testing of the [Demoblaze site](https://www.demoblaze.com), documented with reproduction steps and suggestions.

---

## 🐞 Bug 1: Missing "Forgot Password" Option on Login Page

**Module:** Login  
**Reported By:** Kashish Varshney  
**Date:** 11/07/2025  
**Severity:** Medium  
**Priority:** Medium  
**Bug Type:** UI/UX

### 🔍 Description:
The "Forgot Password?" link is missing from the login modal. This affects users who have forgotten their password and want to reset it.

### ✅ Steps to Reproduce:
1. Go to the website: [https://www.demoblaze.com](https://www.demoblaze.com)
2. Click on the **"Log in"** button in the top navbar
3. Observe the login popup

### 🧪 Expected Result:
There should be a **"Forgot Password?"** link below the login fields.

### ❌ Actual Result:
No "Forgot Password?" link is present on the login modal.

### 📸 Screenshot:
<img width="1920" height="1020" alt="Missing Forgot Password" src="https://github.com/user-attachments/assets/c6761ff5-040f-4af6-bdb4-da9ba204be2f" />

### 🔁 Reproducible:
Yes – happens every time.

### 💡 Suggestion:
Add a "Forgot Password" link for better UX and accessibility.

---

## 🐞 Bug 2: Broken Media in "About Us" Section

**Module:** About Us  
**Reported By:** Kashish Varshney  
**Date:** 11/07/2025  
**Severity:** Low  
**Priority:** Medium  
**Bug Type:** UI/Content

### 🔍 Description:
When clicking "About us", the media content fails to load, and an error is displayed instead.

### ✅ Steps to Reproduce:
1. Go to [https://www.demoblaze.com](https://www.demoblaze.com)
2. Click on **“About us”** in the top menu
3. A popup opens with a broken video frame

### 🧪 Expected Result:
A working media (video or animation) should display

### ❌ Actual Result:
The following error is shown:
> "The media could not be loaded, either because the server or network failed or because the format is not supported."

### 📸 Screenshot:
Add image here from: `/screenshots/TC_015_AboutUs_MediaError.png`

### 🔁 Reproducible:
Yes – consistently occurs on every visit

### 💡 Suggestion:
- Check media path or URL
- Use fallback content or proper format support
