# react-learning
on this repo I will share all what I learned in react

# React Roadmap: Zero to Hero 🚀

A structured learning path for mastering React, from JavaScript prerequisites to advanced React, Next.js, and production-ready projects.

---

## How to Use This Roadmap
- [ ] Study topics in order.
- [ ] Write code for every topic instead of only watching tutorials.
- [ ] Complete the practice tasks before moving forward.
- [ ] Build the projects progressively and revisit earlier concepts when needed.
- [ ] You do not need to master every advanced JavaScript topic before starting React.

---

## Phase 0 — Prerequisites: JavaScript

### JavaScript Fundamentals
- [ ] Variables: `let`, `const`
- [ ] Data types and operators
- [ ] Conditions: `if`/`else`, `switch`
- [ ] Loops: `for`, `while`, `for...of`
- [ ] Functions and arrow functions
- [ ] Arrays and objects
- [ ] Destructuring
- [ ] Spread and rest operators
- [ ] Template literals

### Array Methods
- [ ] `map()`
- [ ] `filter()`
- [ ] `find()`
- [ ] `findIndex()`
- [ ] `some()`
- [ ] `every()`
- [ ] `includes()`
- [ ] `reduce()`
- [ ] `sort()`

### DOM Fundamentals
- [ ] `getElementById()`
- [ ] `querySelector()` and `querySelectorAll()`
- [ ] `createElement()`
- [ ] `appendChild()`
- [ ] `textContent` and `value`
- [ ] `addEventListener()`

### Modern JavaScript
- [ ] `import` and `export`
- [ ] Promises
- [ ] `async` / `await`
- [ ] `fetch()`
- [ ] `try` / `catch`
- [ ] JSON

> **Practice Milestone:** Create a students array and display names, find a student by ID, filter students by age, add a student, delete a student, edit a student, and calculate the average age.

---

## Phase 1 — React Fundamentals

### 1. Introduction to React
- [ ] What React is and why it is used
- [ ] React versus direct DOM manipulation
- [ ] Declarative UI
- [ ] Single-page applications (SPA)
- [ ] Components and the Virtual DOM concept

### 2. Set up a React Project
- [ ] Install Node.js and npm
- [ ] Understand `package.json`
- [ ] Create a project with Vite
- [ ] Understand `src`, `public`, `main.jsx`, and `App.jsx`
- [ ] Run the development server
  ```bash
  npm create vite@latest my-react-app
  cd my-react-app
  npm install
  npm run dev
  ```

### 3. JSX
- [ ] JSX syntax and expressions with `{}`
- [ ] `className` and JSX attributes
- [ ] JSX rules
- [ ] Fragments (`<>...</>`)

### 4. Components
- [ ] Functional components
- [ ] Component naming
- [ ] Component composition
- [ ] Parent and child components
- [ ] Reusable components

### 5. Props
- [ ] Passing props
- [ ] Destructuring props
- [ ] Props containing arrays and objects
- [ ] Passing functions as props
- [ ] The `children` prop

### 6. Lists and Keys
- [ ] Render arrays with `map()`
- [ ] Understand the `key` prop
- [ ] Render lists of objects

### 7. Conditional Rendering
- [ ] `if` statements and early returns
- [ ] Ternary operator (`? :`)
- [ ] Logical `&&`
- [ ] Loading, empty, and error states

---

## Phase 2 — State and User Interaction

### 8. useState
- [ ] Understand state and re-rendering
- [ ] Update state correctly
- [ ] Use multiple state variables
- [ ] Update objects and arrays in state
- [ ] Use functional updates when appropriate

### 9. Events
- [ ] `onClick`
- [ ] `onChange`
- [ ] `onSubmit`
- [ ] Keyboard events
- [ ] Event handlers and event objects

### 10. Forms
- [ ] Controlled inputs
- [ ] Text and number inputs
- [ ] Checkboxes, radio buttons, and select fields
- [ ] Textareas
- [ ] Form submission
- [ ] Client-side validation

> **Project 1 — Student Manager (Frontend only):**
> - [ ] Add students
> - [ ] Display students
> - [ ] Edit and delete students
> - [ ] Search and filter students
> - [ ] Validate form input

---

## Phase 3 — React Hooks and APIs

### 11. useEffect
- [ ] Understand side effects
- [ ] Dependency arrays
- [ ] Effects that run after rendering
- [ ] Cleanup functions
- [ ] Timers and event listeners
- [ ] Avoid unnecessary effects

### 12. Fetch Data from APIs
- [ ] `fetch()` with `async` / `await`
- [ ] GET requests
- [ ] Parse JSON
- [ ] Handle loading, success, empty, and error states
- [ ] Understand HTTP status codes

### 13. useRef
- [ ] Access DOM elements
- [ ] Focus an input
- [ ] Store values that should persist without triggering a re-render

### 14. useMemo
- [ ] Understand memoization
- [ ] Cache expensive calculations when useful
- [ ] Know when NOT to use it

### 15. useCallback
- [ ] Understand function references
- [ ] Use it when it solves a real performance problem
- [ ] Understand its relationship with `React.memo`

---

## Phase 4 — Component Architecture

### 16. Organize Components
- [ ] Component hierarchy
- [ ] Separation of concerns
- [ ] Reusable UI components
- [ ] Composition
- [ ] Organize files and folders

### 17. Lifting State Up
- [ ] Share state between sibling components
- [ ] Keep shared state in the nearest common parent

### 18. Props Drilling
- [ ] Understand what props drilling is
- [ ] Recognize when passing props through many layers becomes difficult

### 19. Context API
- [ ] `createContext()`
- [ ] Context provider
- [ ] `useContext()`
- [ ] Use Context for shared values such as theme, language, and authentication state

---

## Phase 5 — Routing

### 20. React Router
- [ ] Routes and route configuration
- [ ] `Link` and `NavLink`
- [ ] `useNavigate()`
- [ ] Dynamic routes and `useParams()`
- [ ] Nested routes and layouts
- [ ] Not-found (404) pages
- [ ] Protected-route patterns

---

## Phase 6 — Backend Integration

### 21. REST APIs and HTTP
- [ ] GET, POST, PUT, PATCH, and DELETE
- [ ] JSON request and response bodies
- [ ] HTTP status codes
- [ ] Error handling
- [ ] CORS
- [ ] Environment variables for configuration

### 22. React + PHP + MySQL
Understand the flow:
```text
React frontend
     |
  fetch() / HTTP
     |
   PHP API
     |
   MySQL
```

> **Project 2 — Student Management System:**
> - [ ] Create PHP API endpoints
> - [ ] Display students from MySQL
> - [ ] Add, edit, and delete students
> - [ ] Search and filter
> - [ ] Add pagination if needed
> - [ ] Validate data on both frontend and backend
> - [ ] Handle loading and errors

---

## Phase 7 — Authentication and Authorization

### 23. Authentication
- [ ] Login and registration flows
- [ ] Logout
- [ ] Authentication versus authorization
- [ ] Protected pages
- [ ] Sessions and cookies
- [ ] JWT concepts and trade-offs
- [ ] Password hashing on the backend
- [ ] Roles and permissions

> **Project 3 — Admin Dashboard:**
> - [ ] Login
> - [ ] Dashboard layout
> - [ ] Manage users, skills, and projects
> - [ ] Edit profile information
> - [ ] Protect admin operations on the backend

> 🔒 **Security Note:** Never store plain-text passwords. Do not rely on frontend route protection alone; enforce authorization on the server.

---

## Phase 8 — State Management

### 24. Context API Review
- [ ] Know when local component state is enough
- [ ] Know when shared context is useful

### 25. Redux Toolkit
- [ ] Store
- [ ] Slices and reducers
- [ ] Actions and dispatch
- [ ] Selectors
- [ ] Async logic
- [ ] DevTools

### 26. RTK Query
- [ ] Fetching and caching API data
- [ ] Loading and error states
- [ ] Mutations and cache invalidation

*Note: Redux is not required for every application. Learn it when application complexity justifies a dedicated state-management solution.*

---

## Phase 9 — Professional React Practices

### 27. Custom Hooks
- [ ] Extract reusable stateful logic
- [ ] Follow the Rules of Hooks
- [ ] Build examples such as `useAuth`, `useDebounce`, or `useLocalStorage`

### 28. Performance
- [ ] Understand rendering and re-rendering
- [ ] `React.memo`
- [ ] `useMemo` and `useCallback`
- [ ] Lazy loading and code splitting
- [ ] `Suspense`
- [ ] Avoid premature optimization

### 29. Error Handling
- [ ] API errors
- [ ] Form errors
- [ ] Empty and loading states
- [ ] Error boundaries
- [ ] Clear user-facing error messages

### 30. Professional Forms
- [ ] React Hook Form
- [ ] Schema validation with Zod
- [ ] Server-side validation
- [ ] Accessible form labels and error messages

---

## Phase 10 — Styling and UI

### 31. Styling React Applications
- [ ] CSS modules or another component styling approach
- [ ] Tailwind CSS with React
- [ ] Responsive layouts
- [ ] Reusable buttons, inputs, cards, tables, and modals
- [ ] Navigation and sidebars
- [ ] Accessible focus states
- [ ] Dark mode if needed

---

## Phase 11 — TypeScript

### 32. TypeScript with React
*Learn TypeScript after becoming comfortable with React and JavaScript.*
- [ ] Basic types
- [ ] Arrays and objects
- [ ] `type` and `interface`
- [ ] Union types and optional properties
- [ ] Typed props and events
- [ ] Typing hooks
- [ ] Generics

---

## Phase 12 — Advanced React

### 33. Advanced Concepts
- [ ] `useReducer`
- [ ] Advanced component composition
- [ ] Controlled and uncontrolled components
- [ ] Compound components
- [ ] Render props and higher-order components (recognize legacy patterns)
- [ ] `useTransition`
- [ ] `useDeferredValue`
- [ ] `useId`
- [ ] Ref-related APIs and imperative handles when needed

*Learn these concepts when you encounter a use case; you do not need to memorize every API at the beginning.*

---

## Phase 13 — Modern React and Next.js

### 34. Modern React Concepts
- [ ] Server Components concepts
- [ ] Server/client boundaries
- [ ] `Suspense`
- [ ] Streaming concepts
- [ ] Understand which features depend on the framework

### 35. Next.js
- [ ] App Router
- [ ] Pages and layouts
- [ ] Dynamic routes
- [ ] Server and Client Components
- [ ] Loading and error UI
- [ ] Data fetching
- [ ] Route handlers
- [ ] Authentication
- [ ] Metadata and SEO
- [ ] Image optimization
- [ ] Deployment

*Learn Next.js after you understand React components, props, state, hooks, routing, and data fetching.*

---

## Phase 14 — Build Real Projects

- [ ] **Project 1: Todo App**
  - Add, edit, delete, and complete tasks
  - Filter and search
  - Persist data with `localStorage`

- [ ] **Project 2: Student Management System**
  - React frontend
  - PHP API
  - MySQL database
  - CRUD, search, filtering, validation, and pagination

- [ ] **Project 3: E-commerce Frontend**
  - Home and product listing
  - Product details
  - Shopping cart
  - Checkout UI
  - Login and registration
  - API integration and shared state

- [ ] **Project 4: Admin Dashboard**
  - Authentication
  - Users, products, or orders
  - Tables, filters, and forms
  - Statistics and settings
  - Backend authorization

- [ ] **Project 5: Personal Portfolio**
  - Home, About, Skills, Projects, and Contact
  - CV download and social links
  - Admin login
  - Dynamic CRUD for skills and projects
  - React frontend + PHP API + MySQL

---

## Recommended Study Order

1. - [ ] JavaScript fundamentals and modern JavaScript
2. - [ ] React setup, JSX, and components
3. - [ ] Props, lists, keys, and conditional rendering
4. - [ ] Events, `useState`, and forms
5. - [ ] `useEffect`, API calls, and `useRef`
6. - [ ] Component architecture and lifting state
7. - [ ] Context API
8. - [ ] React Router
9. - [ ] REST APIs and React + PHP + MySQL
10. - [ ] Authentication and authorization
11. - [ ] Custom hooks and error handling
12. - [ ] Redux Toolkit and RTK Query when needed
13. - [ ] Performance and professional forms
14. - [ ] TypeScript
15. - [ ] Advanced React concepts
16. - [ ] Next.js
17. - [ ] Build, test, and deploy complete projects

---

## Study Method for Every Topic

For each topic:
1. - [ ] Read a clear explanation.
2. - [ ] Study syntax and examples.
3. - [ ] Write the examples yourself.
4. - [ ] Complete an easy exercise.
5. - [ ] Complete a medium exercise.
6. - [ ] Attempt a challenge exercise.
7. - [ ] Review mistakes before moving on.
8. - [ ] Apply the concept to a project.

---

## Definition of Progress

> You are progressing when you can explain a concept in your own words, implement it without copying a tutorial, debug common mistakes, and use it in a small project.

**Start here:**  
JavaScript prerequisites ➔ React + Vite ➔ JSX ➔ Components ➔ Props.
