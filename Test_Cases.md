# 📋 KRIDA - Test Cases

**Project:** KRIDA Manual Testing  
**Tester:** Sandeep  
**Date:** April 2026  
**Total Test Cases:** 10  

---

## TC_001 - Verify Homepage Loads Correctly

| Field | Details |
|-------|---------|
| **Module** | Homepage |
| **Priority** | High |
| **Status** | ✅ Pass |

**Test Steps:**
1. Open https://krida-frontend-onkp.vercel.app/
2. Observe the page loading

**Expected Result:** Homepage loads with logo, navbar, and content without errors  
**Actual Result:** Homepage loaded correctly with all elements visible

---

## TC_002 - Verify All Navigation Links Work

| Field | Details |
|-------|---------|
| **Module** | Navigation |
| **Priority** | High |
| **Status** | ✅ Pass |

**Test Steps:**
1. Open the website
2. Click each link in the navbar one by one
3. Observe if they navigate to correct pages

**Expected Result:** All navbar links navigate to the correct pages  
**Actual Result:** All navigation links worked correctly

---

## TC_003 - Verify Search Venue Functionality

| Field | Details |
|-------|---------|
| **Module** | Search |
| **Priority** | High |
| **Status** | ✅ Pass |

**Test Steps:**
1. Open the website
2. Locate the search bar
3. Type a sport or venue name
4. Click Search or press Enter

**Expected Result:** Relevant venues appear in search results  
**Actual Result:** Search returned correct results

---

## TC_004 - Verify Book a Venue Works

| Field | Details |
|-------|---------|
| **Module** | Booking |
| **Priority** | Critical |
| **Status** | ✅ Pass |

**Test Steps:**
1. Open the website
2. Search or browse for a venue
3. Click on a venue
4. Click "Book Now"
5. Select a time slot
6. Confirm booking

**Expected Result:** Booking is confirmed and user gets a confirmation  
**Actual Result:** Booking flow worked as expected

---

## TC_005 - Verify Login with Valid Credentials

| Field | Details |
|-------|---------|
| **Module** | Login |
| **Priority** | Critical |
| **Status** | ✅ Pass |

**Test Steps:**
1. Open the website
2. Click "Login"
3. Enter valid email and password
4. Click "Login" button

**Expected Result:** User is logged in and redirected to dashboard  
**Actual Result:** Login was successful

---

## TC_006 - Verify Login with Invalid Credentials

| Field | Details |
|-------|---------|
| **Module** | Login |
| **Priority** | High |
| **Status** | ✅ Pass |

**Test Steps:**
1. Open the website
2. Click "Login"
3. Enter wrong email and wrong password
4. Click "Login" button

**Expected Result:** An error message should appear — "Invalid credentials"  
**Actual Result:** Appropriate error handling observed

---

## TC_007 - Verify Sign Up with New Account

| Field | Details |
|-------|---------|
| **Module** | Sign Up |
| **Priority** | High |
| **Status** | ✅ Pass |

**Test Steps:**
1. Open the website
2. Click "Sign Up" or "Register"
3. Fill in name, email, and password
4. Click "Create Account"

**Expected Result:** Account is created and user is redirected  
**Actual Result:** Sign up completed successfully

---

## TC_008 - Verify Website on Mobile Screen

| Field | Details |
|-------|---------|
| **Module** | Responsiveness |
| **Priority** | Medium |
| **Status** | ✅ Pass |

**Test Steps:**
1. Open the website on Chrome
2. Press F12 to open DevTools
3. Click the mobile/tablet icon (Toggle Device Toolbar)
4. Select a mobile device (e.g., iPhone 12)
5. Observe the layout

**Expected Result:** Website is responsive and looks good on mobile  
**Actual Result:** Website was responsive on mobile view

---

## TC_009 - Verify All Images Load Correctly

| Field | Details |
|-------|---------|
| **Module** | UI / Images |
| **Priority** | Medium |
| **Status** | ✅ Pass |

**Test Steps:**
1. Open the website
2. Navigate through all pages
3. Check every image on each page

**Expected Result:** All images load without broken icons or placeholder boxes  
**Actual Result:** All images loaded correctly on all pages

---

## TC_010 - Verify Footer Links Work

| Field | Details |
|-------|---------|
| **Module** | Footer |
| **Priority** | Low |
| **Status** | ✅ Pass |

**Test Steps:**
1. Open the website
2. Scroll to the bottom (footer)
3. Click each link in the footer

**Expected Result:** All footer links navigate to correct pages  
**Actual Result:** All footer links worked correctly

---

## 📊 Summary

| Total | Pass | Fail | Pass Rate |
|-------|------|------|-----------|
| 10 | 10 ✅ | 0 | 100% |
