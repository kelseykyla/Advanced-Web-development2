# Advanced-Web-development2
# Link to Live site
https://kelseykyla.github.io/Advanced-Web-development/
# Advanced-Web-development
/*
  JS Features Used:
  - Variables & Data Types: Defined const/let variables like bookings (array), time (string), duplicateAttempts (number).
  - Control Structures: if/else used for form validation, rule checks, and logic branching.
  - Loops: for, for...of used in rendering table rows, computing insights, and parsing students.
  - Functions: parseStudentIds(), isWithinOperatingHours(), findBooking(), hasCrossPodClash(), recomputeInsights() — each does one task.
  - Events: addEventListener() handles form submission and row button clicks.
  - DOM Manipulation: createElement, appendChild, innerHTML, and textContent dynamically update select options, table, and error messages.
*/
##  Features

- Real-time booking form with validation
- Enforces 5 strict rules:
  - Pod capacity limit (4 students)
  - No duplicate student in same pod/time
  - No student booked across different pods at same hour
  - Operating hours enforcement (08:00–20:00)
  - Strict === comparisons
- Live bookings table with remove buttons
- Auto-updating insights panel
- Defensive edge-case handling (e.g., lowercase IDs, whitespace)
- Clean UX with structured error messages
