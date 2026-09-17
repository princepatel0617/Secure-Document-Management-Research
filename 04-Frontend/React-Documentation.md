# ⚛️ React Documentation

### Frontend Development Research

---

## 📌 Source Information

**Source:** React Documentation  
**Organization:** Meta / React  
**Type:** Official Documentation

**Official Source:**  
https://react.dev/learn

---

## 🎯 Why This Source Was Studied

React provides a component-based approach for building user interfaces.

For our proposed system, React can be used to build the dashboards and interfaces for different users such as investigators, legal teams and administrators.

---

## 🔑 Key Concepts Studied

### 01 — Components

React applications are built using reusable components.

**Application in our system:**

Separate components can be created for:

- Login
- Dashboard
- Case Management
- Document Upload
- Document Viewer
- Search
- Audit Logs
- User Management

---

### 02 — JSX

JSX allows markup to be written within JavaScript and is commonly used in React projects.

**Application:**

Used to structure the interface and display dynamic case and document information.

---

### 03 — Displaying Data

React can display dynamic data inside components.

**Application:**

Case information, document names, user details and search results can be displayed dynamically from backend data.

---

### 04 — Conditional Rendering

React supports conditional rendering based on application state.

**Application:**

Different interfaces or options can be displayed depending on the user's role or application state.

Example:

```text
Administrator → User Management
Investigator  → Assigned Cases
Legal User    → Authorized Documents
