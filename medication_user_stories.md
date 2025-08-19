
# **User Stories – Habit Tracker App**

## **Exercise 1: Account Registration**
**Description:**  
As a user, I want to register with my name, username, age, and country so that I can create an account and access the habit tracking features.  

**Acceptance Criteria:**  
- The registration form includes fields for name, username, age, and country  
- The **Sign Up** button is disabled until all required fields are filled  
- A new account is created when valid details are submitted  
- A success message or redirect occurs upon successful registration  

**Priority:** High  
**Story Points:** 5  


## **Exercise 2: Account Login**
**Description:**  
As a user, I want to log in using my username and password so that I can access my account and track my habits.  

**Acceptance Criteria:**  
- The login form includes fields for username and password  
- The **Login** button is disabled until both fields are filled  
- User is redirected to the home screen on successful login  
- An error message is displayed if login credentials are invalid  

**Priority:** High  
**Story Points:** 3  


## **Exercise 3: Error Feedback on Login**
**Description:**  
As a user, I want to receive a message if I enter the wrong username or password so that I know my login attempt was unsuccessful.  

**Acceptance Criteria:**  
- An error message is displayed if the username or password is incorrect  
- Error messages are clear and informative (e.g., “Invalid credentials”)  
- Error message disappears once corrected input is provided  
- Login attempt is blocked until correct details are entered  

**Priority:** High  
**Story Points:** 3  


## **Exercise 4: Home Screen**
**Story: Overview at a Glance**  
**Description:**  
As a user, I want to view an overview of my data on the home screen so that I can monitor my progress at a glance.  

**Acceptance Criteria:**  
- Home screen displays summary of progress (e.g., steps/water/habits)  
- Data refreshes automatically on app load  
- Users see a motivational/welcome message  

**Priority:** High  
**Story Points:** 4  

**Story: Intro Guide for New Users**  
**Description:**  
As a new user, I want to see a quick introductory guide on the home screen so that I can learn how to use the app.  

**Acceptance Criteria:**  
- Intro guide/tutorial is displayed for first-time users  
- Option to skip or dismiss the guide is available  
- Guide does not reappear after first use unless reset  

**Priority:** Medium  
**Story Points:** 3  

**Story: Quick Access to Most‑Used Features**  
**Description:**  
As a user, I want to access my most-used features from the home screen so that I can navigate the app efficiently.  

**Acceptance Criteria:**  
- Shortcuts are displayed for commonly used features  
- Shortcuts update based on usage patterns  
- Tapping a shortcut navigates directly to the feature  

**Priority:** High  
**Story Points:** 5  


## **Exercise 5: Detail Screen**
**Story: See Detailed Info**  
**Description:**  
As a user, I want detailed information on a selected item so that I can make informed decisions.  

**Acceptance Criteria:**  
- Detail screen shows images, description, progress, etc.  
- Information matches the selected item  
- Layout is optimized for mobile and tablet  

**Priority:** High  
**Story Points:** 5  

**Story: Save/Share from Detail**  
**Description:**  
As a user, I want to perform actions like saving or sharing an item from the detail screen so that I can share interesting content.  

**Acceptance Criteria:**  
- Buttons available for **Save** and **Share**  
- **Save** adds the item to the user’s list  
- **Share** opens system share options  

**Priority:** Medium  
**Story Points:** 3  

**Story: Related Items**  
**Description:**  
As a user, I want to view related items on the detail screen so that I can explore more options.  

**Acceptance Criteria:**  
- Related items are displayed below the details  
- Tapping a related item opens its detail screen  
- Recommendations are relevant and dynamic  

**Priority:** Medium  
**Story Points:** 3  


## **Exercise 6: Persistent Data**
**Story: Persist Login State**  
**Description:**  
As a user, I want my data like login state to persist across sessions so that I don't need to re-enter details every time.  

**Acceptance Criteria:**  
- User session remains active after app restart  
- Session persists until user logs out  
- Expired sessions redirect to login  

**Priority:** High  
**Story Points:** 4  

**Story: Persist Preferences**  
**Description:**  
As a user, I want to save my preferences such as dark mode so that the app remembers my settings.  

**Acceptance Criteria:**  
- Theme/language/font size persist across sessions  
- Changing preferences updates UI instantly  
- Preferences stored securely  

**Priority:** Medium  
**Story Points:** 3  

**Story: Persist Activity Logs (Admin)**  
**Description:**  
As an admin, I want user activity logs to persist so that I can track and analyze trends over time.  

**Acceptance Criteria:**  
- Logins, habit completions, and key events are logged  
- Logs persist across app updates  
- Data accessible for reporting/analytics  

**Priority:** Medium  
**Story Points:** 5  


## **Exercise 7: External API**
**Story: Real‑Time Weather**  
**Description:**  
As a user, I want to view real-time weather updates on the home screen so that I can plan my day effectively.  

**Acceptance Criteria:**  
- Weather API integrated with the home screen  
- Shows temperature, condition, and icon  
- Updates based on location  

**Priority:** Medium  
**Story Points:** 5  

**Story: Live Currency Conversion**  
**Description:**  
As a user, I want to see live currency conversion rates when making purchases so that I can make informed financial decisions.  

**Acceptance Criteria:**  
- Currency API fetches live exchange rates  
- Prices displayed in the user’s preferred currency  
- Data updates in real time  

**Priority:** Medium  
**Story Points:** 5  

**Story: Nearby Restaurants on Map**  
**Description:**  
As a user, I want to see nearby restaurants on a map so that I can choose a dining location conveniently.  

**Acceptance Criteria:**  
- Maps API integrated with nearby markers  
- Tapping a marker shows details  
- Option to open directions  

**Priority:** Low  
**Story Points:** 8  


## **Exercise 8: Settings Menu**
**Story: Access from Any Screen**  
**Description:**  
As a user, I want to access a settings menu from any screen so that I can adjust preferences at my convenience.  

**Acceptance Criteria:**  
- Settings icon shown across screens  
- Tapping opens the settings menu  
- Navigates to detailed settings screen  

**Priority:** High  
**Story Points:** 3  

**Story: Categorized Sections**  
**Description:**  
As a user, I want to see categorized sections in the settings menu so that I can quickly find the options I need.  

**Acceptance Criteria:**  
- Categories like Profile, Notifications, Data Sync, Theme  
- Options grouped logically  
- Categories can expand/collapse  

**Priority:** Medium  
**Story Points:** 4  

**Story: Admin Controls**  
**Description:**  
As an admin, I want to enable or disable certain settings for users so that I can maintain app security and compliance.  

**Acceptance Criteria:**  
- Admin can toggle availability of settings  
- Disabled settings are hidden or grayed out  
- Restrictions apply immediately to users  

**Priority:** High  
**Story Points:** 5  


## **Exercise 9: Settings Screen**
**Story: Enable Dark Mode**  
**Description:**  
As a user, I want to enable dark mode in the settings screen so that I can reduce eye strain during nighttime usage.  

**Acceptance Criteria:**  
- Dark mode toggle in **Appearance**  
- Theme updates immediately  
- Preference persists across sessions  

**Priority:** Medium  
**Story Points:** 3  

**Story: Notification Preferences**  
**Description:**  
As a user, I want to adjust notification preferences so that I only receive alerts relevant to me.  

**Acceptance Criteria:**  
- Toggles per category (reminders, promotions, updates)  
- Master switch to enable/disable all  
- Preferences saved and applied immediately  

**Priority:** Medium  
**Story Points:** 4  

**Story: Update Email & Password**  
**Description:**  
As a user, I want to update my email and password on the settings screen so that I can keep my account secure.  

**Acceptance Criteria:**  
- Editable email/password fields with validation  
- Strong password rules enforced  
- Success message and immediate credential update  

**Priority:** High  
**Story Points:** 5  


## **Exercise 10: Notifications**
**Story: Daily Reminder**  
**Description:**  
As a user, I want to receive a daily reminder notification so that I don’t forget to complete my tasks.  

**Acceptance Criteria:**  
- Daily notification scheduled at a set/preferred time  
- User can enable/disable in settings  
- Tapping opens tasks screen  

**Priority:** High  
**Story Points:** 4  

**Story: New Features Alert**  
**Description:**  
As a user, I want to receive notifications about new features so that I can explore and benefit from them.  

**Acceptance Criteria:**  
- Sent when new features release  
- Includes link to feature page  
- User can disable feature alerts  

**Priority:** Medium  
**Story Points:** 3  

**Story: Disable Promotional Notifications**  
**Description:**  
As a user, I want to turn off promotional notifications so that I can focus on essential updates only.  

**Acceptance Criteria:**  
- Toggle to disable promotions (keeps critical alerts)  
- No promotional notifications delivered when off  
- Preference persists across sessions  

**Priority:** High  
**Story Points:** 4  

**Story: Admin Targeted Messaging**  
**Description:**  
As an admin, I want to send notifications to specific user groups so that I can target them with relevant information.  

**Acceptance Criteria:**  
- Admin can choose user groups via filters  
- Messages delivered only to selected groups  
- Preview/schedule options and delivery logs available  

**Priority:** Medium  
**Story Points:** 5  
