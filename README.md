This project is a Recipe Finder Application built with React that lets users search for recipes and manage their favorites. It’s a Single-Page Application (SPA) that demonstrates a solid understanding of modern web development principles.

The core technologies and how they work together are:

React: The foundation of the application, used to build a dynamic and responsive user interface. Components like Navbar, Home, and Details were created to break down the UI into reusable and manageable pieces.

React Router DOM: Manages client-side routing, enabling smooth navigation between different pages (/, /favorites, and /recipe-item/:id) without full page reloads.

Context API: This is used for global state management. The GlobalContext provides a centralized way to handle data such as the search query (searchParam), the list of recipes (recipeList), and the user's favorites (favoritesList), making this data accessible to any component that needs it without prop drilling.

Tailwind CSS: A utility-first CSS framework used to style the application. It allowed for rapid UI development by applying classes directly in the JSX, creating a clean and modern design.

Forkify API: A third-party API used to fetch recipe data. The application uses fetch to make asynchronous requests to this API, retrieving recipe information based on the user's search input.
