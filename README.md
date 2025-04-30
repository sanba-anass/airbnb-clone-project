# airbnb-clone-project

## Project Description

This project is a full-stack clone of the popular accommodation booking platform AirBnB. The goal is to build a functional web application that allows users to browse property listings, view detailed property information, and complete bookings. The project will cover frontend development, backend APIs, database design, and deployment.

## Tech Stack

    Frontend: HTML, CSS, JavaScript (React or similar framework)
    Version Control: Git and GitHub
    Design Tools: Figma for UI/UX design
    

## Design Goals:
User-Centric Design:
Simple, intuitive UI for guests and hosts with seamless navigation.

Responsive Interface:
Fully functional across devices (desktop, tablet, mobile).

Secure Transactions:
Ensure safe payments and data protection (SSL, authentication).

Scalable Architecture:
Allow growth in listings, users, and features without degrading performance.

Real-Time Communication:
Enable messaging and booking updates instantly.

Trust & Verification:
Build trust via reviews, ratings, and verified profiles.

## Key Features

For Guests:
User Registration/Login (Email, Google, Facebook)

Search & Filters (Location, date, guests, price, amenities)

Property Listings (Photos, descriptions, reviews)

Booking System (Calendar, availability, instant/book request)

Payment Integration (Stripe, PayPal)

Wishlist/Favorites

In-App Messaging with Hosts

For Hosts:
Host Dashboard (Manage listings, calendar, earnings)

List a Property (Add photos, amenities, pricing)

Booking Management (Approve/reject, messaging)

Payout System (Connect bank account, track payouts)

Reviews & Ratings

| **Page**                   | **Description**                                                                                                                                     | **Key Elements**                                                                                   |
|---------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|
| **Property Listing View** | Displays a scrollable/searchable grid or list of properties based on user input or default location.                                                | - Search bar with filters (location, date, guests)<br>- Grid/List of property cards<br>- Map view |
| **Listing Detailed View** | Shows in-depth details about a selected property, enabling the guest to learn more before booking.                                                  | - Image carousel<br>- Title, price, and location<br>- Host info<br>- Description and amenities<br>- Reviews<br>- Booking calendar        |
| **Simple Checkout View**  | A minimal, focused page for finalizing booking with payment, user confirmation, and policies.                                                       | - Booking summary (dates, guests, price breakdown)<br>- Payment form<br>- Cancellation policy<br>- Confirm button                        |

## UI/UX Design Planning:

🎨 Color Styles

| **Name**            | **Hex Code**   | **Usage**                                |
|---------------------|----------------|------------------------------------------|
| **Primary Red**     | `#FF5A5F`       | Action buttons, highlights                |
| **Secondary Pink**  | `#FFB400`       | Accents, icons                            |
| **Dark Charcoal**   | `#484848`       | Primary text                              |
| **Light Gray**      | `#F7F7F7`       | Backgrounds, cards                        |
| **Gray**            | `#767676`       | Secondary text, icons                     |
| **White**           | `#FFFFFF`       | Background, text contrast                 |
| **Success Green**   | `#008489`       | Confirmations, trust indicators           |
| **Error Red**       | `#D93900`       | Errors, alerts                            |
| **Shadow Black**    | `rgba(0, 0, 0, 0.1)` | Shadows, overlays                     |

✍️ Typography
Font Family
Primary: Circular Std, Helvetica Neue, Arial, sans-serif

Font Weights :


| **Weight Name** | **Value** |
|------------------|-----------|
| Light            | `300`     |
| Regular          | `400`     |
| Medium           | `500`     |
| Bold             | `700`     |

Font Sizes : 


| **Size Name**     | **Pixels** | **Usage**                          |
|-------------------|------------|------------------------------------|
| Display Large     | `48px`     | Hero titles, section headers       |
| Heading 1         | `32px`     | Page titles                        |
| Heading 2         | `24px`     | Subtitles, section headings        |
| Body Large        | `18px`     | Paragraphs, general content        |
| Body Regular      | `16px`     | Main text                          |
| Caption / Label   | `14px`     | Hints, secondary info, buttons     |
| Micro             | `12px`     | Footnotes, metadata                |


Identifying the design properties of a mockup is crucial for several reasons, especially in a product development context where precision, consistency, and communication are key. Here’s why it matters:

1. Ensures Design Consistency
By identifying properties like color styles, typography, spacing, and layout, designers and developers can maintain visual and functional uniformity across all screens and components.

2. Speeds Up Development
When design properties are clearly defined, developers can easily translate the mockup into code without ambiguity, reducing back-and-forth and implementation errors.

3. Enhances Collaboration
Clearly outlined properties allow designers, developers, and stakeholders to speak a common visual language, improving communication and feedback.

4. Supports Design Systems
Identified design properties are the foundation for creating reusable components and design tokens, which power scalable design systems (e.g., in Figma, Storybook, or Tailwind).

5. Improves Accessibility
Defining contrast ratios, font sizes, and hierarchy helps ensure the design meets accessibility standards (e.g., WCAG compliance), making products more inclusive.

6. Facilitates Quality Assurance
QA testers can verify if implementation matches the mockup by comparing specific properties like colors, font sizes, and spacing — not just visuals.

## Project Roles and Responsibilities 

🔹 1. Project Manager (PM)
Role: Oversees project execution and ensures timely delivery within scope, time, and budget.
Responsibilities:

Define and manage project scope, timelines, and resources

Coordinate between teams and stakeholders

Track progress and mitigate risks

Communicate status updates to leadership

🔹 2. Product Owner (PO)
Role: Represents the customer and business interests; owns the product vision and backlog.
Responsibilities:

Define product goals and roadmap

Prioritize features and backlog items

Accept or reject completed work

Clarify requirements and business value for the team

🔹 3. Scrum Master
Role: Facilitates the Scrum process and ensures the team follows Agile principles.
Responsibilities:

Organize and run Scrum ceremonies (stand-ups, sprint planning, reviews, retrospectives)

Remove blockers for the development team

Coach the team on Agile practices

Foster a culture of continuous improvement

🔹 4. Designers (UI/UX)
Role: Create the user interface and experience of the application.
Responsibilities:

Design wireframes, mockups, and user flows

Ensure accessibility, usability, and responsiveness

Collaborate with developers to implement designs

Conduct user research and testing

🔹 5. Frontend Developers
Role: Build the user-facing part of the application (e.g., website or app).
Responsibilities:

Translate UI designs into functional interfaces using HTML, CSS, JavaScript/TypeScript

Implement responsive design and interactivity

Integrate with backend APIs

Ensure performance, accessibility, and cross-browser compatibility

🔹 6. Backend Developers
Role: Handle the server-side logic, databases, and APIs.
Responsibilities:

Develop and maintain APIs and server logic

Design and manage databases

Ensure data security and system scalability

Integrate with third-party services

🔹 7. QA/Testers
Role: Ensure the quality and stability of the product.
Responsibilities:

Write and execute test cases (manual and automated)

Identify, report, and verify bugs

Perform regression, performance, and security testing

Validate user flows and requirements

🔹 8. DevOps Engineers
Role: Maintain infrastructure, CI/CD pipelines, and deployment environments.
Responsibilities:

Set up and manage cloud infrastructure and servers

Automate deployment and integration processes

Monitor system performance and reliability

Ensure system scalability, backups, and recovery

## UI Component Patterns 
🔹 1. Navbar (Navigation Bar)
Purpose: Provides site-wide navigation and user access to core features.
Key Elements:

Logo (clickable, navigates to homepage)

Search bar (location, dates, guests)

Navigation links (e.g., Become a Host, Help, etc.)

User menu (profile, login/logout, bookings)

Responsive behavior for mobile views

🔹 2. Property Card
Purpose: Displays a summary of a property in listing views.
Key Elements:

Property image (with hover animation)

Title or location (e.g., “Cozy Loft in Paris”)

Rating (stars + number of reviews)

Price per night

Tags (e.g., “Superhost”, “New”)

Optional: wishlist icon (heart)

🔹 3. Footer
Purpose: Provides site-wide links and legal information.
Key Elements:

Navigation links (About, Careers, Blog, Help, etc.)

Language and currency switcher

Social media icons

Copyright

Legal links (Privacy Policy, Terms of Service)

🔹 Additional Suggested Components

| **Component**        | **Purpose**                                                                |
|----------------------|----------------------------------------------------------------------------|
| **Search Bar**       | Lets users enter search criteria (location, dates, guests)                 |
| **Filter Panel**     | Provides filtering by price, amenities, type, etc.                         |
| **Booking Calendar** | Allows date selection with availability and price reflection               |
| **Listing Gallery**  | Carousel of property photos in detailed view                               |
| **Review Card**      | Displays user reviews with name, avatar, date, and rating                  |
| **Booking Summary**  | Mini cart-style widget for checkout, showing selected dates and price      |
| **Modal Dialogs**    | For login, booking confirmation, messages                                  |
| **Toast/Alert**      | Status feedback for actions (e.g., booking success, form errors)           |


