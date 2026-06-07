# ReactJS Daily

Everyday practice of React.

---

# Day 1

### React Platforms

* Website – React DOM
* Mobile Apps – React Native

### npm vs npx

* npm – Node Package Manager

* npx – Node Package Executor

* npm = "Buy and keep the tool in your toolbox."

* npx = "Borrow the tool, use it once, and return it."

### Creating a React Project

#### Using Create React App (CRA)

```bash
npx create-react-app 01basicnpx
```

* Creates a larger project bundle.
* Takes more time to set up.

#### Using Vite

```bash
npm create vite@latest 01basicvite
npm install
npm run dev
```

* Creates a lighter and faster project.
* Faster startup and build times.
* Modern and recommended for new React projects.

### Running the Project

#### CRA

```bash
npm start
```

#### Vite

```bash
npm run dev
```

* Starts a local development server for coding and testing.

### Production Build

```bash
npm run build
```

* Creates an optimized production-ready version of the application.
* CRA generates a `build` folder.
* Vite generates a `dist` folder.
* These folders are used for deployment.

---

## package.json

### CRA

* `jest-dom` is a testing library that provides custom matchers for testing DOM elements in React applications.

### Vite

* `devDependencies` are packages used only during development and are not included in the production build.

---

## Cleaning the Project

Inside both `01basicnpx` and `01basicvite`, delete unnecessary files such as:

* setupTests.js
* reportWebVitals.js
* logo.svg
* App.test.js
* App.css

---

## Important Files

### manifest.json

Used to provide metadata about a web application, especially for Progressive Web Apps (PWAs).

Examples:

* App name
* Icons
* Theme color
* Display mode
* Start URL

### index.html

* The main HTML page loaded by the browser.
* React mounts the application into the root element of this page.
* In a Single Page Application (SPA), the same HTML page is used while React updates the content dynamically.

---
