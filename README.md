# Salesforce Accordion Replica

A responsive accordion component inspired by Salesforce’s Starter Suite UI.

## Features

- **Responsive layout**  
  Two-column layout on desktop, single-column stack on mobile for optimal readability.

- **Accordion functionality using native HTML + CSS**  
  Powered by semantic radio inputs and enhanced with CSS selectors:

  - `:checked` — reveals the currently selected accordion panel
  - Adjacent sibling combinator (`+`) — targets the label directly following the input
  - `:has()` — applies styles to parent elements when a child input is checked, enabling dynamic state styling (e.g., borders, visibility)

- **Dynamic image updates via JavaScript**  
  The main image updates in real-time based on which accordion item is active.

## Tools Used

- **HTML5**
- **CSS3**
  - Grid & Flexbox for layout
  - Media queries for responsiveness
  - Transitions and hover/focus states
  - Advanced selectors (`:checked`, `:has()`, combinators)
- **JavaScript**
  - DOM manipulation for image switching

---

Built by **JoeFlashh**
