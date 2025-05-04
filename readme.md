# Microfrontend Project

This is a microfrontend-based application composed of multiple independently developed and deployed modules. The following microfrontends are included:

- **Authentication**: Handles login and registration
- **Dashboard**: Displays analytics and user data
- **Marketing**: Includes home page and product pricing information

## 🚀 Getting Started

Follow these steps to set up and run the project locally:

### 1. Clone the Repository

```bash
git clone <your-repo-url>
cd <repo-directory>
````

### 2. Install Dependencies

Navigate to the `mfp/packages` directory and install dependencies for each package:

```bash
cd mfp/packages
```

For each subdirectory (package), run:

```bash
cd <package-name>
npm install
```

Repeat this step for all packages.

### 3. Start Each Package

After installing dependencies, start each package individually:

```bash
cd <package-name>
npm start
```

Repeat this step for all packages.

### 4. Access the Application

Once all packages are running, open your browser and go to:

```
http://localhost:8000
```

---

## 📦 Microfrontend Modules

* `authentication`: Handles user login and registration
* `dashboard`: Analytics dashboard and user metrics
* `marketing`: Home page and product pricing information

---

## 🛠️ Tech Stack

* Module Federation
* React
* Webpack
* npm