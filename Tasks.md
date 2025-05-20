# Tasks for Interactive Product Tour Builder

## Phase 0: Project Setup & Planning 🏗️

- [ ] **Environment Setup**
    - [ ] Choose a framework: React, Next.js, or Vite.
    - [ ] Initialize the project using the chosen framework (e.g., `create-next-app`, `npm create vite@latest`).
    - [ ] Install Tailwind CSS and configure it.
    - [ ] (Optional) Install Framer Motion: `npm install framer-motion`.
    - [ ] Set up Git repository on GitHub.
    - [ ] Create a basic project structure (folders for components, pages, assets, etc.).
- [ ] **Planning & Design Mockups (Low-Fidelity)**
    - [ ] Sketch out the landing page layout.
    - [ ] Sketch out the product tour display (vertical timeline or carousel).
    - [ ] Sketch out the editor screen layout.
    - [ ] Define the data structure for a "tour step" (e.g., `id`, `title`, `description`, `imageUrl`, `tooltipText`).

---

## Phase 1: Landing Page & Hero Section ✨

- [ ] **Create Landing Page Component/Page**
- [ ] **Develop Hero Section**
    - [ ] Add a compelling headline and subheadline.
    - [ ] Include a brief description of the product tour builder.
    - [ ] Design and implement a clean, modern UI.
- [ ] **Implement "Start Demo" Button**
    - [ ] Style the button.
    - [ ] Add an `onClick` handler (initially, it can just log to the console or navigate to a placeholder).

---

## Phase 2: Core Demo Functionality - Tour Display 🚀

- [ ] **Data Mocking for 3-Step Tour**
    - [ ] Create an array of 3 mock step objects (image URL, description, title).
        - [ ] Source placeholder images for mock screens.
- [ ] **Develop Tour Display Component**
    - [ ] Choose display type:
        - [ ] **Option A: Vertical Timeline**
            - [ ] Create a component for a single timeline step.
            - [ ] Map over mock data to render timeline steps.
            - [ ] Style the timeline elements (lines, dots, content containers).
        - [ ] **Option B: Carousel**
            - [ ] Implement or integrate a basic carousel component.
            - [ ] Create a component for a single carousel slide.
            - [ ] Map over mock data to render carousel slides.
            - [ ] Add navigation controls (next/prev buttons or dots).
- [ ] **Connect "Start Demo" Button to Tour**
    - [ ] On "Start Demo" click, display the tour component/section.
    - [ ] Implement smooth scroll to the tour section or transition to a tour view.
- [ ] **Display Step Content**
    - [ ] For each step, display:
        - [ ] Image/mock screen.
        - [ ] Short description.
- [ ] **Implement Tooltips, Modals, or Highlights (Basic)**
    - [ ] Design a simple tooltip component.
    - [ ] Add a tooltip to one element in a demo step (e.g., on hover over a specific part of the image or description).
    - [ ] (Optional) Design a simple modal component.
    - [ ] (Optional) Add a highlight style for specific elements within a step.

---

## Phase 3: Editor Screen - Step Management 📝

- [ ] **Create Editor Page/Component**
    - [ ] Basic layout for the editor screen.
- [ ] **"Add New Step" Functionality (Mocked)**
    - [ ] Create a form component with fields:
        - [ ] Title (text input).
        - [ ] Image URL (text input).
        - [ ] Description (textarea).
    - [ ] Implement a button to "Add Step".
    - [ ] On form submission:
        - [ ] Get form data.
        - [ ] (Mock) Log the data to the console or add it to a local state array representing tour steps.
- [ ] **Live Preview Section**
    - [ ] Create a section on the editor page to display the tour preview.
    - [ ] Reuse the Tour Display Component (from Phase 2) to render the steps from the local state.
    - [ ] Ensure the preview updates when a new step is (mock) added.

---

## Phase 4: Interactivity & Animations 💫

- [ ] **Smooth Transitions Between Steps**
    - [ ] If using a vertical timeline:
        - [ ] Implement smooth scroll to the next/previous step when navigating.
        - [ ] Consider "snap-to-step" scrolling.
    - [ ] If using a carousel:
        - [ ] Ensure slide transitions are smooth (e.g., using CSS transitions or Framer Motion).
- [ ] **Animate Tooltip/Modal Appearance**
    - [ ] Add subtle animations for tooltip/modal entry and exit (e.g., fade-in, scale-up).
- [ ] **(Optional with Framer Motion) Enhance UI Element Animations**
    - [ ] Add hover effects to buttons or interactive elements.
    - [ ] Animate content loading or appearance.
- [ ] **Ensure Smooth Scrolling for the Entire Page**

---

## Phase 5: Styling & Responsiveness 📱

- [ ] **Global Styles**
    - [ ] Define base font sizes, colors, and spacing consistent with modern UI trends.
- [ ] **Responsive Design**
    - [ ] Test and adjust landing page for various screen sizes (mobile, tablet, desktop).
    - [ ] Test and adjust tour display for various screen sizes.
    - [ ] Test and adjust editor screen for various screen sizes.
    - [ ] Ensure navigation is usable on mobile.
    - [ ] Ensure form elements are usable on mobile.
- [ ] **Accessibility (A11y)**
    - [ ] Add `alt` text to all images.
    - [ ] Ensure sufficient color contrast.
    - [ ] Use semantic HTML elements.
    - [ ] Ensure keyboard navigability for interactive elements (buttons, form fields, tour navigation).
    - [ ] Add ARIA attributes where necessary (e.g., for tooltips, modals).

---

## Phase 6: Bonus Features (Optional) 🌟

- [ ] **Deploy to Hosting Platform**
    - [ ] Choose a platform (Vercel, Netlify, GitHub Pages).
    - [ ] Configure deployment settings.
    - [ ] Deploy the application.
    - [ ] Test the live link.
- [ ] **Drag-and-Drop Reordering of Steps**
    - [ ] Research and choose a drag-and-drop library (e.g., `react-beautiful-dnd`, `dnd-kit`) or implement a simple custom solution.
    - [ ] Implement drag-and-drop functionality in the editor's step list/preview.
    - [ ] Ensure the live preview updates with the reordered steps.
- [ ] **Light/Dark Mode Toggle**
    - [ ] Implement a theme switcher component.
    - [ ] Define color palettes for light and dark modes in Tailwind CSS config.
    - [ ] Allow users to toggle between themes.
    - [ ] Store user's theme preference (e.g., in `localStorage`).

---

## Phase 7: Testing, Documentation & Deployment 🧪📄🚀

- [ ] **Testing**
    - [ ] Manually test all core features across different browsers (Chrome, Firefox, Safari).
    - [ ] Test responsiveness thoroughly.
    - [ ] Test accessibility using browser tools or extensions.
    - [ ] Fix any bugs or UI inconsistencies found.
- [ ] **Documentation**
    - [ ] Create a clear `README.md` file:
        - [ ] Project description.
        - [ ] How to set up and run the project locally.
        - [ ] Tech stack used.
        - [ ] Explanation of features.
        - [ ] Link to the live demo (if deployed).
    - [ ] Comment code where necessary.
- [ ] **Final Code Review & Refactor**
    - [ ] Clean up code.
    - [ ] Remove unused files or comments.
    - [ ] Ensure consistent code style.
- [ ] **Prepare Deliverables**
    - [ ] Ensure GitHub repo is public and up-to-date.
    - [ ] Finalize hosted link (if deployed).
- [ ] **Submit Project** 🎉

