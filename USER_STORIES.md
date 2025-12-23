
# Human Musculoskeletal Learning App (HumanMSK)
## User Stories

## Login/registration page

### User Story 1: Account Registration
**As a** new user  
**I want** to create an account using my personal details  
**So that** I can access the Human Musculoskeletal learning app and save my progress  

**Acceptance Criteria**
- User can navigate to the Sign Up screen from the Login page
- User can enter required registration details (e.g., username/email and password)
- Required fields are validated before submission
- Password rules are clearly displayed
- User receives a success message upon successful registration
- User is redirected to the Home page after registration

---

### User Story 2: User Login
**As a** returning user  
**I want** to log in using my credentials  
**So that** I can continue learning where I left off  

**Acceptance Criteria**
- User can enter username/email and password
- Login button is disabled until required fields are filled
- Credentials are validated against stored data
- Successful login redirects the user to the Home page
- Login state persists across app restarts when persistent storage is enabled

---

### User Story 3: Error Feedback for Invalid Credentials
**As a** user  
**I want** clear error feedback when I enter incorrect login information  
**So that** I understand what went wrong and how to fix it  

**Acceptance Criteria**
- Error message appears if username/email does not exist
- Error message appears if password is incorrect
- Error messages are clear, non-technical, and user-friendly
- Sensitive authentication details are not exposed
- User remains on the Login screen after an error
- Input fields remain editable for correction

---

### User Story 4: Input Validation Feedback
**As a** user  
**I want** immediate validation feedback during login and registration  
**So that** I can correct mistakes before submitting  

**Acceptance Criteria**
- Empty required fields show inline validation messages
- Password mismatch during registration is clearly indicated
- Invalid email format is detected (if email is used)
- Validation messages disappear once the input is corrected

---

### User Story 5: Logout
**As a** logged-in user  
**I want** the ability to log out  
**So that** I can protect my account on shared devices  

**Acceptance Criteria**
- Logout option is available in the Settings menu
- User is returned to the Login screen after logout
- Persistent login data is cleared upon logout

## Home Page

### User Story 6: View Welcome Message
**As a** logged-in user  
**I want** to see a welcome message or motivational quote on the Home page  
**So that** I feel encouraged and oriented when I open the app  

**Acceptance Criteria**
- A welcome message is displayed at the top of the Home page
- Message includes the user’s name when available
- Message updates appropriately on each app launch or session
- Welcome content does not block access to main features

---

### User Story 7: View Learning Progress
**As a** user  
**I want** to see my learning progress on the Home page  
**So that** I can track how much of the musculoskeletal content I have completed  

**Acceptance Criteria**
- Progress is displayed visually (e.g., progress bar or percentage)
- Progress reflects completed anatomy modules or lessons
- Progress updates automatically when new content is completed
- Progress data persists across app sessions

---

### User Story 8: View Completed Tasks or Modules
**As a** user  
**I want** to view a list of completed tasks or lessons  
**So that** I can review what I have already learned  

**Acceptance Criteria**
- Completed tasks or modules are clearly labeled
- List shows completion date or status indicator
- Completed items are read-only
- User can navigate from a completed item to review content if desired
