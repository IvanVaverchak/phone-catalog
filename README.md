**Phone Catalog React Website Overview:**

This project is a dynamic and responsive React website showcasing a catalog of mobile phones, tablets, and accessories. Leveraging TypeScript (TSX) for type safety and React for declarative UI, the website provides an engaging user experience.

**Technologies Used:**

**React with TypeScript (TSX):**

The project is built using React with TypeScript (TSX), combining the benefits of React for UI development and TypeScript for type safety.

**SCSS for Styling:**

The styling is organized using SCSS files per component, following BEM naming conventions for a modular and maintainable structure.

**Custom ProductSlider:**

Component, supporting navigation through buttons and touch gestures. It dynamically adjusts to screen sizes, utilizes touch events for intuitive scrolling, and includes features like infinite scrolling, favorites, and shopping cart functionality. The slider's responsive design enhances user experience across various devices.

**React Router:**

React Router is utilized for navigation between different pages, ensuring a smooth single-page application experience.

**LocalStorage for Cart Storage:**

The Cart items are stored in the LocalStorage, providing persistent storage across page reloads.

**Pagination and Sorting:**

The website incorporates pagination and sorting features for efficient product navigation and exploration.

**Debounced Search:**

A debounced search feature is implemented, enhancing the user experience by optimizing search queries.

**Libraries and Frameworks:**

**Styled Components:**

Styled Components are used to style React components, offering a component-based styling approach for better maintainability.

**GitHub Integration:**

The GitHub repository hosts the version-controlled codebase, facilitating collaborative development.

**Pages and Components Structure:**

The project is structured into pages, components, and helpers folders, enhancing organization and code separation.

**Header and Footer:**

The website includes a header with links to all pages, a logo, favorites, and a cart. Navigation is highlighted using NavLink. The footer includes a link to the GitHub repository and a "Back to top" button.

**Home Page:**

The homepage displays product sliders for hot prices and brand new items. Users can navigate through sliders using buttons or automatic swiping. A "Shop by category" section provides links to phones, tablets, and accessories.

**Phones, Tablets, and Accessories Pages:**

Individual pages for phones, tablets, and accessories display product lists, sortable and paginated. A loader is implemented for data fetching, and sorting and pagination options enhance user control.

**Product Details Page:**

The product details page provides information about a specific product, including tech specs and suggested products. Users can choose product pictures and navigate back to the previous page. Breadcrumbs are implemented for easy navigation.

**Cart and Favorites Pages:**

The cart page displays added items, allows removal and quantity adjustment, and includes a checkout button. The favorites page shows a list of favorited products.

**Search:**

A search component is added to filter products based on user input, with support for pagination, sorting, and debouncing.

**NotFound Page:**

A not-found page is implemented for URLs that do not match any routes, with a link back to the homepage.

This React project provides a comprehensive and user-friendly experience for exploring and interacting with the catalog of phones, tablets, and accessories.

[DEMO LINK](https://IvanVaverchak.github.io/phone-catalog/)
