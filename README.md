# student-mobile-portal
A student portal project for practicing Git and GitHub collaboration.
## Components

### StudentProfile

Displays a single student's basic profile information: name, student ID,
and program.

**File:** `StudentProfile.jsx`

**Fields shown:**
- Name
- Student ID
- Program

This component currently uses fictional sample data for demonstration
purposes. No real student records are used.

**Usage example:**

```jsx
import StudentProfile from "./StudentProfile";

function App() {
  return (
    <div>
      <StudentProfile />
    </div>
  );
}

export default App;
```

Import `StudentProfile` and render it inside any parent component, such
as `App.jsx`, to display the profile section on the page.

---
*Author: Keith Ramzel A. Jundis*
