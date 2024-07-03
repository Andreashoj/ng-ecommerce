# Frontend

Project Setup and Structure
    x Setting up the Angular project with Angular CLI.
    - Organizing the project structure (modules, components, services).

UI Components and Angular Material
    - Using Angular Material for UI components (e.g., navigation, cards, buttons).
    - Creating responsive layouts with Angular Flex Layout.

Product Listing
    - Service Layer: Create a service to fetch and manage product data.
    - Component Communication: Use @Input() and @Output() for communication between components.
    - Data Binding: One-way and two-way data binding for displaying and interacting with data.
    - Directives: Use structural directives (ngFor, ngIf) for rendering lists and conditional content.

Product Details
    - Routing: Set up Angular Router for navigation between the product list and product details.
    - Route Parameters: Fetch and display product details based on route parameters.

Search Functionality
    - Forms: Implement reactive forms for the search input.
    - RxJS: Use RxJS operators like debounceTime, distinctUntilChanged, and switchMap to handle asynchronous search queries.

Shopping Cart
    - State Management: Manage shopping cart state using a service or a state management library (e.g., NgRx).
    - Local Storage: Persist cart data in local storage to maintain state across sessions.

User Authentication (Optional)
    - Implement login and registration forms.
    - Use Angular services to manage authentication state and protect routes.

Animations
    - Use Angular animations for enhancing user interactions (e.g., adding items to the cart).



# Backend

Simple Backend Setup
    x Set up a basic .NET server to serve product data.
    x Create connection to frontend
    - Use Faker.js to generate and return dummy product data.

API Endpoints
    - Create RESTful API endpoints for products (e.g., GET /products, GET /products/)

Asynchronous Requests
    - Handle HTTP requests in Angular using the HttpClient module.
    - Use RxJS to handle the asynchronous nature of HTTP requests and responses.
