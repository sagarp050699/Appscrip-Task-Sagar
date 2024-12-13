# Project Appscrip Task By Sagar Patil

## Overview

This project demonstrates the implementation of a responsive web page using HTML, CSS, and modern JavaScript frameworks. The page is developed using both static HTML/CSS and a React.js (Next.js) setup. The project incorporates Server-Side Rendering (SSR) to optimize SEO and performance.

## 1. HTML & CSS Implementation

- **HTML**: Implemented a basic webpage structure with `header`, `main`, and `footer` sections.
- **CSS**: Applied styles to ensure responsiveness for mobile and tablet devices. Basic reset and media queries are used to adjust layout based on screen size.

## 2. React.js (Next.js) Implementation

- **Setup**: Initialized a Next.js project using `create-next-app`.
- **Page Component**: Created a functional page component with:
  - Server-Side Rendering (SSR) using `getServerSideProps`.
  - Use of `Head` component for SEO metadata.
  - Responsive layout and styling.

## 3. Server-Side Rendering (SSR)

- **Usage**: Demonstrated SSR capabilities by fetching data server-side and passing it as props to the page component.

## 4. Responsiveness

- **Design**: Ensured the page layout adjusts appropriately for different devices, including mobile and tablet screens.
- **Testing**: Page tested across various screen sizes using browser developer tools.

## 5. Evaluation Criteria

- **Code Structure**: Organized code into modular components and styles.
- **Naming Conventions**: Used descriptive names for files, components, and CSS classes.
- **Pre-built JS Packages**: Minimized the use of external libraries and utilized built-in features wherever possible.
- **Screen Size Fit**: Ensured the page is functional and visually appealing across different device sizes.
- **Min DOM Size**: Maintained a minimal DOM structure to enhance performance.

## 6. SEO Settings

- **Page Title**: Set using the `<title>` tag within the `Head` component.
- **Page Description**: Added meta description for better SEO.
- **H1 & H2 Tags**: Implemented for clear content hierarchy.
- **Schema Settings**: Added JSON-LD schema for structured data.
- **Images**: Used descriptive, SEO-friendly filenames and appropriate `alt` text.

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine.

### Installation

1. Clone the repository:

   ```bash
   git clone origin https://github.com/sagarp050699/Appscrip-Task-Sagar.git
   cd <repository-directory>
   ```

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
