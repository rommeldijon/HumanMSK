
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

## Menu & Navigation

### User Story 9: Access Menu Options
**As a** user  
**I want** to access a menu from anywhere in the app  
**So that** I can easily navigate between different sections  

**Acceptance Criteria**
- Menu is accessible from all main screens
- Menu opens and closes smoothly
- Menu displays clearly labeled navigation options
- Current active screen is visually indicated

---

### User Story 10: Navigate to Profile
**As a** user  
**I want** to navigate to my profile from the menu  
**So that** I can view and manage my personal information  

**Acceptance Criteria**
- Profile option is visible in the menu
- Selecting Profile navigates to the Profile screen
- Profile screen displays user-specific information
- Navigation does not reset app state unnecessarily

---

### User Story 11: Return to Home Page
**As a** user  
**I want** to return to the Home page using the menu  
**So that** I can quickly access my learning overview  

**Acceptance Criteria**
- Home option is available in the menu
- Selecting Home navigates to the Home page
- Home page loads without data loss
- Navigation transition is consistent with the rest of the app

---

## Menu & Navigation

### User Story 9: Access Menu Options
**As a** user  
**I want** to access a menu from anywhere in the app  
**So that** I can easily navigate between different sections  

**Acceptance Criteria**
- Menu is accessible from all main screens
- Menu opens and closes smoothly
- Menu displays clearly labeled navigation options
- Current active screen is visually indicated

---

### User Story 10: Navigate to Profile
**As a** user  
**I want** to navigate to my profile from the menu  
**So that** I can view and manage my personal information  

**Acceptance Criteria**
- Profile option is visible in the menu
- Selecting Profile navigates to the Profile screen
- Profile screen displays user-specific information
- Navigation does not reset app state unnecessarily

---

### User Story 11: Return to Home Page
**As a** user  
**I want** to return to the Home page using the menu  
**So that** I can quickly access my learning overview  

**Acceptance Criteria**
- Home option is available in the menu
- Selecting Home navigates to the Home page
- Home page loads without data loss
- Navigation transition is consistent with the rest of the app

---

## Menu & Navigation

### User Story 9: Access Menu Options
**As a** user  
**I want** to access a menu from anywhere in the app  
**So that** I can easily navigate between different sections  

**Acceptance Criteria**
- Menu is accessible from all main screens
- Menu opens and closes smoothly
- Menu displays clearly labeled navigation options
- Current active screen is visually indicated

---

### User Story 10: Navigate to Profile
**As a** user  
**I want** to navigate to my profile from the menu  
**So that** I can view and manage my personal information  

**Acceptance Criteria**
- Profile option is visible in the menu
- Selecting Profile navigates to the Profile screen
- Profile screen displays user-specific information
- Navigation does not reset app state unnecessarily

---

### User Story 11: Return to Home Page
**As a** user  
**I want** to return to the Home page using the menu  
**So that** I can quickly access my learning overview  

**Acceptance Criteria**
- Home option is available in the menu
- Selecting Home navigates to the Home page
- Home page loads without data loss
- Navigation transition is consistent with the rest of the app

---

## Detailed Content Screen

### User Story 12: View Detailed Content Information
**As a** user  
**I want** to view detailed information about a musculoskeletal topic  
**So that** I can better understand the anatomy or concept being presented  

**Acceptance Criteria**
- Detailed screen displays a clear title for the topic
- Screen includes descriptive content (text, images, or diagrams)
- Content is readable and well-structured
- User can scroll through longer content if necessary

---

### User Story 13: View Instructions or Task Description
**As a** user  
**I want** to see instructions or an explanation of the task on the detailed screen  
**So that** I know what I am expected to learn or complete  

**Acceptance Criteria**
- Instructions are clearly visible on the detailed screen
- Instructions explain the purpose of the task or content
- Instructions are concise and easy to understand
- User can revisit instructions at any time on the screen

## Profile Page

### User Story 14: View Profile Information
**As a** logged-in user  
**I want** to view my personal account information  
**So that** I can review the details associated with my account  

**Acceptance Criteria**
- Profile screen displays user information (e.g., name, username/email)
- Information shown reflects the most recently saved data
- Profile information is read-only by default
- Profile data loads securely and efficiently

---

### User Story 15: Edit Profile Information
**As a** user  
**I want** to edit my personal registration details  
**So that** I can keep my account information up to date  

**Acceptance Criteria**
- User can enter an edit mode from the Profile screen
- Editable fields are clearly indicated
- Input validation is applied to updated fields
- User can save or cancel changes
- Updated information is persisted across app sessions
- User receives feedback upon successful update

## Tasks & Progress Management

### User Story 16: Add New Tasks
**As a** user  
**I want** to add new learning tasks or activities  
**So that** I can organize what I plan to study or complete  

**Acceptance Criteria**
- User can create a new task from the Tasks screen
- Task includes a title and optional description
- Task is added to the active task list
- Newly added tasks are saved persistently
- User receives confirmation when a task is created

---

### User Story 17: Delete Tasks
**As a** user  
**I want** to delete tasks I no longer need  
**So that** I can keep my task list organized  

**Acceptance Criteria**
- User can select a task to delete
- System requests confirmation before deletion
- Deleted task is removed from the list immediately
- Deleted task does not reappear after app restart

---

### User Story 18: Reorder or Move Tasks
**As a** user  
**I want** to reorder or move tasks within my task list  
**So that** I can prioritize my learning activities  

**Acceptance Criteria**
- User can move tasks up or down in the list
- Task order updates immediately in the UI
- Task order is saved persistently
- Reordering does not affect task content

---

### User Story 19: Personalize Tasks
**As a** user  
**I want** to personalize my tasks  
**So that** they match my learning preferences and goals  

**Acceptance Criteria**
- User can customize task details (e.g., notes, priority, tags)
- Personalized attributes are displayed with the task
- Changes to tasks are saved persistently
- User can update or remove personalization at any time

---

### User Story 20: Track Task Completion
**As a** user  
**I want** to mark tasks as completed  
**So that** I can track my learning progress  

**Acceptance Criteria**
- User can mark a task as completed
- Completed tasks are visually distinguished
- Completion status updates progress indicators
- Completed tasks remain accessible for review
