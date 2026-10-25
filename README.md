# CampusFind — A Smart Lost-and-Found System for University Students

## About the Project

CampusFind is a web-based lost-and-found platform designed to help university students report missing belongings and find items that have been lost or recovered on campus.

Losing personal belongings such as student ID cards, mobile phones, bags, books, and other valuables can be frustrating. Sometimes, even when someone finds a missing item, the owner has no easy way of knowing where to look for it.

CampusFind aims to make this process easier by providing a central platform where students can report lost items, share information about found belongings, and search for items reported by other users.

The project is being developed as a practical application of web development skills, with the goal of creating a useful solution to a problem students commonly experience on university campuses.

## Project Objectives

The main objectives of CampusFind are to:

* Provide a central platform for reporting lost and found belongings.
* Help students search for missing items using keywords and categories.
* Allow users to share useful information about where and when items were lost or found.
* Make it easier for students to connect with people who may have found their belongings.
* Provide a simple, responsive, and user-friendly experience across mobile phones, tablets, and computers.
* Establish a foundation for future features such as user authentication, item claims, notifications, and database integration.

## Key Features

### Current Frontend

The initial frontend focuses on the main interface and browsing experience.

* **Homepage:** Introduces CampusFind and explains its purpose.
* **Navigation:** Provides access to the main sections of the platform.
* **Item Listings:** Displays sample lost-and-found items.
* **Search:** Allows users to search item listings using relevant keywords.
* **Category Filtering:** Helps users narrow listings by category.
* **Responsive Design:** Adapts the interface to different screen sizes.
* **How It Works:** Explains the basic process of using the platform.

The current interface uses sample data to demonstrate the browsing experience. These listings do not represent verified reports from actual students.

### Planned Features

The following features are intended for future development:

* Submit reports for lost and found items.
* Upload images of reported belongings.
* View detailed information about individual items.
* Provide contact or claim information to help reunite owners with their belongings.
* Register and log in to user accounts.
* Manage submitted reports.
* Track the status of reported items.
* Connect the frontend to a backend and database.
* Introduce moderation and verification features to help reduce false reports and fraudulent claims.
* Add notifications when relevant items are reported.

These features will be introduced progressively as development continues.

## Technology Stack

CampusFind is being developed using the following technologies:

| Technology | Purpose                                             |
| ---------- | --------------------------------------------------- |
| HTML5      | Application structure                               |
| CSS3       | Styling, layouts, animations, and responsive design |
| JavaScript | Application logic and interactivity                 |
| React      | Building reusable user interface components         |
| Vite       | Development server and build tooling                |
| Git        | Version control                                     |
| GitHub     | Source code hosting and collaboration               |

The frontend uses plain CSS rather than a utility-first CSS framework.

A backend and database may be introduced in a later phase to support persistent data, authentication, and other dynamic features.

## Project Structure

The frontend is organized into reusable React components.

```text
CampusFind/
├── public/
├── src/
│   ├── components/
│   │   ├── Navbar.jsx
│   │   ├── Hero.jsx
│   │   ├── SearchBar.jsx
│   │   ├── CategoryFilter.jsx
│   │   ├── ItemCard.jsx
│   │   └── Footer.jsx
│   ├── App.jsx
│   ├── App.css
│   ├── index.css
│   └── main.jsx
├── .gitignore
├── index.html
├── package.json
├── package-lock.json
└── README.md
```

The structure may change as new features are added.

## Getting Started

Follow these instructions to run CampusFind on your local computer.

### Prerequisites

Ensure that you have installed:

* Node.js
* npm
* Git
* Visual Studio Code or another code editor

### 1. Clone the Repository

Replace `<your-github-username>` with your GitHub username.

```bash
git clone https://github.com/<your-github-username>/CampusFind.git
```

### 2. Navigate to the Project Folder

```bash
cd CampusFind
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Start the Development Server

```bash
npm run dev
```

Vite will display a local development address in the terminal. Open that address in your browser to view CampusFind.

### 5. Build for Production

To check whether the frontend can be built for production, run:

```bash
npm run build
```

To preview the production build locally, run:

```bash
npm run preview
```

## How CampusFind Is Intended to Work

The planned user journey is straightforward:

1. A student loses an item or finds an item belonging to someone else.
2. The student submits a report with relevant details.
3. The report becomes available for other users to search.
4. A student searches or browses the available listings.
5. When a potentially matching item is found, the student follows the available contact or claim process.
6. The item is returned to its rightful owner after appropriate verification.

The complete reporting, contact, and verification workflow will depend on the features implemented in future development phases.

## Development Approach

CampusFind is being developed incrementally.

The initial phase focuses on building a responsive frontend and establishing the main user interface. Subsequent phases will introduce functional reporting forms, item details, persistent storage, user accounts, and other features.

Git and GitHub are used to track changes throughout development. Individual files and features can be committed with descriptive commit messages to make the project's development history easier to understand.

## Future Improvements

Potential improvements include:

* Backend API development.
* Database integration for storing reports.
* Secure authentication and authorization.
* Image uploads and storage.
* Item claim and verification workflows.
* Search and filtering improvements.
* Administrative moderation tools.
* Email or in-app notifications.
* Deployment for public access.

These improvements will be prioritized as the project develops and requirements become clearer.

## Project Status

**Status:** In Development

The current focus is the frontend implementation. Features described as planned or future improvements should not be considered fully implemented until they are developed and tested.

## Contribution

Contributions, suggestions, and constructive feedback are welcome.

If you would like to contribute:

1. Fork the repository.
2. Create a branch for your changes.
3. Make your changes and test them.
4. Commit your work with a descriptive message.
5. Push your branch to GitHub.
6. Open a pull request describing your contribution.

Please keep changes focused and explain what each contribution adds to the project.

## Author

**Enock Hayford**

Computer Science Student
University of Cape Coast (UCC)

## Acknowledgements

CampusFind is a learning and development project inspired by the everyday challenge of lost belongings within university communities.

The goal is to apply web development skills to build a practical, accessible, and useful solution for students.

---

*CampusFind — Helping students find what matters.*
