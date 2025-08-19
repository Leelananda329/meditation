# **User Stories – Medication Tracking App**

---

## **Exercise 1: Account Registration**
**Description:**  
As a user, I want to register by entering my name, email, password, and age so that I can create an account and securely track my medications.  

**Acceptance Criteria:**  
- Registration form includes fields: name, email, password, and age  
- **Sign Up** button is disabled until all required fields are completed  
- A new account is created when valid details are submitted  
- A success message or redirect occurs upon successful registration  

**Priority:** High  
**Story Points:** 5  

---

## **Exercise 2: Account Login**
**Description:**  
As a user, I want to log in using my email and password so that I can access my personalized medication records.  

**Acceptance Criteria:**  
- Login form includes fields for email and password  
- **Login** button is disabled until both fields are filled  
- Redirects user to the home screen upon successful login  
- Displays error if login credentials are invalid  

**Priority:** High  
**Story Points:** 3  

---

## **Exercise 3: Error Feedback on Login**
**Description:**  
As a user, I want to receive an error message if I enter the wrong email or password so that I know my login attempt was unsuccessful.  

**Acceptance Criteria:**  
- Clear error message displayed for invalid credentials (e.g., "Incorrect email or password")  
- Error disappears once corrected input is provided  
- Login attempt is blocked until correct details are entered  

**Priority:** High  
**Story Points:** 3  

---

## **Exercise 4: Home Screen**
**Story: Medication Overview**  
**Description:**  
As a user, I want to see my daily medication schedule and progress on the home screen so that I can track what to take at a glance.  

**Acceptance Criteria:**  
- Displays list of medications due today with dosage and times  
- Shows status (taken, missed, pending)  
- Updates in real-time  

**Priority:** High  
**Story Points:** 5  

**Story: Intro Guide for New Users**  
**Description:**  
As a new user, I want to see a quick tutorial on how to log medications so that I understand how to use the app effectively.  

**Acceptance Criteria:**  
- A tutorial is shown on first login  
- Option to skip or revisit later  
- Tutorial is not shown again unless reset  

**Priority:** Medium  
**Story Points:** 3  

**Story: Quick Access Shortcuts**  
**Description:**  
As a user, I want to quickly access my medication history and upcoming reminders from the home screen so that I can navigate efficiently.  

**Acceptance Criteria:**  
- Shortcuts displayed for **Medication History** and **Reminders**  
- Tapping navigates directly to the respective screen  
- Most used shortcuts are highlighted  

**Priority:** High  
**Story Points:** 4  

---

## **Exercise 5: Detail Screen**
**Story: View Medication Details**  
**Description:**  
As a user, I want detailed information about each medication so that I can understand dosage, frequency, and purpose.  

**Acceptance Criteria:**  
- Displays name, dosage, frequency, prescribing doctor, and notes  
- Medication image or icon shown  
- Data matches prescription details  

**Priority:** High  
**Story Points:** 5  

**Story: Save/Share Medication Info**  
**Description:**  
As a user, I want to share my medication details with a caregiver so that they can help me manage my routine.  

**Acceptance Criteria:**  
- Share option opens system share dialog  
- Details exported as text or PDF  
- Saved in "My Medications" list when bookmarked  

**Priority:** Medium  
**Story Points:** 4  

**Story: Related Information**  
**Description:**  
As a user, I want to view related information such as potential side effects or interactions so that I can make informed choices.  

**Acceptance Criteria:**  
- Related side effects and warnings shown on detail screen  
- Safe medication alternatives suggested if available  
- Tapping opens related detail  

**Priority:** Medium  
**Story Points:** 4  

---

## **Exercise 6: Persistent Data**
**Story: Persist Login State**  
**Description:**  
As a user, I want my login state to persist so that I don’t need to log in every time I open the app.  

**Acceptance Criteria:**  
- User stays logged in unless they log out  
- Secure session stored on device  
- Expired sessions prompt for re-login  

**Priority:** High  
**Story Points:** 4  

**Story: Persist Medication Preferences**  
**Description:**  
As a user, I want my medication schedules and preferences to persist so that I don’t have to re-enter them.  

**Acceptance Criteria:**  
- Schedules and reminders saved locally/cloud  
- Settings like notification sound persist  
- Updates sync across devices if logged in  

**Priority:** High  
**Story Points:** 5  

**Story: Admin Activity Logs**  
**Description:**  
As an admin, I want to track user medication adherence logs so that I can analyze health patterns.  

**Acceptance Criteria:**  
- Records of taken/missed medications are logged  
- Data exportable for reports  
- Logs persist across updates  

**Priority:** Medium  
**Story Points:** 5  

---

## **Exercise 7: External API**
**Story: Weather API Integration**  
**Description:**  
As a user, I want to see weather info (e.g., humid or dry) on the home screen so that I can understand its effect on my condition.  

**Acceptance Criteria:**  
- Weather API integrated with current location  
- Displays temperature and condition  
- Updates periodically  

**Priority:** Medium  
**Story Points:** 4  

**Story: Pharmacy Locator**  
**Description:**  
As a user, I want to see nearby pharmacies on a map so that I can refill my prescription conveniently.  

**Acceptance Criteria:**  
- Uses Google Maps API to show pharmacies nearby  
- Distance and contact info displayed  
- Directions available  

**Priority:** High  
**Story Points:** 6  

**Story: Drug Info API**  
**Description:**  
As a user, I want drug interaction info from an external API so that I can avoid dangerous combinations.  

**Acceptance Criteria:**  
- API fetches interaction data  
- Warnings shown if potential interaction exists  
- User alerted in real-time  

**Priority:** High  
**Story Points:** 7  

---

## **Exercise 8: Settings Menu**
**Story: Access from Any Screen**  
**Description:**  
As a user, I want to access the settings menu anytime so that I can update my preferences easily.  

**Acceptance Criteria:**  
- Settings icon available on all screens  
- Tapping opens settings menu  
- Menu is consistent in layout  

**Priority:** High  
**Story Points:** 3  

**Story: Categorized Settings**  
**Description:**  
As a user, I want settings grouped into categories (Notifications, Profile, Data Sync) so that I can find them easily.  

**Acceptance Criteria:**  
- Clear categories with labels  
- Easy navigation to each section  
- Collapsible sections  

**Priority:** Medium  
**Story Points:** 3  

**Story: Admin Restrictions**  
**Description:**  
As an admin, I want to restrict users from changing certain settings so that app security is maintained.  

**Acceptance Criteria:**  
- Admin can lock settings (e.g., data sync)  
- Restricted options are hidden or disabled  
- Changes reflect immediately  

**Priority:** High  
**Story Points:** 5  

---

## **Exercise 9: Settings Screen**
**Story: Dark Mode**  
**Description:**  
As a user, I want to enable dark mode so that I can reduce eye strain at night.  

**Acceptance Criteria:**  
- Toggle for dark mode in settings  
- Applies immediately across screens  
- Preference saved for future sessions  

**Priority:** Medium  
**Story Points:** 3  

**Story: Notification Preferences**  
**Description:**  
As a user, I want to control which medication reminders I receive so that I avoid unnecessary alerts.  

**Acceptance Criteria:**  
- Enable/disable reminders for specific medications  
- Choose frequency (daily, weekly)  
- Saved preferences persist  

**Priority:** High  
**Story Points:** 4  

**Story: Update Account Details**  
**Description:**  
As a user, I want to update my email and password so that my account stays secure.  

**Acceptance Criteria:**  
- Editable fields with validation  
- Strong password rules enforced  
- Confirmation message shown after update  

**Priority:** High  
**Story Points:** 5  

---

## **Exercise 10: Notifications**
**Story: Daily Medication Reminder**  
**Description:**  
As a user, I want to receive notifications when it’s time to take my medication so that I don’t miss a dose.  

**Acceptance Criteria:**  
- Notifications triggered at scheduled times  
- Shows medication name and dosage  
- Opens medication detail when tapped  

**Priority:** High  
**Story Points:** 5  

**Story: New Feature Updates**  
**Description:**  
As a user, I want to receive notifications about new features so that I can benefit from them.  

**Acceptance Criteria:**  
- Notification sent on feature release  
- Includes link to explore feature  
- User can disable feature notifications  

**Priority:** Medium  
**Story Points:** 3  

**Story: Turn Off Promotional Notifications**  
**Description:**  
As a user, I want to disable promotional alerts so that I only receive important reminders.  

**Acceptance Criteria:**  
- Toggle for promotional notifications in settings  
- Only medication-related reminders remain active  
- Preference saved  

**Priority:** High  
**Story Points:** 4  

**Story: Admin Targeted Notifications**  
**Description:**  
As an admin, I want to send notifications to specific patient groups so that I can deliver relevant health updates.  

**Acceptance Criteria:**  
- Admin can select patient groups  
- Notifications targeted and logged  
- Delivery status visible to admin  

**Priority:** Medium  
**Story Points:** 5  
