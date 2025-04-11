# kubera1System Structure
Copy
kubera-system/
├── index.html                 # Common login page
├── css/
│   └── style.css              # Main stylesheet
├── innovator/
│   ├── dashboard.html         # Innovator landing page
│   ├── profile.html           # Innovator profile page
│   └── raise-funding.html     # Raise funding request page
├── investor/
│   ├── dashboard.html         # Investor landing page
│   ├── profile.html           # Investor profile page
│   └── analyze-funding.html   # Analyze funding request page
└── images/                    # For any images used
Navigation Flow
Common Entry Point
Login Page (index.html)

Entry point for all users

Authenticates and redirects to appropriate dashboard based on role

Innovator Flow
Copy
1. Innovator Dashboard (innovator/dashboard.html)
   - View current funding requests
   - Raise new funding request
   - Access profile

2. Raise Funding Request (innovator/raise-funding.html)
   - Submit new funding proposals
   - Return to dashboard when complete

3. Innovator Profile (innovator/profile.html)
   - Edit personal and company information
   - Return to dashboard when complete
Investor Flow
Copy
1. Investor Dashboard (investor/dashboard.html)
   - View funding requests needing attention
   - Click on requests to analyze them
   - Access profile

2. Analyze Funding (investor/analyze-funding.html)
   - Review funding request details
   - Make investment decisions
   - Return to dashboard when complete

3. Investor Profile (investor/profile.html)
   - Edit personal and investment preferences
   - Return to dashboard when complete
Development Setup
Clone the repository

Open index.html in a web browser to start

No server requirements for basic functionality (pure HTML/CSS)

Technical Implementation
HTML Structure
Semantic HTML5 markup

Consistent layout across all pages

Role-based templates

CSS Features
Responsive design foundation

Clean, modern interface

Status indicators with color coding

Consistent styling for forms and tables

JavaScript (To Be Implemented)
Form validation

Dynamic content loading

Interactive elements

Authentication system