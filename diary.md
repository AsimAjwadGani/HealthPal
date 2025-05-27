**Project Development Diary**

**###Feb 27, 2025**

Started collecting inspiration for Health Pal, focusing on health and wellness platforms.
Decided on the main idea: a centralized UI for health solutions—emergency services, medicine reminders, health tips, and more.
Outlined the key components and features to implement.
Jotted down ideas for the home page

**###Feb 28, 2025**

Created the initial project using Vite and installed React.
Added Tailwind CSS and DaisyUI for rapid UI development.
Set up ESLint, Tailwind, and PostCSS configurations.
Established the core directory structure under src/, including folders for assets and components.
Introduced React Router to manage different pages and views seamlessly.
Prepared a Root.jsx file to serve as the primary layout container.

**###March 01, 2025**

Developed a Navbar.jsx component featuring a pill icon (GiPill) and brand name Health Pal.
Incorporated Register and Login buttons for future authentication flows.
Integrated the Navbar into Root.jsx, ensuring consistent navigation across the app.
Crafted a hero section within Root.jsx, displaying a bold welcome message and subheading.
Added two CTA buttons: Get Started and Learn More.
Included a placeholder image to reinforce the health-centric theme.
Created Feedback.jsx to showcase a list of top health articles, each with title, image, and read-time badge.
Highlighted the first article as a “featured” post and arranged the rest in a grid layout.
Prepared the component for future “Learn More” functionality, which might lead to detailed article pages.
Implemented Footer.jsx with a centered layout and bold cyan background.
Added navigation links (About us, Contact, Jobs) and social media icons for a more polished feel.
Ensured responsiveness across mobile, tablet, and desktop using Tailwind utility classes.

**###March 02, 2025**

Built Services.jsx to list out key offerings like SOS services, medicine reminders, and doctor consultations.
Integrated icons (FaAmbulance, FaStethoscope, CiPill, CiHeart) to visually distinguish each service.
Added a Stats.jsx component to display metrics such as total likes, page views, and client satisfaction—currently visible on larger screens only.
Developed UserSay.jsx to feature user testimonials, complete with avatars, ratings, and location info.
Implemented a star/half-star rating system, ensuring feedback is visually appealing and easy to read.
Integrated all components (Navbar, Services, Feedback, UserSay, Stats, Footer) in Root.jsx.
Confirmed that the site remains responsive across various screen sizes.
Performed minor UI tweaks: consistent color palette, font sizes, and spacing.


**##March 3, 2025**##

Integrated Firebase authentication for login, registration, and logout functionalities.
Implemented form validation for email and password input fields.
Enhanced user feedback for authentication errors (e.g., incorrect credentials, email already in use).

**HCI Principles Applied:**
Error Prevention & User Feedback: Users are notified when they enter incorrect credentials, preventing frustration.

Consistency & Standards: The authentication process follows common UI patterns to ensure users can navigate the login and registration process seamlessly.

**HCI Theories Used:**
Cognitive Load Theory: By reducing the number of actions required for login and registration, the cognitive burden is minimized.

Fitts' Law: The login button is placed in an easily accessible location, reducing the effort needed to interact with it.

**##March 4, 2025**##

Updated the navbar and sidebar menu for easier navigation.
Made the mobile menu more accessible using a responsive drawer menu.
Added hover effects and transition animations for a smoother experience.

**HCI Principles Applied:**
Flexibility & Efficiency of Use: The sidebar menu allows quick access to different sections.

Visibility of System Status: The active page is highlighted in the navbar.

**HCI Theories Used:**
Color Theory: The primary colors were chosen to create contrast and improve readability.

Gestalt Principles: The navbar and sidebar use proximity and similarity to group related elements logically.

**##March 5, 2025**##

Implemented a form for users to add their medicines, including name, quantity, timing, and expiration date.
Allowed file upload for prescription images.
Displayed medicine list with an "Expired" or "Ongoing" status based on expiry date.

**HCI Principles Applied:**

Recognition Rather Than Recall: Users can see their medicine history and don’t have to remember everything.

Affordance: Input fields clearly indicate where the user should enter data.

**HCI Theories Used:**

Distributed Cognition: The system helps users remember their medication schedules.

Color Coding for Readability: Expired medicines appear in red for quick identification.

**##March 6, 2025**##

Designed a user-friendly interface for booking consultations.
Integrated options to select doctors, date, time, and consultation type (virtual or in-person).
Created a "Join Live Consultation" button for upcoming appointments.
**HCI Principles Applied:**

Match Between System & Real World: Users can select a date and time in an intuitive calendar format.

User Control & Freedom: Users can cancel or reschedule consultations easily.

**HCI Theories Used:**

Mental Models: The appointment booking flow mimics real-world scheduling processes.

Gestalt Principle of Continuity: The layout guides users through the booking process naturally.

**##March 7, 2025**##

Developed a dedicated SOS page for calling an ambulance with a single click.
Implemented an alert confirming the user's request before sending.
Displayed a history of previous SOS calls.

**HCI Principles Applied:**

Visibility of System Status: Users get confirmation that their SOS request has been received.

Error Prevention: Added a confirmation step to avoid accidental emergency calls.

**HCI Theories Used:**

Fitts’ Law: The SOS button is large and centrally placed for quick access in emergencies.

Contrast & Readability: The emergency button uses high-contrast colors to grab attention.

**##March 8, 2025**##

Developed a profile page where users can edit their name, height, weight, and update profile pictures.
Implemented local storage for name persistence.
Added an option to display the user's initials in a default profile picture.

**HCI Principles Applied:**

User Control & Freedom: Users can update their personal details at any time.

Flexibility & Customization: Users can personalize their profile for a more tailored experience.

**HCI Theories Used:**

Personalization Theory: Allows users to feel more engaged with the system.

User Mental Models: A profile system that behaves similarly to common social platforms.

**##March 9, 2025**##

Integrated a section with expert health articles.
Added "Read Time" and author information to each article.
Featured the most popular article with an enlarged display.

**HCI Principles Applied:**

Aesthetic & Minimalist Design: Kept the interface clean to encourage reading.

Recognition Rather Than Recall: Users can scan articles without clicking through multiple pages.

**HCI Theories Used:**

Cognitive Load Reduction: Articles are presented in digestible sections.

Gestalt Principles: The featured article is visually distinct, guiding user attention.

**##March 10, 2025**##

Designed a "What Our Users Say" section displaying testimonials.
Added star ratings and country flags for authenticity.

**HCI Principles Applied:**

Social Proof: Encourages user trust by showing real user experiences.

Feedback & Visibility: Star ratings provide a quick understanding of overall satisfaction.

**HCI Theories Used:**

Trust & Credibility Theory: User testimonials enhance credibility.

Color Psychology: Soft colors for background contrast to make reviews more readable.

**##March 11, 2025**##

Added a stats section showing page views, total likes, and user satisfaction percentage.
Integrated dynamic numbers that update over time.

**HCI Principles Applied:**

Feedback & System Visibility: Users see real-time stats reflecting engagement.

Aesthetic & Minimalist Design: Stats are displayed in a simple, readable format.

**HCI Theories Used:**

Cognitive Load Theory: Avoided unnecessary elements to keep focus on key metrics.

Gestalt Principle of Similarity: All stat elements share a uniform design.

**##March 12, 2025**##

Optimized responsiveness for mobile screens.
Adjusted padding, margins, and font sizes for better readability.
Conducted user testing for feedback on usability.

**HCI Principles Applied:**

Usability Testing: Addressed user concerns about navigation and clarity.

Consistency & Standards: Ensured UI elements followed a uniform style.

**HCI Theories Used:**

Color Theory: Finalized contrast ratios for accessibility.

User-Centered Design: Iterated based on user feedback for final improvements.



