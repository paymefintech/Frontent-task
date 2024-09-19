# Frontent-task

Here are **5 advanced frontend developer interview tasks**. Each task is divided into 5 parts for a total of 20 points, testing different aspects of frontend development including performance, UI/UX, advanced JavaScript, API handling, and state management.

---

### **Task 1: E-Commerce Product Dashboard**
**Overview**: Build a responsive product listing dashboard with filtering, sorting, and a shopping cart functionality.

---

#### **1. Responsive Layout & Product Display (4 Points)**

- **Description**: Create a responsive product listing grid using **CSS Grid/Flexbox**. The layout should be mobile-first, adjusting based on screen size.
  - Each product card should display an image, price, title, and "Add to Cart" button.
  - Support dark and light themes with a toggle.

- **Skills to Evaluate**: Responsive Web Design, CSS Grid/Flexbox, Theming

---

#### **2. Filtering & Sorting (4 Points)**

- **Description**: Implement product filtering by category and price range, as well as sorting by price or name.
  - Use React/Next.js with **Context API** or **Redux** for state management.
  - Ensure that filtering and sorting can be combined efficiently.

- **Skills to Evaluate**: React/Next.js, State Management, Filtering/Sorting Logic

---

#### **3. Cart Functionality (4 Points)**

- **Description**: Implement a shopping cart where users can add, remove, and update product quantities.
  - Show a "Cart" sidebar or modal that displays the selected items and total price.
  - Ensure the cart persists across page refreshes using **localStorage/sessionStorage**.

- **Skills to Evaluate**: State Management, Persistent Data Storage, Cart Logic

---

#### **4. Performance Optimization (4 Points)**

- **Description**: Implement lazy loading for product images, and use **React.memo** or **useCallback/useMemo** to prevent unnecessary re-renders.
  - Implement **code-splitting** for the cart and product details components.

- **Skills to Evaluate**: Performance Optimization, Lazy Loading, Code-Splitting

---

#### **5. Unit Testing & Accessibility (4 Points)**

- **Description**: Write unit tests for key components (e.g., product list, cart) using **Jest** or **React Testing Library**.
  - Ensure the product dashboard is accessible (semantic HTML, ARIA roles).

- **Skills to Evaluate**: Unit Testing, Accessibility, Best Practices

---

---

### **Task 2: Social Media Feed with Infinite Scroll**
**Overview**: Build a responsive social media feed with infinite scroll, a like system, and post creation functionality.

---

#### **1. Responsive Feed Layout (4 Points)**

- **Description**: Create a responsive feed layout where each post is displayed as a card. The layout should adapt to mobile, tablet, and desktop views.
  - Include user profile pictures, post content, timestamps, and like buttons on each post.

- **Skills to Evaluate**: Responsive Design, CSS Flexbox/Grid

---

#### **2. Infinite Scroll & API Integration (4 Points)**

- **Description**: Implement **infinite scroll** to load posts as the user scrolls down the feed. Fetch data from a public API (e.g., a JSON placeholder or custom mock API).
  - Use **IntersectionObserver API** for scroll detection.

- **Skills to Evaluate**: Infinite Scroll, API Integration, IntersectionObserver

---

#### **3. Like System & Post Creation (4 Points)**

- **Description**: Implement a "like" system where users can like or unlike posts, with the like count updating in real-time.
  - Allow users to create new posts with text and images using a simple form.

- **Skills to Evaluate**: State Management, Event Handling, Real-Time Updates

---

#### **4. Performance Optimization (4 Points)**

- **Description**: Implement lazy loading for post images and use **React.memo** to prevent unnecessary re-renders of posts.
  - Apply **debouncing** for API calls when loading posts.

- **Skills to Evaluate**: Performance Optimization, Lazy Loading, Debouncing

---

#### **5. Testing & Code Quality (4 Points)**

- **Description**: Write tests for the feed and post components. Ensure clean, modular code following best practices.
  - Ensure accessibility with semantic HTML and keyboard navigation.

- **Skills to Evaluate**: Unit Testing, Code Quality, Accessibility

---

---

### **Task 3: Real-Time Collaborative Task Manager**
**Overview**: Build a real-time task management application where users can create, assign, and update tasks. Users should be able to see changes in real-time.

---

#### **1. Responsive Task Board Layout (4 Points)**

- **Description**: Create a **Kanban-style task board** using **CSS Grid**. Each task should be displayed in a card with title, description, and assignee.
  - Implement drag-and-drop functionality for moving tasks between columns (e.g., To Do, In Progress, Done).

- **Skills to Evaluate**: CSS Grid, Drag-and-Drop, Responsive Design

---

#### **2. Task Creation & Assignment (4 Points)**

- **Description**: Implement a form to create tasks with a title, description, and assignee. Use **Context API** or **Redux** to manage the global task state.
  - Allow users to assign tasks to different team members.

- **Skills to Evaluate**: State Management, Form Handling, Task Creation

---

#### **3. Real-Time Updates with WebSockets (4 Points)**

- **Description**: Implement real-time updates using **WebSockets** or **Firebase**. When a task is created or updated, all users should see the changes immediately.
  - Handle edge cases like connection loss or reconnection.

- **Skills to Evaluate**: WebSockets, Real-Time Updates, Edge Case Handling

---

#### **4. Performance Optimization (4 Points)**

- **Description**: Optimize performance by implementing **code-splitting** and using **React.memo** to avoid unnecessary re-renders.
  - Implement **pagination** for loading large sets of tasks.

- **Skills to Evaluate**: Performance Optimization, Code-Splitting, Pagination

---

#### **5. Testing & Code Structure (4 Points)**

- **Description**: Write unit tests for key components, such as the task list and task creation form.
  - Ensure the app follows best practices with clean, modular, and reusable components.

- **Skills to Evaluate**: Unit Testing, Code Quality, Best Practices

---

---

### **Task 4: Portfolio Website with Interactive Elements**
**Overview**: Build a personal portfolio website showcasing projects, with a blog and interactive elements like animations and transitions.

---

#### **1. Responsive Portfolio Layout (4 Points)**

- **Description**: Create a responsive layout for the portfolio, with sections for "About Me", "Projects", and "Blog". Ensure the layout looks great on all devices.
  - Use **CSS Grid/Flexbox** to organize the sections, and implement smooth scrolling for navigation.

- **Skills to Evaluate**: Responsive Design, CSS Grid/Flexbox

---

#### **2. Project Display with Animations (4 Points)**

- **Description**: Display projects as cards or tiles, with animations on hover (e.g., scale, shadow).
  - Use **CSS transitions/animations** or a library like **Framer Motion** to make the project section interactive.

- **Skills to Evaluate**: CSS Animations, UI/UX Design

---

#### **3. Blog Section with Markdown Rendering (4 Points)**

- **Description**: Create a simple blog section where blog posts are written in Markdown and rendered on the page.
  - Use a markdown-to-HTML converter (e.g., **remark**, **marked**) to display posts.

- **Skills to Evaluate**: Markdown Rendering, State Management

---

#### **4. Performance Optimization & SEO (4 Points)**

- **Description**: Ensure the portfolio is highly performant by implementing **lazy loading** for images and **code-splitting** for the blog section.
  - Add basic **SEO optimizations** (meta tags, open graph tags, etc.).

- **Skills to Evaluate**: Performance Optimization, Lazy Loading, SEO Best Practices

---

#### **5. Testing & Accessibility (4 Points)**

- **Description**: Write tests for the project and blog components. Ensure the site is accessible, with semantic HTML and keyboard navigation.
  - Ensure all images have alt text, and form elements are labeled correctly.

- **Skills to Evaluate**: Unit Testing, Accessibility, Best Practices

---

---

### **Task 5: Real-Time Weather Dashboard**
**Overview**: Build a weather dashboard that fetches real-time weather data, displays it in a visually appealing way, and allows users to search for cities.

---

#### **1. Responsive Dashboard Layout (4 Points)**

- **Description**: Build a responsive dashboard layout with a search bar at the top, followed by a section displaying current weather data for a selected city.
  - Use **CSS Grid** or **Flexbox** to create a clean, organized design.

- **Skills to Evaluate**: Responsive Design, CSS Grid/Flexbox

---

#### **2. API Integration (4 Points)**

- **Description**: Use the **OpenWeather API** (or another weather API) to fetch and display real-time weather data. Show temperature, weather description, wind speed, and humidity.
  - Implement **error handling** for invalid city searches.

- **Skills to Evaluate**: API Integration, Error Handling

---

#### **3. Search & Recent Searches (4 Points)**

- **Description**: Implement a search bar that allows users to search for a city and display the current weather.
  - Keep a list of recent searches using **localStorage** and

 allow users to click on them to view the weather again.

- **Skills to Evaluate**: State Management, Persistent Storage, Event Handling

---

#### **4. Performance Optimization (4 Points)**

- **Description**: Use **debouncing** to limit API calls during city search. Implement **lazy loading** for background images and weather icons.
  - Use **React.memo** or **useMemo/useCallback** to optimize rendering.

- **Skills to Evaluate**: Performance Optimization, Lazy Loading, Debouncing

---

#### **5. Testing & Accessibility (4 Points)**

- **Description**: Write unit tests for the search and weather display components.
  - Ensure the weather dashboard is accessible, with focus management and semantic HTML.

- **Skills to Evaluate**: Unit Testing, Accessibility, Best Practices

---

These tasks are designed to comprehensively evaluate the candidate's frontend development skills, covering a range of technologies, performance optimizations, and best practices.
